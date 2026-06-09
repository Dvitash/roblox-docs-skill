---
name: roblox-docs
description: >-
  REQUIRED before writing or editing Luau that touches Roblox engine APIs
  (Instance, Part, Model, BasePart, Services, enums). Look up signatures,
  method syntax (: not .), inheritance, and scriptability in local class docs.
  Triggers: IsA, CFrame, Material, Transparency, Size, Shape, Ball, Neon,
  ForceField, GetPivot, GetExtentsSize, CollectionService, ProximityPrompt,
  game:GetService, Part/Model creation, any Instance property or method.
---

# roblox-docs

Local reference for Roblox engine classes generated from the official Creator Docs repository.

## When to read (always)

Read this skill **before** writing the line when the change involves:

- Creating or mutating `Instance` / `Part` / `Model` / `BasePart`
- Calling any engine method (`IsA`, `GetPivot`, `GetExtentsSize`, `GetDescendants`, …)
- Setting `Material`, `Transparency`, `Size`, `Shape`, `CFrame`, `Parent`
- Using `game:GetService`, `CollectionService`, `Enum.*`

Then open `classes/<ClassName>.md` for the class you are using. For common mistakes (colon vs dot, Ball sizing), see [examples.md](examples.md).

**Enums are NOT guessable.** Before writing any `Enum.<X>.<Value>`, open `enums/<X>.md` and confirm the value is in its **Valid values** list. Do not assume a value exists because it "should" (e.g. `Enum.VerticalAlignment.Stretch` does not exist — the only values are `Center`, `Top`, `Bottom`).

## Lookup

- If you know the class name, read `classes/<ClassName>.md`.
- If you know the enum name, read `enums/<EnumName>.md` — it lists every valid item, its integer value, tags, and summary.
- If you only know behavior, a property, a method, or a service area, search `index.tsv` (classes) or `enums.tsv` (enums) first:

```bash
rg -i "<keyword>" index.tsv
rg -i "<keyword>" enums.tsv
```

- `index.tsv` columns are `ClassName`, `Superclass`, and `Summary`.
- `enums.tsv` columns are `EnumName`, space-separated `ItemNames`, and `Summary` — so `rg -i "stretch" enums.tsv` tells you which enum (if any) actually has a `Stretch` item.
- For inherited members, read the listed superclass and repeat up the chain.
- When multiple classes are plausible, read the smallest set needed to answer the task.

## Contents

- `classes/` contains one Markdown file per Roblox class.
- `enums/` contains one Markdown file per Roblox enum, with a table of every valid item.
- `index.tsv` is the search index for class names, superclass names, and one-line summaries.
- `enums.tsv` is the search index for enum names, their item names, and one-line summaries.
- `manifest.json` tracks source YAML SHA256 hashes so updates only regenerate changed classes and enums.
- `scripts/` contains the maintenance tooling for regenerating the local docs.

## Rules

- Read only relevant class files. Never bulk-read `classes/`.
- Do not rationalize or fill gaps from memory. If there is even a shadow of doubt about a Roblox Instance, class, service, property, method, event, enum, tag, inheritance relationship, or scriptability, look it up here.
- Treat this local reference as the verification source for Roblox engine API details available in this repo.
- Treat signatures, types, inheritance, member names, and tags as authoritative.
- Treat generated prose summaries as orientation; verify ambiguous behavior against the member signatures and tags in the same file.
- Only skip lookup when the task does not depend on Roblox engine API details.

## Maintenance

Only update the generated docs when the user asks for a refresh or the local reference appears stale.

Run from the skill directory; `update.ps1` clones or pulls `Roblox/creator-docs`, creates the virtualenv if needed, and regenerates `classes/`, `index.tsv`, and `manifest.json`:

```powershell
.\update.ps1
```

One-time setup can also be run directly:

```powershell
.\scripts\setup.ps1
```

```bash
./scripts/setup.sh
```

To run the generator manually:

```powershell
.\scripts\.venv\Scripts\python.exe scripts\update_docs.py --source <creator-docs-clone> --outdir .
```

```bash
./scripts/.venv/bin/python scripts/update_docs.py --source <creator-docs-clone> --outdir .
```

Requires Ollama with the summarizer model pulled on the inference host:

```bash
ollama pull QyrouNnet/summarizer:400m-q4_k_m
```

Env vars (optional):
- `OLLAMA_API_URL` — OpenAI-compatible endpoint (default `http://192.168.1.197:11434/v1`)
- `OLLAMA_MODEL` — model tag (default `QyrouNnet/summarizer:400m-q4_k_m`)

# roblox-docs

Local reference for Roblox engine classes, enums, and methods. Generated from the official [Roblox Creator Docs](https://github.com/Roblox/creator-docs) repository.

Use this Claude Code skill to look up Roblox API signatures, method syntax, inheritance, enum values, and scriptability before writing Luau code that touches the engine.

## Installation

1. Clone or download this repository
2. Place in your Claude Code skills directory:
   - **Project-level**: `.claude/skills/roblox-docs/`
   - **Global**: `~/.claude/skills/roblox-docs/`

3. The skill auto-triggers on references to Roblox engine classes (`Instance`, `Part`, `Model`, `BasePart`, `CFrame`, `Material`, `Size`, `Shape`, `Enum.*`, `game:GetService`, `CollectionService`, `ProximityPrompt`, etc.)

## Usage

### Look up a class

Open `classes/<ClassName>.md` to find:
- Properties and their types
- Methods with signatures
- Events and their arguments
- Inheritance chain
- Scriptability (Server/Client/Studio)

**Example:**
```
classes/Part.md → Part properties (Size, Material, Transparency, Color, etc.)
classes/Instance.md → Universal methods (IsA, GetChildren, FindFirstChild, Parent, etc.)
```

### Look up an enum

Open `enums/<EnumName>.md` to find every valid enum value and its integer representation.

**Important:** Enums are NOT guessable. Always verify the exact spelling in the enum file before writing `Enum.SomeEnum.SomeValue`.

**Example:** `Enum.VerticalAlignment` only has `Center`, `Top`, `Bottom` — not `Stretch`.

### Search indexes

Quick lookups without opening files:

```bash
# Find a class by keyword
rg -i "material" index.tsv

# Find an enum by keyword
rg -i "vertical" enums.tsv
```

- `index.tsv` columns: `ClassName`, `Superclass`, `Summary`
- `enums.tsv` columns: `EnumName`, space-separated `ItemNames`, `Summary`

## When to use

**Always read before writing code that touches:**

- Creating or mutating `Instance` / `Part` / `Model` / `BasePart`
- Calling any engine method (`IsA`, `GetPivot`, `GetExtentsSize`, `GetDescendants`, etc.)
- Setting properties (`Material`, `Transparency`, `Size`, `Shape`, `CFrame`, `Parent`)
- Using `game:GetService`, `CollectionService`, `Enum.*`

## Contents

- `classes/` — One Markdown file per Roblox class with full API reference
- `enums/` — One Markdown file per Roblox enum with all valid values
- `index.tsv` — Search index for class names, superclasses, and summaries
- `enums.tsv` — Search index for enum names, items, and summaries
- `SKILL.md` — Skill metadata and usage guide

## Data source

Generated from the official Roblox Creator Docs repository. This snapshot is current as of the build date in `SKILL.md`.

## License

MIT License — see LICENSE file

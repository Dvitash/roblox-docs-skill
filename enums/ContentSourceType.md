# Enum.ContentSourceType

The source type of a `Datatype.Content` value.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | Empty value with no source type. Does not reference any content or hold any non‑`nil` value. |
| `Uri` | 1 |  | An [asset URI](../../../projects/assets/index.md#asset-uris) `string` value contained in `Datatype.Content.Uri`. |
| `Object` | 2 |  | A non-`nil` `Class.Object` reference contained in `Datatype.Content.Object`. |
| `Opaque` | 3 |  | A non-`nil` `Opaque` reference contained in `Datatype.Content.Opaque`. |

**Valid values:** `Enum.ContentSourceType.None`, `Enum.ContentSourceType.Uri`, `Enum.ContentSourceType.Object`, `Enum.ContentSourceType.Opaque`

# Enum.RollOffMode

How `Class.Sound|Sounds` parented to a `Class.BasePart` or `Class.Attachment` attenuate (fade out) as the distance between the listener and the parent increases.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Inverse` | 0 |  | Volume attenuates from `Class.Sound.RollOffMinDistance` in an inverse manner, mirroring how sounds attenuate in the real world. This is done through `Class.Sound.RollOffMinDistance`/`distance`, where `distance` is the `Datatype.Vector3.Magnitude` between the audio source and the audio listener. |
| `Linear` | 1 |  | Volume attenuates between `Class.Sound.RollOffMinDistance` and `Class.Sound.RollOffMaxDistance` with a linear relationship. This is done through (`Class.Sound.RollOffMaxDistance`/`distance`)/(`Class.Sound.RollOffMaxDistance`-`Class.Sound.RollOffMinDistance`), where `distance` is the `Datatype.Vector3.Magnitude` between the audio source and the audio listener. |
| `LinearSquare` | 2 |  | Volume attenuates between `Class.Sound.RollOffMinDistance` and `Class.Sound.RollOffMaxDistance` with a linear squared relationship. This is done through squaring `Linear`. |
| `InverseTapered` | 3 |  | A hybrid model which follows the `Inverse` model when close to `Class.Sound.RollOffMinDistance` and the `LinearSquare` model when close to `Class.Sound.RollOffMaxDistance`. This is done by taking the lesser of `Inverse` and `LinearSquare`. |

**Valid values:** `Enum.RollOffMode.Inverse`, `Enum.RollOffMode.Linear`, `Enum.RollOffMode.LinearSquare`, `Enum.RollOffMode.InverseTapered`

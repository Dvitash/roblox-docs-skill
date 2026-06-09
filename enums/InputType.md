# Enum.InputType

The InputType Enum controls the SurfaceInputs of `Class.Part`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `NoInput` | 0 |  | Behaves like a weld and does nothing. |
| `Constant` | 12 |  | Rotate at a constant velocity of `Class.BasePart` `ParamB`. |
| `Sin` | 13 |  | Rotate at a velocity of: `ParamA * math.sin(workspace.DistributedGameTime * ParamB)`, where `Class.BasePart` `ParamA` determines the maximum speed at which the part spins, and `Class.BasePart` `ParamB` determines how frequently it changes direction. |

**Valid values:** `Enum.InputType.NoInput`, `Enum.InputType.Constant`, `Enum.InputType.Sin`

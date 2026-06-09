# Enum.PredictionMode

Enum used with `Class.RunService:SetPredictionMode()` to define the prediction mode for the instance.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Automatic` | 0 |  | The engine will automatically decide if this instance should be predicted or not. Currently, only `Class.BasePart\|BaseParts` near the local player character's `Class.Humanoid` will be predicted within a dynamic radius that grows and shrinks based on the device's capability to handle the simulation load. |
| `On` | 1 |  | The instance will be predicted. Mismatches in the attributes of this instance between the client and server will cause a rollback and resimulation. If the instance is a `Class.BasePart`, its physics properties will be predicted ahead of the replicated authoritative server state. |
| `Off` | 2 |  | The instance will **not** be predicted. Regular network ownership semantics apply. |

**Valid values:** `Enum.PredictionMode.Automatic`, `Enum.PredictionMode.On`, `Enum.PredictionMode.Off`

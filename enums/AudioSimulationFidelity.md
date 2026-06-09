# Enum.AudioSimulationFidelity

Enum which determines how detailed audio simulation should be for `Class.AudioEmitter|AudioEmitters` and `Class.AudioListener|AudioListeners`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | No acoustic simulation occurs; only direction and distance are taken into account. |
| `Automatic` | 1 |  | The audio engine simulates transmission, diffraction, and reflections at a level of detail suitable to most devices. |

**Valid values:** `Enum.AudioSimulationFidelity.None`, `Enum.AudioSimulationFidelity.Automatic`

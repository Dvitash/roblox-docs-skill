# Enum.PhysicsSteppingMethod

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | The current default is `Adaptive`. |
| `Fixed` | 1 |  | All simulated assemblies inside the workspace will advance forward at 240 Hz. This option is best for optimal stability and simulation accuracy. |
| `Adaptive` | 2 |  | The engine attempts to assign optimal simulation rates for individual assemblies of either 240 Hz, 120 Hz, or 60 Hz. This setting is optimized for performance. |

**Valid values:** `Enum.PhysicsSteppingMethod.Default`, `Enum.PhysicsSteppingMethod.Fixed`, `Enum.PhysicsSteppingMethod.Adaptive`

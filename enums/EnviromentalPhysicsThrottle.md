# Enum.EnviromentalPhysicsThrottle

Used to control the throttle rate of Roblox's physics engine.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `DefaultAuto` | 0 |  | Automatically adjusts throttle level based on performance. |
| `Disabled` | 1 |  | No throttling; every physics step runs. |
| `Always` | 2 |  | Maximum throttling; physics is effectively frozen. |
| `Skip2` | 3 |  | Runs 1 out of every 2 steps (50% reduction). If `Class.Workspace.PhysicsSteppingMethod` is set to `Enum.PhysicsSteppingMethod.Adaptive\|Adaptive`, skipping is based on groups of 4 steps instead of individual steps. |
| `Skip4` | 4 |  | Runs 1 out of every 4 steps (75% reduction). If `Class.Workspace.PhysicsSteppingMethod` is set to `Enum.PhysicsSteppingMethod.Adaptive\|Adaptive`, skipping is based on groups of 4 steps instead of individual steps. |
| `Skip8` | 5 |  | Runs 1 out of every 8 steps (87.5% reduction). If `Class.Workspace.PhysicsSteppingMethod` is set to `Enum.PhysicsSteppingMethod.Adaptive\|Adaptive`, skipping is based on groups of 4 steps instead of individual steps. |
| `Skip16` | 6 |  | Runs 1 out of every 16 steps (93.75% reduction). If `Class.Workspace.PhysicsSteppingMethod` is set to `Enum.PhysicsSteppingMethod.Adaptive\|Adaptive`, skipping is based on groups of 4 steps instead of individual steps. |

**Valid values:** `Enum.EnviromentalPhysicsThrottle.DefaultAuto`, `Enum.EnviromentalPhysicsThrottle.Disabled`, `Enum.EnviromentalPhysicsThrottle.Always`, `Enum.EnviromentalPhysicsThrottle.Skip2`, `Enum.EnviromentalPhysicsThrottle.Skip4`, `Enum.EnviromentalPhysicsThrottle.Skip8`, `Enum.EnviromentalPhysicsThrottle.Skip16`

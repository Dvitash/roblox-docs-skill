# Enum.HumanoidStateType

Describes the physics control states within the Humanoid.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `FallingDown` | 0 |  | The Humanoid has been tripped, and will attempt to get up in a few moments. |
| `Ragdoll` | 1 |  | (Deprecated) The Humanoid has been hit by a fast moving object (uncontrolled falling). _The Humanoid can recover from this._ This state has to be set and unset manually using `Class.Humanoid:ChangeState()`. |
| `GettingUp` | 2 |  | The Humanoid is getting back on their feet after FallingDown or Ragdoll. |
| `Jumping` | 3 |  | The Humanoid just jumped. (Check `Class.Humanoid.Jump`). This state lasts only briefly. This state normally transitions into either Landed, if on the ground, or Freefall, if still in the air. |
| `Swimming` | 4 |  | The Humanoid is currently swimming in `Class.Terrain` water. |
| `Freefall` | 5 |  | The Humanoid is currently freefalling (jumped from a height or fell off a ledge). |
| `Flying` | 6 |  | When set, the Humanoid won't be animated, as with the `Class.Humanoid.PlatformStand` property. This state lasts as long as the player flies. |
| `Landed` | 7 |  | The Humanoid touched the ground after a Freefall. This state lasts only briefly. |
| `Running` | 8 |  | Currently running while on the ground. |
| `RunningNoPhysics` | 10 |  | (Deprecated) Currently running and not near other physical objects. |
| `StrafingNoPhysics` | 11 |  | Not currently used with default Humanoid. Cannot be set with `Class.Humanoid:ChangeState()`. |
| `Climbing` | 12 |  | The Humanoid is climbing (e.g. up a `Class.TrussPart` or ladder). |
| `Seated` | 13 |  | The Humanoid is currently sitting in a Seat or VehicleSeat. Check the `Class.Humanoid.Sit` property. |
| `PlatformStanding` | 14 |  | The Humanoid is platformstanding. Check the `Class.Humanoid.PlatformStand` property. |
| `Dead` | 15 |  | The Humanoid died. Changing a Humanoid's state to this state will kill it. |
| `Physics` | 16 |  | The Humanoid doesn't apply any force on its own and will not automatically transition to any other state. This state has to be set and unset manually using `Class.Humanoid:ChangeState()`. |
| `None` | 18 |  | Unusable placeholder in case an unknown state gets triggered internally. |

**Valid values:** `Enum.HumanoidStateType.FallingDown`, `Enum.HumanoidStateType.Ragdoll`, `Enum.HumanoidStateType.GettingUp`, `Enum.HumanoidStateType.Jumping`, `Enum.HumanoidStateType.Swimming`, `Enum.HumanoidStateType.Freefall`, `Enum.HumanoidStateType.Flying`, `Enum.HumanoidStateType.Landed`, `Enum.HumanoidStateType.Running`, `Enum.HumanoidStateType.RunningNoPhysics`, `Enum.HumanoidStateType.StrafingNoPhysics`, `Enum.HumanoidStateType.Climbing`, `Enum.HumanoidStateType.Seated`, `Enum.HumanoidStateType.PlatformStanding`, `Enum.HumanoidStateType.Dead`, `Enum.HumanoidStateType.Physics`, `Enum.HumanoidStateType.None`

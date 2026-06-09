# Enum.HumanoidDisplayDistanceType

HumanoidDisplayDistanceType determines how `Class.Humanoid.HealthDisplayDistance`, and `Class.Humanoid.NameDisplayDistance` are used in determining whether a players's name and health are visible to other players.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Viewer` | 0 |  | A player selecting `Viewer` on their `Class.Humanoid` will see the Name and healthbar of other players if those other players are within the distance settings set in the `Class.Humanoid` selecting `Viewer` (this can be thought of as the lowest priority, and will not be taken into account if other players are selecting 'Subject' or 'None'). |
| `Subject` | 1 |  | A player selecting `Subject` on their `Class.Humanoid` will allow other players to see their Name and healthbar if those other players are within the distance settings set in the `Class.Humanoid` selecting `Subject` (this can be thought of as the second highest priority). |
| `None` | 2 |  | A player selecting `None` on their `Class.Humanoid` will not have their Name and healthbar displayed to other players under any circumstance (this can be thought of as the highest priority). |

**Valid values:** `Enum.HumanoidDisplayDistanceType.Viewer`, `Enum.HumanoidDisplayDistanceType.Subject`, `Enum.HumanoidDisplayDistanceType.None`

# Enum.AnimationPriority

The AnimationPriority Enum determines how concurrently-playing AnimationTracks contribute to the final animation.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Idle` | 0 |  | (6) - Recommended priority for character idle animations. |
| `Movement` | 1 |  | (5) - Recommended priority for walk, run, swim, climb, and other locomotion animations. |
| `Action` | 2 |  | (4) - Recommended priority for character actions that must override idle and locomotion animations. |
| `Action2` | 3 |  | (3) - Action2 will override Action. |
| `Action3` | 4 |  | (2) - Action3 will override Action2. |
| `Action4` | 5 |  | (1) - Action4 is the highest priority available, overriding all other priority values. |
| `Core` | 1000 |  | (7) - Lowest priority, intended for use by Roblox default animations and catalog animation bundles. |

**Valid values:** `Enum.AnimationPriority.Idle`, `Enum.AnimationPriority.Movement`, `Enum.AnimationPriority.Action`, `Enum.AnimationPriority.Action2`, `Enum.AnimationPriority.Action3`, `Enum.AnimationPriority.Action4`, `Enum.AnimationPriority.Core`

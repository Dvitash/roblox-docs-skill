# Pose

**Superclass:** [PoseBase](PoseBase.md)

Poses are fundamental building blocks of animations, holding `Datatype.CFrame`s to apply to connected `Class.Motor6D`s.

## Properties
### `Pose.CFrame`
- **Type:** `CFrame`
- **Summary:** This `Datatype.CFrame` applies to the `Class.Motor6D` corresponding with the `Class.Pose` when the `Class.Motor6D.Transform` is changed.

### `Pose.MaskWeight`
- **Type:** `float`
- **Tags:** NotReplicated, Deprecated

## Methods
### `Pose:AddSubPose(pose: [Instance](Instance.md)) -> ()`
- **Summary:** Adds a sub `Class.Pose` to the `Class.Pose` by parenting it.

### `Pose:GetSubPoses() -> Instances`
- **Summary:** Returns an array containing all sub `Class.Pose|Poses` that have been added to a `Class.Pose`.

### `Pose:RemoveSubPose(pose: [Instance](Instance.md)) -> ()`
- **Summary:** Removes a sub `Class.Pose` from the `Class.Pose` by parenting it to `nil`.

# IKControl

**Superclass:** [Instance](Instance.md)

IKControl is a class used to generate procedural animation poses using Inverse Kinematics (IK) by specifying the desired movement of parts between the IK controls and the target.

## Properties
### `IKControl.ChainRoot`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The last part that you are interested in moving your character. For example, the upper arm. Must be an ancestor of `Class.IKControl.EndEffector|EndEffector` and be a `Class.BasePart` or a `Class.Bone` in your character.

### `IKControl.Enabled`
- **Type:** `boolean`
- **Summary:** Toggles the control on and off. True by default.

### `IKControl.EndEffector`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The part that you are interested in moving to reach the `Class.IKControl.Target|Target`. For example, the hand of your character. Must be a descendant of `Class.IKControl.ChainRoot|ChainRoot` and be a `Class.BasePart` or a `Class.Bone` in your character.

### `IKControl.EndEffectorOffset`
- **Type:** `CFrame`
- **Summary:** An additional offset applied on top of the `Class.IKControl.EndEffector|EndEffector` in its local space to change where it moves.

### `IKControl.Offset`
- **Type:** `CFrame`
- **Summary:** An additional offset applied on top of the `Class.IKControl.Target|Target` to change where the `Class.IKControl.EndEffector|EndEffector` moves.

### `IKControl.Pole`
- **Type:** `[Instance](Instance.md)`
- **Summary:** An optional instance that determines which way the chain bends. You can use this to specify which way an elbow or knee bends.

### `IKControl.Priority`
- **Type:** `int`
- **Summary:** Specifies the order in which controls are solved. Higher values have higher priority.

### `IKControl.SmoothTime`
- **Type:** `float`
- **Summary:** Specifies the average number of seconds that it takes for the `Class.IKControl.EndEffector|EndEffector` to smoothly reach the `Class.IKControl.Target|Target`.

### `IKControl.Target`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The object that the `Class.IKControl.EndEffector|EndEffector` reaches for or points at. It can be anything that has a position in the world, such as `Class.BasePart`, `Class.Attachment`, `Class.Bone`, or `Class.Motor6D`.

### `IKControl.Type`
- **Type:** `IKControlType`
- **Summary:** Specifies how the solver satisfies this control.

### `IKControl.Weight`
- **Type:** `float`
- **Summary:** Specifies the weight of the IK control target. Should be in the [0, 1] range.

## Methods
### `IKControl:GetChainCount() -> int`

### `IKControl:GetChainLength() -> float`

### `IKControl:GetNodeLocalCFrame(index: int) -> CFrame`

### `IKControl:GetNodeWorldCFrame(index: int) -> CFrame`

### `IKControl:GetRawFinalTarget() -> CFrame`

### `IKControl:GetSmoothedFinalTarget() -> CFrame`

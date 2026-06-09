# EulerRotationCurve

**Superclass:** [Instance](Instance.md)

EulerRotationCurve is a 3D rotation curve represented by a group of three `Class.FloatCurve` objects, allowing for sampling and rotation at specific times.

## Properties
### `EulerRotationCurve.RotationOrder`
- **Type:** `RotationOrder`
- **Summary:** Euler angles rotation order.

## Methods
### `EulerRotationCurve:GetAnglesAtTime(time: float) -> Array`
- **Summary:** Samples the three `Class.FloatCurve|FloatCurves` (`X`, `Y`, `Z`) at the passed `time` argument and returns the result as three Euler angles.

### `EulerRotationCurve:GetRotationAtTime(time: float) -> CFrame`
- **Summary:** Samples the `Class.EulerRotationCurve` at a given `time` and returns the corresponding rotation.

### `EulerRotationCurve:X() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the `X` Euler angle channel.

### `EulerRotationCurve:Y() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the `Y` Euler angle channel.

### `EulerRotationCurve:Z() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the `Z` Euler angle channel.

# Vector3Curve

**Superclass:** [Instance](Instance.md)

Vector3Curve is a class representing a 3D vector curve, grouping three `Class.FloatCurve` instances. It allows accessing the values of the three axes simultaneously via `getValueAtTime()`.

## Methods
### `Vector3Curve:GetValueAtTime(time: float) -> Array`
- **Summary:** Returns the three `Class.FloatCurve|FloatCurves` (X, Y, Z) at the passed time argument.

### `Vector3Curve:X() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the X channel (the first child instance of type `Class.FloatCurve` named `X`).

### `Vector3Curve:Y() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the Y channel (the first child instance of type `Class.FloatCurve` named `Y`).

### `Vector3Curve:Z() -> [FloatCurve](FloatCurve.md)`
- **Summary:** Returns the `Class.FloatCurve` controlling the Z channel (the first child instance of type `Class.FloatCurve` named `Z`).

# CompositeValueCurve

**Superclass:** [Instance](Instance.md)

Animation curves group child `Class.FloatCurve|FloatCurves` to animate different components of a non-unary value.

## Properties
### `CompositeValueCurve.CurveType`
- **Type:** `CompositeValueCurveType`
- **Summary:** The type of value animated by this `Class.CompositeValueCurve`.

## Methods
### `CompositeValueCurve:GetComponentCurves() -> List<[FloatCurve](FloatCurve.md)>`
- **Summary:** Returns the child curves with the given names for the `Class.CompositeValueCurve.CurveType|CurveType` of this `Class.CompositeValueCurve`.

### `CompositeValueCurve:GetValueAtTime(time: float) -> Variant`
- **Summary:** Returns the sampled animated value at the passed `time` argument.

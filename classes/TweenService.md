# TweenService

**Superclass:** [Instance](Instance.md)

TweenService is a class used to create `Class.Tween|Tweens` that interpolate the properties of instances, handling multiple properties and preventing simultaneous modifications.

## Tags
- NotCreatable
- Service

## Methods
### `TweenService:Create(instance: [Instance](Instance.md), tweenInfo: TweenInfo, propertyTable: Dictionary) -> [Tween](Tween.md)`
- **Summary:** Creates a new `Class.Tween` given the object whose properties are to be tweened, a `Datatype.TweenInfo`, and a dictionary of goal property values.

### `TweenService:GetValue(alpha: float, easingStyle: EasingStyle, easingDirection: EasingDirection) -> float`
- **Summary:** Calculates a new alpha given an `Enum.EasingStyle` and `Enum.EasingDirection`.

### `TweenService:SmoothDamp(current: Variant, target: Variant, velocity: Variant, smoothTime: float, maxSpeed: float?, dt: float?) -> Tuple`
- **Summary:** Smoothly interpolates a value towards a target, simulating a critically damped spring.

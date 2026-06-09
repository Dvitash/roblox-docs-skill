# HapticService

**Superclass:** [Instance](Instance.md)

HapticService is a class that provides haptic feedback to controllers and devices. It is superseded by `Class.HapticEffect`, which supports multiple effects, looped effects, and customizable haptics.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `HapticService:GetMotor(inputType: UserInputType, vibrationMotor: VibrationMotor) -> Tuple`
- **Summary:** Returns the current vibration value set to the specified `Class.InputObject.UserInputType|UserInputType` and `Enum.VibrationMotor`.

### `HapticService:IsMotorSupported(inputType: UserInputType, vibrationMotor: VibrationMotor) -> boolean`
- **Summary:** Returns `true` if the specified motor is available to be used with the specified `Enum.UserInputType`.

### `HapticService:IsVibrationSupported(inputType: UserInputType) -> boolean`
- **Summary:** Returns `true` if the specified `Enum.UserInputType` supports haptic feedback.

### `HapticService:SetMotor(inputType: UserInputType, vibrationMotor: VibrationMotor, vibrationValues: Tuple) -> ()`
- **Summary:** Sets the vibration intensity of the specified `Class.InputObject.UserInputType|UserInputType` and `Enum.VibrationMotor`.

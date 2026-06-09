# VehicleSeat

**Superclass:** [BasePart](BasePart.md)

The `VehicleSeat` class is a seat object that controls a vehicle by linking the player to it, forwarding movement inputs, and allowing control via avatar behavior.

## Properties
### `VehicleSeat.AreHingesDetected`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Displays how many hinges are detected by the `VehicleSeat`. Useful for debugging vehicle designs.

### `VehicleSeat.Disabled`
- **Type:** `boolean`
- **Summary:** Toggles whether the `VehicleSeat` is active or not.

### `VehicleSeat.HeadsUpDisplay`
- **Type:** `boolean`
- **Summary:** If `true`, a UI speed bar will be displayed on screen that tells you what speed the vehicle is moving at.

### `VehicleSeat.MaxSpeed`
- **Type:** `float`
- **Summary:** The maximum speed that can be attained.

### `VehicleSeat.Occupant`
- **Type:** `[Humanoid](Humanoid.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Class.Humanoid` that is sitting in the seat.

### `VehicleSeat.Steer`
- **Type:** `int`
- **Tags:** NotReplicated
- **Summary:** The direction of movement, tied to left and right movement inputs.

### `VehicleSeat.SteerFloat`
- **Type:** `float`
- **Summary:** The left-to-right movement float, tied to left and right movement inputs.

### `VehicleSeat.Throttle`
- **Type:** `int`
- **Tags:** NotReplicated
- **Summary:** The direction of throttle, tied to forward and backward movement inputs.

### `VehicleSeat.ThrottleFloat`
- **Type:** `float`
- **Summary:** The forward-to-reverse throttle float, tied to forward and backward movement inputs.

### `VehicleSeat.Torque`
- **Type:** `float`
- **Summary:** How fast the vehicle will be able to attain `Class.VehicleSeat.MaxSpeed|MaxSpeed`.

### `VehicleSeat.TurnSpeed`
- **Type:** `float`
- **Summary:** The speed at which the vehicle will turn. Higher numbers can cause problems and are not necessarily better.

## Methods
### `VehicleSeat:Sit(humanoid: [Instance](Instance.md)) -> ()`
- **Summary:** Forces the character with the specified `Class.Humanoid` to sit in the `VehicleSeat`.

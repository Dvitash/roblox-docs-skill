# SkateboardPlatform

**Superclass:** [Part](Part.md)

The SkateboardPlatform class is a base class for creating skateboards, and it includes methods to manage user input and create vehicles.

## Tags
- Deprecated

## Properties
### `SkateboardPlatform.Controller`
- **Type:** `[SkateboardController](SkateboardController.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The SkateboardPlatform's active SkateboardController.

### `SkateboardPlatform.ControllingHumanoid`
- **Type:** `[Humanoid](Humanoid.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The `Class.Humanoid` that is controlling the SkateboardPlatform.

### `SkateboardPlatform.Steer`
- **Type:** `int`
- **Summary:** The direction of movement, tied to the keys A and D. Must be 1 (right), 0 (straight), or -1 (left). Will refresh back to 0 unless constantly set.

### `SkateboardPlatform.StickyWheels`
- **Type:** `boolean`
- **Summary:** If true, wheels won't roll without user input.

### `SkateboardPlatform.Throttle`
- **Type:** `int`
- **Summary:** The direction of movement, tied to the keys W and S. Must be an integer 1 (forward), 0 (null), or -1 (reverse). Will refresh back to 0 unless constantly set.

## Methods
### `SkateboardPlatform:ApplySpecificImpulse(impulseWorld: Vector3) -> ()`
- **Summary:** Adds ''impulseWorld'' to the SkateboardPlatform's `Class.BasePart.Velocity`.

## Events
### `SkateboardPlatform.Equipped(humanoid: [Instance](Instance.md), skateboardController: [Instance](Instance.md))`
- **Summary:** Fired when the skateboard is equipped.

### `SkateboardPlatform.equipped(humanoid: [Instance](Instance.md), skateboardController: [Instance](Instance.md))`
- **Tags:** Deprecated

### `SkateboardPlatform.MoveStateChanged(newState: MoveState, oldState: MoveState)`
- **Summary:** Fired when the SkateboardPlatform's `Class.SkateboardPlatform.ControllingHumanoid` changes the force being used on the SkateboardPlatform.

### `SkateboardPlatform.Unequipped(humanoid: [Instance](Instance.md))`
- **Summary:** Fired whenever the skateboard is unequipped.

### `SkateboardPlatform.unequipped(humanoid: [Instance](Instance.md))`
- **Tags:** Deprecated

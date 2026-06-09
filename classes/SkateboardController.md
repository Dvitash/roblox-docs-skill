# SkateboardController

**Superclass:** [Controller](Controller.md)

The SkateboardController class is a class responsible for translating PlayerActions to movements using `Class.SkateboardPlatform`. It handles steering and throttle direction updates.

## Properties
### `SkateboardController.Steer`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The direction of movement, tied to the keys A and D. Must be 1 (right), 0 (straight), or -1 (left). Will refresh back to 0 unless constantly set.

### `SkateboardController.Throttle`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The direction of movement, tied to the keys W and S. Must be an integer 1 (forward), 0 (null), or -1 (reverse). Will refresh back to 0 unless constantly set.

## Events
### `SkateboardController.AxisChanged(axis: string)`
- **Summary:** Fired when any input state of the skateboard controller is updated.

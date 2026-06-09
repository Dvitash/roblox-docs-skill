# InputObject

**Superclass:** [Instance](Instance.md)

InputObject is a class used to represent a single user input, which includes properties like `Class.InputObject.UserInputState` and `Class.InputObject.Position`.

## Tags
- NotCreatable

## Properties
### `InputObject.Delta`
- **Type:** `Vector3`
- **Summary:** A `Datatype.Vector3` describing the delta between input movements.

### `InputObject.KeyCode`
- **Type:** `KeyCode`
- **Summary:** Contains an Enum that describes the kind of input used.

### `InputObject.Position`
- **Type:** `Vector3`
- **Summary:** A `Datatype.Vector3` describing the positional value of this input.

### `InputObject.UserInputState`
- **Type:** `UserInputState`
- **Summary:** Describes the state of an input being performed, following a specific flow depending on the `Class.InputObject.UserInputType|UserInputType`.

### `InputObject.UserInputType`
- **Type:** `UserInputType`
- **Summary:** Describes the kind of input being performed (mouse, keyboard, gamepad, touch, etc.).

## Methods
### `InputObject:IsModifierKeyDown(modifierKey: ModifierKey) -> boolean`
- **Summary:** Returns whether the passed in modifier key is down.

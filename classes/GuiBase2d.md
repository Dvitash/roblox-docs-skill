# GuiBase2d

**Superclass:** [GuiBase](GuiBase.md)

The `GuiBase2d` class is an abstract class inherited by `Class.GuiObject` and represents a 2D `Class.GuiObject` that inherits from `Class.GuiBase2d`. It provides methods for setting absolute position, rotation, and size, along with methods for localizing descendants.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `GuiBase2d.AbsolutePosition`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the actual screen position of a `Class.GuiBase2d` element, in pixels.

### `GuiBase2d.AbsoluteRotation`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the actual screen rotation of a `Class.GuiBase2d` element, in degrees.

### `GuiBase2d.AbsoluteSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the actual screen size of a `Class.GuiBase2d` element, in pixels.

### `GuiBase2d.AutoLocalize`
- **Type:** `boolean`
- **Summary:** When set to `true`, localization will be applied to this `Class.GuiBase2d` and its descendants.

### `GuiBase2d.Localize`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Automatically set to true when a localization table's `Class.LocalizationTable.Root` targets this object, or an ancestor of this object.

### `GuiBase2d.RootLocalizationTable`
- **Type:** `[LocalizationTable](LocalizationTable.md)`
- **Summary:** A reference to a `Class.LocalizationTable` to be used to apply automated localization to this `Class.GuiBase2d` and its descendants.

### `GuiBase2d.SelectionBehaviorDown`
- **Type:** `SelectionBehavior`
- **Summary:** Customizes gamepad selection behavior in the down direction.

### `GuiBase2d.SelectionBehaviorLeft`
- **Type:** `SelectionBehavior`
- **Summary:** Customizes gamepad selection behavior in the left direction.

### `GuiBase2d.SelectionBehaviorRight`
- **Type:** `SelectionBehavior`
- **Summary:** Customizes gamepad selection behavior in the right direction.

### `GuiBase2d.SelectionBehaviorUp`
- **Type:** `SelectionBehavior`
- **Summary:** Customizes gamepad selection behavior in the up direction.

### `GuiBase2d.SelectionGroup`
- **Type:** `boolean`
- **Summary:** Allows customization of gamepad selection movement.

## Events
### `GuiBase2d.SelectionChanged(amISelected: boolean, previousSelection: [GuiObject](GuiObject.md), newSelection: [GuiObject](GuiObject.md))`
- **Summary:** Fires when the gamepad selection moves to, leaves, or changes within the connected `Class.GuiBase2d` or any descendant `Class.GuiObject|GuiObjects`.

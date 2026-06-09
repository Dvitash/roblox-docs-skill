# Controller

**Superclass:** [Instance](Instance.md)

The `Controller` class is the base class for controller objects, such as `Class.HumanoidController`, and contains methods for binding and unbinding buttons.

## Tags
- NotCreatable

## Methods
### `Controller:BindButton(button: Button, caption: string) -> ()`
- **Summary:** Activates an overriding bind on the specified button.

### `Controller:bindButton(button: Button, caption: string) -> ()`
- **Tags:** Deprecated

### `Controller:GetButton(button: Button) -> boolean`
- **Summary:** Returns whether or not Button is being pressed.

### `Controller:getButton(button: Button) -> boolean`
- **Tags:** Deprecated

### `Controller:UnbindButton(button: Button) -> ()`
- **Summary:** Removes the bind on button.

## Events
### `Controller.ButtonChanged(button: Button)`
- **Summary:** Fired when the pressed state of a bound button is changed. This event can be used in conjunction with `Class.Controller:GetButton()` to see whether a bound button is being pressed down or not.

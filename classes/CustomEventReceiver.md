# CustomEventReceiver

**Superclass:** [Instance](Instance.md)

This file contains a `CustomEventReceiver` class, along with methods to handle attaching and disconnecting events, and events that fire when the source property is changed.

## Tags
- Deprecated

## Properties
### `CustomEventReceiver.Source`
- **Type:** `[Instance](Instance.md)`
- **Summary:** Attaches the `Class.CustomEventReceiver` object to a `Class.CustomEvent`.

## Methods
### `CustomEventReceiver:GetCurrentValue() -> float`
- **Summary:** Returns the current value of the receiver's `Class.CustomEventReceiver.Source` property.

## Events
### `CustomEventReceiver.EventConnected(event: [Instance](Instance.md))`
- **Summary:** Fires when the receiver is attached to a different `Class.CustomEvent`, when the `Class.CustomEventReceiver.Source` property is changed.

### `CustomEventReceiver.EventDisconnected(event: [Instance](Instance.md))`
- **Summary:** Fires when the receiver is attached to a different `Class.CustomEvent` instance when the `Class.CustomEventReceiver.Source` property is changed.

### `CustomEventReceiver.SourceValueChanged(newValue: float)`
- **Summary:** Fires when the value of the CustomEvent's source is changed, passing the CustomEvent's new value.

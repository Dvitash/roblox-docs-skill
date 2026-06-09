# CustomEvent

**Superclass:** [Instance](Instance.md)

CustomEvent is a class that represents a receiver connected to the `Class.CustomEvent`. It inherits from `Instance` and has specific methods for setting and disconnecting receivers.

## Tags
- Deprecated

## Methods
### `CustomEvent:GetAttachedReceivers() -> Instances`
- **Summary:** Returns the `Class.CustomEventReceiver|CustomEventReceivers` that are connected to the `Class.CustomEvent`.

### `CustomEvent:SetValue(newValue: float) -> ()`
- **Summary:** Sets the value of the `Class.CustomEvent` and fires the `Class.CustomEventReceiver.SourceValueChanged` event for all connected `CustomEventReceiver|receivers`.

## Events
### `CustomEvent.ReceiverConnected(receiver: [Instance](Instance.md))`
- **Summary:** Fires when a receiver is connected to the `Class.CustomEvent`.

### `CustomEvent.ReceiverDisconnected(receiver: [Instance](Instance.md))`
- **Summary:** Fires when a receiver is disconnected from the `Class.CustomEvent`.

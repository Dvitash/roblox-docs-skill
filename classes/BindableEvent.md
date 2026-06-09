# BindableEvent

**Superclass:** [Instance](Instance.md)

BindableEvent is an object that allows scripts to communicate custom events via asynchronous one-way communication between the same script and other connected functions.

## Methods
### `BindableEvent:[Fire](Fire.md)(arguments: Tuple) -> ()`
- **Summary:** Fires the `Class.BindableEvent` which in turn fires the `Class.BindableEvent.Event|Event` event.

## Events
### `BindableEvent.Event(arguments: Tuple)`
- **Summary:** Fires when any script calls the `Class.BindableEvent:Fire()|Fire()` method on the same `Class.BindableEvent` instance.

# BindableFunction

**Superclass:** [Instance](Instance.md)

BindableFunction is a class in Roblox that allows for synchronous two-way communication between scripts on the same side of the client-server boundary. It enables manual invocation of a callback function until it is found.

## Methods
### `BindableFunction:Invoke(arguments: Tuple) -> Tuple`
- **Tags:** Yields
- **Summary:** Invokes the `Class.BindableFunction` which in turn calls the `Class.BindableFunction.OnInvoke|OnInvoke` callback, returning any values returned by the callback.

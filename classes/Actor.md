# Actor

**Superclass:** [Model](Model.md)

An `Actor` is a container for code that can be safely split into its own thread, allowing multiple scripts to run in separate threads.

## Methods
### `Actor:BindToMessage(topic: string, function: Function) -> RBXScriptConnection`
- **Summary:** Binds a Luau callback to a message with the specified topic.

### `Actor:BindToMessageParallel(topic: string, function: Function) -> RBXScriptConnection`
- **Summary:** Binds a Luau callback to a message with the specified topic.

### `Actor:SendMessage(topic: string, message: Tuple) -> ()`
- **Summary:** Sends a message to an Actor.

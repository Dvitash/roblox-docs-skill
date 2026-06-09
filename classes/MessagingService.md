# MessagingService

**Superclass:** [Instance](Instance.md)

MessagingService is a class for allowing servers of the same experience to communicate with each other in real time, typically within 1-2 seconds using developer-defined topics.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `MessagingService:PublishAsync(topic: string, message: Variant) -> ()`
- **Tags:** Yields
- **Summary:** Invokes the supplied callback whenever a message is pushed to the topic.

### `MessagingService:SubscribeAsync(topic: string, callback: Function) -> RBXScriptConnection`
- **Tags:** Yields
- **Summary:** Begins listening to the given topic.

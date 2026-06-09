# ModerationService

**Superclass:** [Instance](Instance.md)

ModerationService is a class representing a moderation service, which handles content review and management. It includes methods for binding content to reviews, creating content, and performing asynchronous reviews.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ModerationService:BindReviewableContentEventProcessor(priority: int, callback: Function) -> RBXScriptConnection`

### `ModerationService:CreateReviewableContentAsync(config: Dictionary) -> string`
- **Tags:** Yields

### `ModerationService:CreateReviewableContentKey(content: Content) -> string`

### `ModerationService:InternalRequestReviewableContentReviewAsync(config: Dictionary) -> ()`
- **Tags:** Yields

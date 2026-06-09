# ExperienceNotificationService

**Superclass:** [Instance](Instance.md)

This file contains methods for validating users and prompting them to enable experience notifications, along with documentation for the `ExperienceNotificationService` class.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `ExperienceNotificationService:CanPromptOptInAsync() -> boolean`
- **Tags:** Yields
- **Summary:** Indicates whether the local player can be prompted to enable notifications.

### `ExperienceNotificationService:PromptOptIn() -> ()`
- **Summary:** Shows an in-experience prompt for the local player to enable notifications.

## Events
### `ExperienceNotificationService.OptInPromptClosed()`
- **Summary:** Fires when the local player closes the prompt.

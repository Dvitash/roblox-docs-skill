# UserSettings

**Superclass:** [GenericSettings](GenericSettings.md)

UserSettings is a singleton class in Roblox that stores basic user settings that persist across all games. It provides methods to check for feature enablement and erase saved state.

## Tags
- NotCreatable

## Methods
### `UserSettings:IsUserFeatureEnabled(name: string) -> boolean`
- **Summary:** Returns true if the specified user feature is enabled. This will throw an error if the user feature does not exist.

### `UserSettings:Reset() -> ()`
- **Summary:** Erases the saved state of the UserSettings, and restores its default values.

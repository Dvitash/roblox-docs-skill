# PolicyService

**Superclass:** [Instance](Instance.md)

PolicyService is a class used to query information regarding player policy compliance based on age range, location, and platform type. It allows users to view brand project assets and determine if the user can see specific content or features.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `PolicyService:CanViewBrandProjectAsync(player: [Player](Player.md), brandProjectId: string) -> boolean`
- **Tags:** Yields
- **Summary:** Determines if a user can see brand project assets inside your experience.

### `PolicyService:GetPolicyInfoForPlayerAsync(player: [Instance](Instance.md)) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns policy information about a player based on geolocation, age group, and platform.

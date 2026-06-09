# GroupService

**Superclass:** [Instance](Instance.md)

GroupService is a class in Roblox that allows developers to fetch information about a Roblox group from within a game.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `GroupService:GetAlliesAsync(groupId: int64) -> [StandardPages](StandardPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.StandardPages` object including information on all of the specified group's allies.

### `GroupService:GetEnemiesAsync(groupId: int64) -> [StandardPages](StandardPages.md)`
- **Tags:** Yields
- **Summary:** Returns a `Class.StandardPages` object including information on all of the specified group's enemies.

### `GroupService:GetGroupInfoAsync(groupId: int64) -> Variant`
- **Tags:** Yields
- **Summary:** Returns a table containing information about the given group.

### `GroupService:GetGroupsAsync(userId: int64) -> Array`
- **Tags:** Yields
- **Summary:** Returns a list of tables containing information on all of the groups a given player is a member of.

### `GroupService:GetRolesInGroupAsync(userId: int64, groupId: int64) -> Variant`
- **Tags:** Yields
- **Summary:** Returns all roles held by the specified user in the specified group, supporting multi-role group membership.

### `GroupService:PromptJoinAsync(groupId: int64) -> GroupMembershipStatus`
- **Tags:** Yields
- **Summary:** Prompts the local `Class.Player` to join a specified Roblox group via a native modal.

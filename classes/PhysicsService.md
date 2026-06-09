# PhysicsService

**Superclass:** [Instance](Instance.md)

This file contains methods for working with `Class.PhysicsService` to manage collision groups and their associated parts.

## Tags
- NotCreatable
- Service

## Methods
### `PhysicsService:CollisionGroupContainsPart(name: string, part: [BasePart](BasePart.md)) -> boolean`
- **Tags:** Deprecated
- **Summary:** Returns whether the part is in the collision group.

### `PhysicsService:CollisionGroupsAreCollidable(name1: string, name2: string) -> boolean`
- **Summary:** Returns whether the two groups will collide.

### `PhysicsService:CollisionGroupSetCollidable(name1: string, name2: string, collidable: boolean) -> ()`
- **Summary:** Sets the collision status between two groups.

### `PhysicsService:CreateCollisionGroup(name: string) -> int`
- **Tags:** Deprecated
- **Summary:** Creates a new collision group with the given name, and returns the ID of the created group.

### `PhysicsService:GetCollisionGroupId(name: string) -> int`
- **Tags:** Deprecated
- **Summary:** Returns the ID of the collision group with the specified name.

### `PhysicsService:GetCollisionGroupName(name: int) -> string`
- **Tags:** Deprecated
- **Summary:** Returns the name of the group with the corresponding ID.

### `PhysicsService:GetCollisionGroups() -> Array`
- **Tags:** Deprecated
- **Summary:** Returns a table with info on all of the place's collision groups.

### `PhysicsService:GetMaxCollisionGroups() -> int`
- **Summary:** Returns the maximum number of collision groups.

### `PhysicsService:GetRegisteredCollisionGroups() -> Array`
- **Summary:** Returns a table with info on all of the place's collision groups.

### `PhysicsService:IsCollisionGroupRegistered(name: string) -> boolean`
- **Summary:** Checks if a collision group is registered.

### `PhysicsService:RegisterCollisionGroup(name: string) -> ()`
- **Summary:** Registers a new collision group with the given name.

### `PhysicsService:RemoveCollisionGroup(name: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Removes the collision group with the given name.

### `PhysicsService:RenameCollisionGroup(from: string, to: string) -> ()`
- **Summary:** Renames specified collision group.

### `PhysicsService:SetPartCollisionGroup(part: [BasePart](BasePart.md), name: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the collision group of a part.

### `PhysicsService:UnregisterCollisionGroup(name: string) -> ()`
- **Summary:** Unregisters the collision group for the given name.

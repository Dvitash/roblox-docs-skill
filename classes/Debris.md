# Debris

**Superclass:** [Instance](Instance.md)

The `Class.Debris` service allows scheduling guaranteed object destruction without yielding, which is useful for managing system resources.

## Tags
- NotCreatable
- Service

## Properties
### `Debris.MaxItems`
- **Type:** `int`
- **Tags:** Deprecated
- **Summary:** The maximum number of items that can be assigned to the `Class.Debris` service at one time.

## Methods
### `Debris:AddItem(item: [Instance](Instance.md), lifetime: double) -> ()`
- **Summary:** Schedules a given `Class.Instance` for destruction within the specified lifetime.

### `Debris:addItem(item: [Instance](Instance.md), lifetime: double) -> ()`
- **Tags:** Deprecated

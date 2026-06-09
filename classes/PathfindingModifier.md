# PathfindingModifier

**Superclass:** [Instance](Instance.md)

PathfindingModifier is a class used to represent space with a higher or lower cost to be traversed when creating paths. It allows for smarter path computation by including modifiers in `Class.PathfindingService` parameters.

## Properties
### `PathfindingModifier.Label`
- **Type:** `string`
- **Summary:** The name of the navigation area inside or on top of the parts enclosed by the modifier.

### `PathfindingModifier.PassThrough`
- **Type:** `boolean`
- **Summary:** Determines if the parts enclosed by the modifier are traversable, even if they would normally be collided with.

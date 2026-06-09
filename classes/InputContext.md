# InputContext

**Superclass:** [Instance](Instance.md)

InputContext is a class defining a collection of related actions and how they interact with other contexts. It manages the ordering and priority of related `Class.InputAction` instances.

## Properties
### `InputContext.Enabled`
- **Type:** `boolean`
- **Summary:** Determines if this `InputContext` is enabled or not.

### `InputContext.Priority`
- **Type:** `int`
- **Summary:** The priority level at which the context should be run.

### `InputContext.Sink`
- **Type:** `boolean`
- **Summary:** Determines whether input bindings of lower priority will be processed.

# StyleRule

**Superclass:** [StyleBase](StyleBase.md)

StyleRule class defines style properties that override properties of instances affected by `Class.StyleRule.Selector|Selector`.

## Properties
### `StyleRule.Priority`
- **Type:** `int`
- **Summary:** A number that determines how properties of the `StyleRule` apply relative to the same properties in other `StyleRules`. Higher priority values take precedence over lower.

### `StyleRule.Selector`
- **Type:** `string`
- **Summary:** A string specifying which instances the `StyleRule` should affect.

### `StyleRule.SelectorError`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A read-only string that displays errors from the `Class.StyleRule.Selector|Selector` property.

## Methods
### `StyleRule:GetDefaultPropertyTransition() -> Variant`
- **Summary:** Returns the default transition applied to all properties of the `StyleRule` that don't have an explicit transition set.

### `StyleRule:GetProperties() -> Dictionary`
- **Summary:** Returns a dictionary of key-value pairs describing the properties of the `StyleRule`.

### `StyleRule:GetProperty(name: string) -> Variant`
- **Summary:** Returns the value of a specific property in the `StyleRule`.

### `StyleRule:GetPropertyTransitions() -> Dictionary`
- **Summary:** Returns a dictionary of all property transitions set on the `StyleRule`.

### `StyleRule:SetDefaultPropertyTransition(transitionParams: Variant) -> ()`
- **Summary:** Sets or clears a default transition that applies to all properties of the `StyleRule` that don't have an explicit transition set.

### `StyleRule:SetProperties(styleProperties: Dictionary) -> ()`
- **Summary:** Lets you declare and set multiple properties of the `StyleRule` at once.

### `StyleRule:SetProperty(name: string, value: Variant) -> ()`

### `StyleRule:SetPropertyTransition(property: string, transitionParams: Variant) -> ()`
- **Summary:** Sets or clears the transition for a single property on the `StyleRule`.

### `StyleRule:SetPropertyTransitions(properties: Dictionary) -> ()`
- **Summary:** Lets you declare and set transitions for multiple properties of the `StyleRule` at once.

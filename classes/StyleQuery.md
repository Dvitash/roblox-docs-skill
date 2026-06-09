# StyleQuery

**Superclass:** [Instance](Instance.md)

StyleQuery is an instance used to set conditions for a `Class.StyleRule`, allowing authors to set conditions like `"MaxSize"` and `"PreferredInput"`.

## Properties
### `StyleQuery.IsActive`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** A boolean that determines whether a `Class.StyleRule.Selector` of `@` will match the `Class.StyleQuery` name.

## Methods
### `StyleQuery:GetCondition(name: string) -> Variant`
- **Summary:** Returns the value of a specific condition in the `StyleQuery`.

### `StyleQuery:GetConditions() -> Dictionary`
- **Summary:** Returns a dictionary of key-value pairs describing the conditoins set on the `StyleQuery`.

### `StyleQuery:SetCondition(name: string, value: Variant) -> ()`

### `StyleQuery:SetConditions(conditions: Dictionary) -> ()`
- **Summary:** Lets you declare and set multiple conditions of the `StyleQuery` at once.

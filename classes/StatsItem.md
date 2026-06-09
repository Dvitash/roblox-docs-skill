# StatsItem

**Superclass:** [Instance](Instance.md)

A StatsItem is an internal measurement item created by the engine to benchmark backend components, and it can be read by plugins.

## Tags
- NotCreatable

## Properties
### `StatsItem.DisplayName`
- **Type:** `string`
- **Tags:** Hidden, ReadOnly, NotReplicated

## Methods
### `StatsItem:GetValue() -> double`
- **Summary:** Returns the StatsItem's value.

### `StatsItem:GetValueString() -> string`
- **Summary:** Returns the StatsItem's value as a formatted string.

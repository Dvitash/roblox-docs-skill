# StyleBase

**Superclass:** [Instance](Instance.md)

The `StyleBase` class is the base class for `Class.StyleSheet` and `Class.StyleRule`, which holds a list of child rules and associated token definitions.

## Tags
- NotCreatable

## Methods
### `StyleBase:GetStyleRules() -> List<[StyleRule](StyleRule.md)>`
- **Summary:** Returns an array of associated `Class.StyleRule|StyleRules`.

### `StyleBase:InsertStyleRule(rule: [StyleRule](StyleRule.md), priority: int?) -> ()`
- **Summary:** Inserts a new `Class.StyleRule` into the array of rules.

### `StyleBase:SetStyleRules(rules: Instances) -> ()`
- **Summary:** Similar to `Class.StyleBase:InsertStyleRule()|InsertStyleRule()` but lets you declare and set multiple `Class.StyleRule|StyleRules` at once.

## Events
### `StyleBase.StyleRulesChanged()`
- **Summary:** Fires when one or more `Class.StyleRule|StyleRules` is explicitly changed on the connected `Class.StyleSheet` or `Class.StyleRule`.

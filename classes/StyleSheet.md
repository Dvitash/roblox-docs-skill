# StyleSheet

**Superclass:** [StyleBase](StyleBase.md)

Aggregates `Class.StyleRule` and `Class.DataModel` trees can be linked to apply style properties to instances, and the `StyleSheet` class provides methods for deriving and setting these style properties.

## Methods
### `StyleSheet:GetDerives() -> List<[StyleSheet](StyleSheet.md)>`
- **Summary:** Returns an array of other `StyleSheets` from which the `StyleSheet` is deriving `Class.StyleRule|StyleRules` and token definitions.

### `StyleSheet:SetDerives(derives: Instances) -> ()`
- **Summary:** Sets the `StyleSheet` to derive `Class.StyleRule|StyleRules` and token definitions from one or more other `StyleSheets`.

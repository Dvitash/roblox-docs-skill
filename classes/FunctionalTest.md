# FunctionalTest

**Superclass:** [Instance](Instance.md)

FunctionalTest is a class in the `Instance` hierarchy that implements testing functionality. It is deprecated and should be replaced with `Class.TestService`.

## Tags
- Deprecated

## Properties
### `FunctionalTest.Description`
- **Type:** `string`
- **Summary:** The description of the FunctionalTest.

## Methods
### `FunctionalTest:Error(message: string) -> ()`

### `FunctionalTest:Failed(message: string) -> ()`
- **Summary:** Prints a red message to the output, prefixed by _"TestService: "_.

### `FunctionalTest:Pass(message: string) -> ()`

### `FunctionalTest:Passed(message: string) -> ()`

### `FunctionalTest:Warn(message: string) -> ()`
- **Summary:** Prints if a condition is true, otherwise prints a warning.

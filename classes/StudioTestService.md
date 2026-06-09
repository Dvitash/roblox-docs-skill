# StudioTestService

**Superclass:** [Instance](Instance.md)

StudioTestService is a class used by plugins to automate and customize Test and Run mode testing, allowing them to launch tests or run complex code automatically.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `StudioTestService.EditModeActive`
- **Type:** `boolean`

## Methods
### `StudioTestService:AddPlayers(numPlayers: int) -> ()`

### `StudioTestService:CanLeaveTest() -> boolean`

### `StudioTestService:EndTest(value: Variant) -> ()`

### `StudioTestService:ExecuteMultiplayerTestAsync(numPlayers: int, args: Variant) -> Variant`
- **Tags:** Yields

### `StudioTestService:ExecutePlayModeAsync(args: Variant) -> Variant`
- **Tags:** Yields

### `StudioTestService:ExecuteRunModeAsync(args: Variant) -> Variant`
- **Tags:** Yields

### `StudioTestService:GetTestArgs() -> Variant`

### `StudioTestService:LeaveTest() -> ()`

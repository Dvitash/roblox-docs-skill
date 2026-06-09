# TestService

**Superclass:** [Instance](Instance.md)

This file contains two classes, `TestService` and `RBX_CHECK`, which are used by Roblox to run controlled tests of the engine.

## Tags
- Service

## Properties
### `TestService.AutoRuns`
- **Type:** `boolean`
- **Summary:** If set to `true`, the game will start running when the service's `Class.TestService:RunAsync()` method is called.

### `TestService.Description`
- **Type:** `string`
- **Summary:** A description of the test being executed.

### `TestService.ErrorCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Measures how many errors have been recorded in the test session.

### `TestService.ExecuteWithStudioRun`
- **Type:** `boolean`
- **Summary:** When set to `true`, `TestService` will be executed when using the **Run** action in Roblox Studio.

### `TestService.Is30FpsThrottleEnabled`
- **Type:** `boolean`
- **Tags:** NotReplicated, Deprecated
- **Summary:** Sets whether or not the physics engine should be throttled to 30 FPS while the test is being ran.

### `TestService.IsPhysicsEnvironmentalThrottled`
- **Type:** `boolean`
- **Summary:** Sets whether or not the physics environment should be throttled while running this test.

### `TestService.IsSleepAllowed`
- **Type:** `boolean`
- **Summary:** Sets whether or not physics objects will be allowed to fall asleep while the test simulation is running.

### `TestService.NumberOfPlayers`
- **Type:** `int`
- **Summary:** The number of players expected in this test, if any.

### `TestService.SimulateSecondsLag`
- **Type:** `double`
- **Summary:** Sets a specific amount of additional latency experienced by players during the test session.

### `TestService.TestCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Measures how many test calls have been recorded in the test session.

### `TestService.ThrottlePhysicsToRealtime`
- **Type:** `boolean`
- **Summary:** Sets whether the test should be throttled to simulate time according to real world time or as fast as possible.

### `TestService.Timeout`
- **Type:** `double`
- **Summary:** The maximum amount of time that tests are allowed to run for.

### `TestService.WarnCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Measures how many warning calls have been recorded in the test session.

## Methods
### `TestService:Check(condition: boolean, description: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints result of a condition to the output.

### `TestService:Checkpoint(text: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints `Test checkpoint:` followed by a string to the output in blue text.

### `TestService:Done() -> ()`
- **Summary:** Prints `Testing Done` to the output in blue text.

### `TestService:Error(description: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints a red error message to the output, prefixed by `TestService: `.

### `TestService:Fail(description: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Indicates a fatal error in a `TestService` run.

### `TestService:isFeatureEnabled(name: string) -> boolean`

### `TestService:[Message](Message.md)(text: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints `TestService:` followed by a string to the output in blue text.

### `TestService:RegisterTest(testOptions: Dictionary) -> TestCase`

### `TestService:Require(condition: boolean, description: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints whether a condition is true along with a description string.

### `TestService:Run() -> ()`
- **Tags:** Yields, Deprecated
- **Summary:** Runs scripts which are parented to `TestService`.

### `TestService:RunAsync() -> ()`
- **Tags:** Yields
- **Summary:** Runs scripts which are parented to `TestService`.

### `TestService:ScopeTime() -> Dictionary`

### `TestService:TakeSnapshot(snapshotname: string, source: [Instance](Instance.md)) -> ()`

### `TestService:Warn(condition: boolean, description: string, source: [Instance](Instance.md), line: int) -> ()`
- **Summary:** Prints if a condition is `true`, otherwise prints a warning.

## Events
### `TestService.ServerCollectConditionalResult(condition: boolean, text: string, script: [Instance](Instance.md), line: int)`
- **Summary:** Fires when the server should collect a conditional test result.

### `TestService.ServerCollectResult(text: string, script: [Instance](Instance.md), line: int)`
- **Summary:** Fires when the server should collect a test result.

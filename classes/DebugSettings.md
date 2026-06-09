# DebugSettings

**Superclass:** [Instance](Instance.md)

The `DebugSettings` class provides various diagnostic information for Roblox, including data model status and instance counts.

## Tags
- NotCreatable
- Service
- NotReplicated
- NotBrowsable

## Properties
### `DebugSettings.DataModel`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether a `Class.DataModel` is actively in memory, as an integer (where 1 = true, and 0 = false).

### `DebugSettings.InstanceCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The number of instances active in the simulation.

### `DebugSettings.IsScriptStackTracingEnabled`
- **Type:** `boolean`
- **Summary:** Whether or not a stacktrace is displayed in the output for an error.

### `DebugSettings.JobCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Returns the number of internal DataModel jobs actively being processed.

### `DebugSettings.PlayerCount`
- **Type:** `int`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The number of players currently in the active game-instance.

### `DebugSettings.ReportSoundWarnings`
- **Type:** `boolean`
- **Summary:** Whether or not sound warnings should be reported.

### `DebugSettings.RobloxVersion`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current client version of Roblox. Can also be retrieved by using the version() function.

### `DebugSettings.TickCountPreciseOverride`
- **Type:** `TickCountSampleMethod`
- **Summary:** Sets the internal sampling method used to measure elapsed time with consistency across platforms.

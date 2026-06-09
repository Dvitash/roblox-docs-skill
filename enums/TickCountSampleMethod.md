# Enum.TickCountSampleMethod

Controls the precision of a timer.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Fast` | 0 |  | Compute time using a faster, but less precise method. |
| `Benchmark` | 1 |  | Dynamically decide between using ''Fast'' and ''Precise'' depending on performance. |
| `Precise` | 2 |  | Compute time using a precise method. |

**Valid values:** `Enum.TickCountSampleMethod.Fast`, `Enum.TickCountSampleMethod.Benchmark`, `Enum.TickCountSampleMethod.Precise`

# Enum.AssetFetchStatus

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Success` | 0 |  | The asset loaded successfully. |
| `Failure` | 1 |  | The asset failed to load successfully. Subsequent attempts are likely to fail; there may be something wrong with the `Datatype.Content\|Content` string. |
| `None` | 2 |  | The engine has no information about this asset. The engine never tried to load it. |
| `Loading` | 3 |  | The engine is in the middle of trying to load this asset. |
| `TimedOut` | 4 |  | The engine tried to load this asset but timed out. Future attempts to load may succeed. |

**Valid values:** `Enum.AssetFetchStatus.Success`, `Enum.AssetFetchStatus.Failure`, `Enum.AssetFetchStatus.None`, `Enum.AssetFetchStatus.Loading`, `Enum.AssetFetchStatus.TimedOut`

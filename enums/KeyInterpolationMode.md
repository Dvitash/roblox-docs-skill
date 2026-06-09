# Enum.KeyInterpolationMode

Describes the interpolation method between two keys.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Constant` | 0 |  | The segment starting at this key will constantly evaluate to the value set at this key. |
| `Linear` | 1 |  | The segment starting at this key will evaluate using a linear interpolation at this key and the value at the next key. |
| `Cubic` | 2 |  | The segment starting at this key will evaluate using cubic interpolation of this key value using its right tangent and the next key value and its left tangent. |

**Valid values:** `Enum.KeyInterpolationMode.Constant`, `Enum.KeyInterpolationMode.Linear`, `Enum.KeyInterpolationMode.Cubic`

# Enum.CompositeValueCurveType

Describes the type of value animated by a `Class.CompositeValueCurve`.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `ColorRGB` | 0 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"R"`, `"G"`, and `"B"` to animate the corresponding components of the `Datatype.Color3` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `ColorHSV` | 1 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"H"`, `"S"`, and `"V"` to animate hue, saturation, and value of a color that will be converted to RGB before returning a `Datatype.Color3` value from the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `NumberRange` | 2 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"Min"` and `"Max"` to animate the corresponding components of the `Datatype.NumberRange` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `Rect` | 3 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"MinX"`, `"MaxX"`, `"MinY"`, and `"MaxY"` to animate the corresponding components of the `Datatype.Rect` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `UDim` | 4 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"Scale"` and `"Offset"` to animate the corresponding components of the `Datatype.UDim` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `UDim2` | 5 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"ScaleX"`, `"OffsetX"`, `"ScaleY"`, and `"OffsetY"` to animate the corresponding components of the `Datatype.UDim2` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `Vector2` | 6 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"X"` and `"Y"` to animate the corresponding components of the `Datatype.Vector2` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |
| `Vector3` | 7 |  | The `Class.CompositeValueCurve` will animate children of type `Class.FloatCurve` named `"X"`, `"Y"`, and `"Z"` to animate the corresponding components of the `Datatype.Vector3` value returned by the method `Class.CompositeValueCurve:GetValueAtTime()`. |

**Valid values:** `Enum.CompositeValueCurveType.ColorRGB`, `Enum.CompositeValueCurveType.ColorHSV`, `Enum.CompositeValueCurveType.NumberRange`, `Enum.CompositeValueCurveType.Rect`, `Enum.CompositeValueCurveType.UDim`, `Enum.CompositeValueCurveType.UDim2`, `Enum.CompositeValueCurveType.Vector2`, `Enum.CompositeValueCurveType.Vector3`

# Enum.WrapLayerDebugMode

The Studio-only property for quickly visualizing and debugging meshes with inner cage and outer cages.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | This debug rendering mode does nothing. This is the default value. |
| `BoundCage` | 1 |  | This debug mode visualizes corresponding cage mesh vertices bound to an underlying `Class.WrapTarget`. In order to find corresponding vertices between different cages, the Wrap Deformer algorithm uses UV matching. As long as your `Class.WrapLayer` cage mesh share the same UV layout as `Class.WrapTarget`, its vertices will be marked as "bound". |
| `LayerCage` | 2 |  | This debug mode shows the resulting layer mesh as a whole. The deformer will use vertex locations from the previous layer for all unbound vertices. |
| `BoundCageAndLinks` | 3 |  | The same as BoundCage but also visualizes how bound vertices were moved. You can use this mode to identify where they belong on a previous layer and where they are located on the current layer. |
| `Reference` | 4 |  | This debug mode shows the original inner cage mesh as it was created. |
| `Rbf` | 5 |  | This debug mode visualizes the internal RBF solver state. You can estimate the wrap deformer's expected behavior by looking at this state. All renderable mesh vertices move from a "big sphere" to a "small sphere" along a corresponding line connecting two spheres. |
| `OuterCage` | 6 |  | This debug mode shows the original outer cage mesh as it was created. |
| `ReferenceMeshAfterMorph` | 7 |  |  |
| `HSROuterDetail` | 8 |  |  |
| `HSROuter` | 9 |  |  |
| `HSRInner` | 10 |  |  |
| `HSRInnerReverse` | 11 |  |  |
| `LayerCageFittedToBase` | 12 |  |  |
| `LayerCageFittedToPrev` | 13 |  |  |
| `PreWrapDeformerOuterCage` | 14 |  |  |
| `SkinningTransfer` | 15 |  |  |

**Valid values:** `Enum.WrapLayerDebugMode.None`, `Enum.WrapLayerDebugMode.BoundCage`, `Enum.WrapLayerDebugMode.LayerCage`, `Enum.WrapLayerDebugMode.BoundCageAndLinks`, `Enum.WrapLayerDebugMode.Reference`, `Enum.WrapLayerDebugMode.Rbf`, `Enum.WrapLayerDebugMode.OuterCage`, `Enum.WrapLayerDebugMode.ReferenceMeshAfterMorph`, `Enum.WrapLayerDebugMode.HSROuterDetail`, `Enum.WrapLayerDebugMode.HSROuter`, `Enum.WrapLayerDebugMode.HSRInner`, `Enum.WrapLayerDebugMode.HSRInnerReverse`, `Enum.WrapLayerDebugMode.LayerCageFittedToBase`, `Enum.WrapLayerDebugMode.LayerCageFittedToPrev`, `Enum.WrapLayerDebugMode.PreWrapDeformerOuterCage`, `Enum.WrapLayerDebugMode.SkinningTransfer`

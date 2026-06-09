# Enum.ScaleType

Determines how an image (of a `Class.ImageLabel` or `Class.ImageButton`) is scaled.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Stretch` | 0 |  | The image is stretched to fit within the element. |
| `Slice` | 1 |  | 9-Slice scaling: slice the image into 9 regions and apply different scaling rules to each region. The slice boundaries are determined by `Class.ImageLabel.SliceCenter` or `Class.ImageButton.SliceCenter`. See [UI 9-Slice Design](../../../ui/9-slice.md) for more information. . |
| `Tile` | 2 |  | The image is tiled to fit within the element. For example, if the element is twice the X dimension of the image, the image will appear twice (2 tiles). |
| `Fit` | 3 |  | The image is scaled fit within the element X or Y dimension (whichever fits first). |
| `Crop` | 4 |  | The image is cropped to fit within the element. |

**Valid values:** `Enum.ScaleType.Stretch`, `Enum.ScaleType.Slice`, `Enum.ScaleType.Tile`, `Enum.ScaleType.Fit`, `Enum.ScaleType.Crop`

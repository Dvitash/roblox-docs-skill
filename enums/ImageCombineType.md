# Enum.ImageCombineType

Enum for determining how two images are combined together.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `BlendSourceOver` | 1 |  | Blends pixels from the source with pixels from the destination using source over alpha blending. |
| `Overwrite` | 2 |  | Overwrites all pixels in the destination image with pixels from the source image. |
| `Add` | 3 |  | Adds pixels from the source and pixels from the destination together. |
| `Multiply` | 4 |  | Multiplies pixels from the source and pixels from the destination together. RGBA values are multiplied as values between `0` and `1`. Values lower than `1` have a darkening effect on the image. |
| `AlphaBlend` | 5 |  | Blends pixels from the source with pixels from the destination based on the alpha of the source pixels. Unlike **BlendSourceOver**, the destination color in **AlphaBlend** affects the resulting color of the image, regardless of the destination color's alpha. |
| `NormalMapBlend` | 6 |  |  |

**Valid values:** `Enum.ImageCombineType.BlendSourceOver`, `Enum.ImageCombineType.Overwrite`, `Enum.ImageCombineType.Add`, `Enum.ImageCombineType.Multiply`, `Enum.ImageCombineType.AlphaBlend`, `Enum.ImageCombineType.NormalMapBlend`

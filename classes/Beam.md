# Beam

**Superclass:** [Instance](Instance.md)

The `Beam` class is a class for connecting two `Class.Attachment` objects by drawing a texture between them. It supports custom curve parameters and allows for customizable beam appearance.

## Properties
### `Beam.Attachment0`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The `Class.Attachment` the beam originates from.

### `Beam.Attachment1`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** The `Class.Attachment` the beam ends at.

### `Beam.Brightness`
- **Type:** `float`
- **Summary:** Scales the light emitted from the beam when `Class.Beam.LightInfluence|LightInfluence` is less than 1.

### `Beam.Color`
- **Type:** `ColorSequence`
- **Summary:** Determines the color of the beam across its `Class.Beam.Segments|Segments`.

### `Beam.CurveSize0`
- **Type:** `float`
- **Summary:** Determines, along with `Class.Beam.Attachment0|Attachment0`, the position of the second control point in the beam's Bézier curve.

### `Beam.CurveSize1`
- **Type:** `float`
- **Summary:** Determines, along with `Class.Beam.Attachment1|Attachment1`, the position of the third control point in the beam's Bézier curve.

### `Beam.Enabled`
- **Type:** `boolean`
- **Summary:** Determines whether the beam is visible or not.

### `Beam.FaceCamera`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.Beam.Segments|Segments` of the beam will always face the camera, regardless of its orientation.

### `Beam.LightEmission`
- **Type:** `float`
- **Summary:** Determines to what degree the colors of the beam are blended with the colors behind it.

### `Beam.LightInfluence`
- **Type:** `float`
- **Summary:** Determines the degree to which the beam is influenced by the environment's lighting.

### `Beam.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated

### `Beam.Segments`
- **Type:** `int`
- **Summary:** Sets how many straight segments the beam is made up of.

### `Beam.Texture`
- **Type:** `ContentId`
- **Summary:** The content ID of the texture to be displayed on the beam.

### `Beam.TextureLength`
- **Type:** `float`
- **Summary:** Sets the length of the beam's texture, dependent on `Class.Beam.TextureMode|TextureMode`.

### `Beam.TextureMode`
- **Type:** `TextureMode`
- **Summary:** Determines the manner in which the `Class.Beam.Texture|Texture` scales and repeats.

### `Beam.TextureSpeed`
- **Type:** `float`
- **Summary:** Determines the speed at which the `Class.Beam.Texture|Texture` image moves along the beam.

### `Beam.Transparency`
- **Type:** `NumberSequence`
- **Summary:** Determines the transparency of the beam across its segments.

### `Beam.Width0`
- **Type:** `float`
- **Summary:** The width of the beam at its origin (`Class.Beam.Attachment0|Attachment0`), in studs.

### `Beam.Width1`
- **Type:** `float`
- **Summary:** The width of the beam at its end (`Class.Beam.Attachment1|Attachment1`), in studs.

### `Beam.ZOffset`
- **Type:** `float`
- **Summary:** The distance, in studs, the beam display is offset relative to the `Class.Workspace.CurrentCamera|CurrentCamera`.

## Methods
### `Beam:SetTextureOffset(offset: float) -> ()`
- **Summary:** Sets the current offset of the beam's texture cycle.

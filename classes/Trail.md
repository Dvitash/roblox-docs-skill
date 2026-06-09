# Trail

**Superclass:** [Instance](Instance.md)

The `Trail` class is used to create a trail effect between two attachments by defining how the trail segments are drawn based on the attachment positions.

## Properties
### `Trail.Attachment0`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** Along with `Class.Trail.Attachment1|Attachment1`, determines where the trail will start drawing its segments.

### `Trail.Attachment1`
- **Type:** `[Attachment](Attachment.md)`
- **Summary:** Along with `Class.Trail.Attachment0|Attachment0`, determines where the trail will start drawing its segments.

### `Trail.Brightness`
- **Type:** `float`
- **Summary:** Scales the light emitted from the trail when `Class.Trail.LightInfluence|LightInfluence` is less than 1.

### `Trail.Color`
- **Type:** `ColorSequence`
- **Summary:** The color of the trail throughout its lifetime.

### `Trail.Enabled`
- **Type:** `boolean`
- **Summary:** Determines whether the trail will be drawn or not.

### `Trail.FaceCamera`
- **Type:** `boolean`
- **Summary:** Determines whether the trail will always face the camera, regardless of its orientation.

### `Trail.Lifetime`
- **Type:** `float`
- **Summary:** Determines how long each segment in a trail will last, in seconds.

### `Trail.LightEmission`
- **Type:** `float`
- **Summary:** Determines to what degree the colors of the trail are blended with the colors behind it.

### `Trail.LightInfluence`
- **Type:** `float`
- **Summary:** Determines the degree to which the trail is influenced by the environment's lighting.

### `Trail.LocalTransparencyModifier`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated

### `Trail.MaxLength`
- **Type:** `float`
- **Summary:** Sets the maximum length of the trail.

### `Trail.MinLength`
- **Type:** `float`
- **Summary:** Sets the minimum length of the trail.

### `Trail.Texture`
- **Type:** `ContentId`
- **Summary:** The content ID of the texture to be displayed on the trail.

### `Trail.TextureLength`
- **Type:** `float`
- **Summary:** Sets the length of the trail's texture, dependent on `Class.Trail.TextureMode|TextureMode`.

### `Trail.TextureMode`
- **Type:** `TextureMode`
- **Summary:** Determines the manner in which the `Class.Trail.Texture|Texture` scales, repeats, and moves along with the trail's attachments.

### `Trail.Transparency`
- **Type:** `NumberSequence`
- **Summary:** Sets the transparency of the trail's segments over its `Class.Trail.Lifetime|Lifetime`.

### `Trail.WidthScale`
- **Type:** `NumberSequence`
- **Summary:** Scales the width of the trail over the course of its lifetime.

## Methods
### `Trail:Clear() -> ()`
- **Summary:** Clears the segments of the trail.

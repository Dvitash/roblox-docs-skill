# Enum.TextureMode

Describes how the texture of a `Class.Trail` or `Class.Beam` behaves.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Stretch` | 0 |  | For a `Class.Trail`, the texture will stretch out based on the lifetime of the trail, and shrink inwards if the trail's attachments stop moving. For a `Class.Beam`, the texture will repeat `Class.Beam.TextureLength\|TextureLength` times across the beam's overall length. See [here](../../../effects/beams.md#texture-lengthmode) for details. |
| `Wrap` | 1 |  | For a `Class.Trail`, the texture will be tiled as the length of the trail changes, but the textures will remain stationary relative to their attachments. For a `Class.Beam`, the texture repetitions will equal the beam's overall length (in&nbsp;studs) divided by its `Class.Beam.TextureLength\|TextureLength`. See [here](../../../effects/beams.md#texture-lengthmode) for details. |
| `Static` | 2 |  | For a `Class.Trail`, the texture will be rolled out as the attachments move, and they will remain in place until their lifetime is met. This setting is ideal for trail textures that should appear "stamped" where rendered, such as paw prints or tire tracks. This value is not supported for `Class.Beam` and therefore behaves identically to **Wrap**. |

**Valid values:** `Enum.TextureMode.Stretch`, `Enum.TextureMode.Wrap`, `Enum.TextureMode.Static`

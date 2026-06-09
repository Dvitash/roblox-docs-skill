# CharacterMesh

**Superclass:** [CharacterAppearance](CharacterAppearance.md)

This file contains properties for modifying the appearance of character body parts and loading mesh textures.

## Properties
### `CharacterMesh.BaseTextureContent`
- **Type:** `Content`

### `CharacterMesh.BaseTextureId`
- **Type:** `int64`
- **Summary:** The texture of a CharacterMesh. It can be overridden by Shirts, Pants, T-Shirts, and the `Class.CharacterMesh.OverlayTextureId` property.

### `CharacterMesh.BodyPart`
- **Type:** `BodyPart`
- **Summary:** The part of the Character's body that is affected.

### `CharacterMesh.MeshContent`
- **Type:** `Content`

### `CharacterMesh.MeshId`
- **Type:** `int64`
- **Summary:** Used to load a mesh file, and apply it to the given BodyPart.

### `CharacterMesh.OverlayTextureContent`
- **Type:** `Content`

### `CharacterMesh.OverlayTextureId`
- **Type:** `int64`
- **Summary:** The assetId of the overlay texture. The overlay covers Shirts, Pants, T-Shirts, and the `Class.CharacterMesh.BaseTextureId`.

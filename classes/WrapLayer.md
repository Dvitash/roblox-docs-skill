# WrapLayer

**Superclass:** [BaseWrap](BaseWrap.md)

WrapLayer is a class defining the inner and outer surfaces of 3D accessories, which are used for layering other objects without clipping or breaking.

## Properties
### `WrapLayer.AutoSkin`
- **Type:** `WrapLayerAutoSkin`

### `WrapLayer.BindOffset`
- **Type:** `CFrame`
- **Summary:** `Datatype.CFrame` is used to adjust a binding point for clothing item mesh. Could be used to move and rotate clothing items. This property is intended for fine-tuning only and it is heavily optional.

### `WrapLayer.Color`
- **Type:** `Color3`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Sets color used for the debug rendering. See `Class.WrapTarget.DebugMode`.

### `WrapLayer.DebugMode`
- **Type:** `WrapLayerDebugMode`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Allows switching between different debugging visualization modes for cage meshes.

### `WrapLayer.Enabled`
- **Type:** `boolean`
- **Summary:** Allows for disabling of the `Class.WrapLayer` object as if it does not exist.

### `WrapLayer.Order`
- **Type:** `int`
- **Summary:** Controls the composition order for layered clothing.

### `WrapLayer.Puffiness`
- **Type:** `float`
- **Summary:** Controls how much underlying clothing items inflate the current clothing item.

### `WrapLayer.ReferenceMeshContent`
- **Type:** `Content`

### `WrapLayer.ReferenceMeshId`
- **Type:** `ContentId`
- **Summary:** AssetID for reference mesh used to define Inner Cage of a 3D object.

### `WrapLayer.ReferenceOrigin`
- **Type:** `CFrame`
- **Summary:** Reference mesh offset relative to parent MeshPart (in the parent MeshPart space) Note: this property is set up automatically by the FBX importer.

### `WrapLayer.ReferenceOriginWorld`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Reference mesh offset relative to parent MeshPart (in the world space) Note: this property is set up automatically by the FBX importer.

### `WrapLayer.ShrinkFactor`
- **Type:** `float`
- **Summary:** Allows slight shrinking/expanding of the resulting render mesh, without affecting any other layers.

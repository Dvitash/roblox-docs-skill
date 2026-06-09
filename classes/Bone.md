# Bone

**Superclass:** [Attachment](Attachment.md)

Bones are non-rendered objects that drive movement for animation and clothing creation, and they inherit properties from `Class.Attachment`.

## Properties
### `Bone.Transform`
- **Type:** `CFrame`
- **Tags:** NotReplicated
- **Summary:** Determines the current animated offset of the bone in its local space.

### `Bone.TransformedCFrame`
- **Type:** `CFrame`
- **Tags:** Hidden, ReadOnly, NotReplicated
- **Summary:** Describes the combined `Class.Attachment.CFrame|CFrame` offset of the bone and the current animation offset in the bone local space.

### `Bone.TransformedWorldCFrame`
- **Type:** `CFrame`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the combined `Class.Attachment.CFrame|CFrame` offset of the bone and the current animation offset in world space.

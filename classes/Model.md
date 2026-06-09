# Model

**Superclass:** [PVInstance](PVInstance.md)

Model is a container class used to group objects, and it has several properties and methods that extend its functionality.

## Properties
### `Model.LevelOfDetail`
- **Type:** `ModelLevelOfDetail`
- **Summary:** Sets the level of detail on the model for experiences with instance streaming enabled.

### `Model.ModelStreamingMode`
- **Type:** `ModelStreamingMode`
- **Summary:** Controls the model streaming behavior on `Class.Model|Models` when instance streaming is enabled.

### `Model.PrimaryPart`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** The primary part of the `Class.Model`, or `nil` if not explicitly set.

### `Model.Scale`
- **Type:** `float`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** Editor-only property used to scale the model around its pivot. Setting this property will move the scale as though `Class.Model:ScaleTo()` was called on it.

### `Model.WorldPivot`
- **Type:** `CFrame`
- **Tags:** NotReplicated
- **Summary:** Determines where the pivot of a `Class.Model` which does **not** have a set `Class.Model.PrimaryPart` is located.

## Methods
### `Model:AddPersistentPlayer(playerInstance: [Player](Player.md)) -> ()`
- **Summary:** Sets this model to be persistent for the specified player. `Class.Model.ModelStreamingMode|ModelStreamingMode` must be set to `Enum.ModelStreamingMode|PersistentPerPlayer` for behavior to be changed as a result of addition.

### `Model:BreakJoints() -> ()`
- **Tags:** Deprecated
- **Summary:** Breaks connections between `BaseParts`, including surface connections with any adjacent parts, `Class.WeldConstraint|WeldConstraints` and all `Class.Weld|Welds` and other `Class.JointInstance|JointInstances`.

### `Model:breakJoints() -> ()`
- **Tags:** Deprecated

### `Model:GetBoundingBox() -> Tuple`
- **Summary:** Returns a description of a volume that contains all parts of a Model.

### `Model:GetExtentsSize() -> Vector3`
- **Summary:** Returns the size of the smallest bounding box that contains all of the `Class.BasePart|BaseParts` in the `Class.Model`, aligned with the `Class.Model.PrimaryPart` if it is set.

### `Model:GetModelCFrame() -> CFrame`
- **Tags:** Deprecated
- **Summary:** This value historically returned the CFrame of a central position in the model.

### `Model:GetModelSize() -> Vector3`
- **Tags:** Deprecated
- **Summary:** Returns the Vector3 size of the Model.

### `Model:GetPersistentPlayers() -> List<[Player](Player.md)>`
- **Summary:** Returns all the `Class.Player` objects that this model object is persistent for. Behavior varies based on whether this method is called from a `Class.Script` or a `Class.LocalScript`.

### `Model:GetPrimaryPartCFrame() -> CFrame`
- **Tags:** Deprecated
- **Summary:** Returns the `Datatype.CFrame` of the model's `Class.Model.PrimaryPart`. This function will throw an error if no primary part exists for the `Class.Model`.

### `Model:GetScale() -> float`
- **Summary:** Returns the canonical scale of the model, which defaults to 1 for newly created models and will change as it is scaled via `Class.Model:ScaleTo()`.

### `Model:MakeJoints() -> ()`
- **Tags:** Deprecated
- **Summary:** Goes through all `Class.BasePart|BaseParts` in the `Class.Model`. If any part's side has a SurfaceType that can make a joint it will create a joint with any adjacent parts.

### `Model:makeJoints() -> ()`
- **Tags:** Deprecated

### `Model:move(location: Vector3) -> ()`
- **Tags:** Deprecated

### `Model:MoveTo(position: Vector3) -> ()`
- **Summary:** Moves the `Class.Model.PrimaryPart|PrimaryPart` to the given position. If a primary part has not been specified, the root part of the model will be used.

### `Model:moveTo(location: Vector3) -> ()`
- **Tags:** Deprecated

### `Model:RemovePersistentPlayer(playerInstance: [Player](Player.md)) -> ()`
- **Summary:** Makes this model no longer persistent for the specified player. `Class.Model.ModelStreamingMode|ModelStreamingMode` must be set to `Enum.ModelStreamingMode|PersistentPerPlayer` for behavior to be changed as a result of removal.

### `Model:ResetOrientationToIdentity() -> ()`
- **Tags:** Deprecated
- **Summary:** Resets the rotation of the model's parts to the previously set identity rotation, which is done through the `Class.Model:SetIdentityOrientation()` method.

### `Model:ScaleTo(newScaleFactor: float) -> ()`
- **Summary:** Sets the scale factor of the model, adjusting the sizing and location of all descendant Instances such that they have that scale factor relative to their initial sizes and locations when scale factor was 1.

### `Model:SetIdentityOrientation() -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the identity rotation of the given model, allowing you to reset the rotation of the entire model later, through the use of the `ResetOrientationToIdentity` method.

### `Model:SetPrimaryPartCFrame(cframe: CFrame) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the `Class.BasePart.CFrame` of the model's `Class.Model.PrimaryPart`. All other parts in the model will also be moved and will maintain their orientation and offset respective to the `Class.Model.PrimaryPart`.

### `Model:TranslateBy(delta: Vector3) -> ()`
- **Summary:** Shifts a `Class.Model` by the given `Datatype.Vector3` offset, preserving the model's orientation. If another `Class.BasePart` or `Class.Terrain` already exists at the new position then the `Class.Model` will overlap said object.

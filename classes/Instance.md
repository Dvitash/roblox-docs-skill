# Instance

**Superclass:** [Object](Object.md)

`Instance` is the base class for all classes in Roblox's `Class.DataModel` hierarchy, which can be accessed via code. It is not possible to directly create root `Instance` objects, but `Datatype.Instance.new()` creates them.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `Instance.Archivable`
- **Type:** `boolean`
- **Summary:** Determines if an `Class.Instance` and its descendants can be cloned using `Class.Instance:Clone()`, and can be saved/published.

### `Instance.archivable`
- **Type:** `boolean`
- **Tags:** Hidden, NotReplicated, Deprecated

### `Instance.Capabilities`
- **Type:** `SecurityCapabilities`
- **Summary:** The set of capabilities allowed to be used for scripts inside this container.

### `Instance.Name`
- **Type:** `string`
- **Summary:** A non-unique identifier of the `Class.Instance`.

### `Instance.Parent`
- **Type:** `[Instance](Instance.md)`
- **Tags:** NotReplicated
- **Summary:** Determines the hierarchical parent of the `Class.Instance`.

### `Instance.PredictionMode`
- **Type:** `PredictionMode`
- **Tags:** ReadOnly, NotReplicated, NotScriptable

### `Instance.RobloxLocked`
- **Type:** `boolean`
- **Tags:** Hidden
- **Summary:** A deprecated property that used to protect `Class.CoreGui` objects.

### `Instance.Sandboxed`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** When enabled, the instance can only access abilities in its `Capabilities` list.

### `Instance.UniqueId`
- **Type:** `UniqueId`
- **Tags:** NotReplicated
- **Summary:** A unique identifier for the instance.

## Methods
### `Instance:AddTag(tag: string) -> ()`
- **Summary:** Applies a tag to the instance.

### `Instance:children() -> Instances`
- **Tags:** Deprecated
- **Summary:** Returns an array of the object's children.

### `Instance:ClearAllChildren() -> ()`
- **Summary:** This method destroys all of an instance's children.

### `Instance:Clone() -> [Instance](Instance.md)`
- **Summary:** Create a copy of an instance and all its descendants, ignoring instances that are not `Class.Instance.Archivable|Archivable`.

### `Instance:clone() -> [Instance](Instance.md)`
- **Tags:** Deprecated

### `Instance:Destroy() -> ()`
- **Summary:** Sets the `Class.Instance.Parent` property to `nil`, locks the `Class.Instance.Parent` property, disconnects all connections, and calls `Destroy()` on all children.

### `Instance:destroy() -> ()`
- **Tags:** Deprecated

### `Instance:FindFirstAncestor(name: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the first ancestor of the `Class.Instance` whose `Class.Instance.Name` is equal to the given name.

### `Instance:FindFirstAncestorOfClass(className: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the first ancestor of the `Class.Instance` whose `Class.Object.ClassName` is equal to the given className.

### `Instance:FindFirstAncestorWhichIsA(className: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the first ancestor of the `Class.Instance` for whom `Class.Object:IsA()` returns true for the given className.

### `Instance:FindFirstChild(name: string, recursive: boolean) -> [Instance](Instance.md)?`
- **Summary:** Returns the first child of the `Class.Instance` found with the given name.

### `Instance:findFirstChild(name: string, recursive: boolean) -> [Instance](Instance.md)`
- **Tags:** Deprecated

### `Instance:FindFirstChildOfClass(className: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the first child of the `Class.Instance` whose `Class.Object.ClassName|ClassName` is equal to the given class name.

### `Instance:FindFirstChildWhichIsA(className: string, recursive: boolean) -> [Instance](Instance.md)?`
- **Summary:** Returns the first child of the `Class.Instance` for whom `Class.Object:IsA()` returns true for the given className.

### `Instance:FindFirstDescendant(name: string) -> [Instance](Instance.md)?`
- **Summary:** Returns the first descendant found with the given `Class.Instance.Name`.

### `Instance:GetActor() -> [Actor](Actor.md)?`
- **Summary:** Returns the `Class.Actor` associated with the Instance, if any.

### `Instance:GetAttribute(attribute: string) -> Variant`
- **Summary:** Returns the value which has been assigned to the given attribute name.

### `Instance:GetAttributeChangedSignal(attribute: string) -> RBXScriptSignal`
- **Summary:** Returns an event that fires when the given attribute changes.

### `Instance:GetAttributes() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Returns a dictionary of the instance's attributes.

### `Instance:GetChildren() -> Instances`
- **Summary:** Returns an array containing all of the instance's children.

### `Instance:getChildren() -> Instances`
- **Tags:** Deprecated

### `Instance:GetDebugId(scopeLength: int) -> string`
- **Tags:** NotBrowsable
- **Summary:** Returns a coded string of the debug ID used internally by Roblox.

### `Instance:GetDescendants() -> Instances`
- **Tags:** CustomLuaState
- **Summary:** Returns an array containing all of the descendants of the instance.

### `Instance:GetFullName() -> string`
- **Summary:** Returns a string describing the instance's ancestry.

### `Instance:GetStyled(name: string, selector: string?) -> Variant`
- **Summary:** Returns the styled or explicitly modified value of the specified property, or else the default property value if it hasn't been styled/modified.

### `Instance:GetStyledPropertyChangedSignal(property: string) -> RBXScriptSignal`

### `Instance:GetTags() -> Array`
- **Summary:** Gets an array of all tags applied to the instance.

### `Instance:HasTag(tag: string) -> boolean`
- **Summary:** Check whether the instance has a given tag.

### `Instance:IsAncestorOf(descendant: [Instance](Instance.md)) -> boolean`
- **Summary:** Returns true if an `Class.Instance` is an ancestor of the given descendant.

### `Instance:IsDescendantOf(ancestor: [Instance](Instance.md)) -> boolean`
- **Summary:** Returns `true` if an `Class.Instance` is a descendant of the given ancestor.

### `Instance:isDescendantOf(ancestor: [Instance](Instance.md)) -> boolean`
- **Tags:** Deprecated

### `Instance:IsPropertyModified(property: string) -> boolean`
- **Summary:** Returns `true` if the value stored in the specified property is not equal to the code-instantiated default.

### `Instance:QueryDescendants(selector: string) -> Instances`
- **Tags:** CustomLuaState

### `Instance:Remove() -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the object's `Parent` to `nil`, and does the same for all its descendants.

### `Instance:remove() -> ()`
- **Tags:** Deprecated

### `Instance:RemoveTag(tag: string) -> ()`
- **Summary:** Removes a tag from the instance.

### `Instance:ResetPropertyToDefault(property: string) -> ()`
- **Summary:** Resets a property to its default value.

### `Instance:SetAttribute(attribute: string, value: Variant) -> ()`
- **Summary:** Sets the attribute with the given name to the given value.

### `Instance:WaitForChild(childName: string, timeOut: double) -> [Instance](Instance.md)`
- **Tags:** CustomLuaState, CanYield
- **Summary:** Returns the child of the `Class.Instance` with the given name. If the child does not exist, it will yield the current thread until it does.

## Events
### `Instance.AncestryChanged(child: [Instance](Instance.md), parent: [Instance](Instance.md))`
- **Summary:** Fires when the `Class.Instance.Parent` property of this object or one of its ancestors is changed.

### `Instance.AttributeChanged(attribute: string)`
- **Summary:** Fires whenever an attribute is changed on the `Class.Instance`.

### `Instance.ChildAdded(child: [Instance](Instance.md))`
- **Summary:** Fires after an object is parented to this `Class.Instance`.

### `Instance.childAdded(child: [Instance](Instance.md))`
- **Tags:** Deprecated

### `Instance.ChildRemoved(child: [Instance](Instance.md))`
- **Summary:** Fires after a child is removed from this `Class.Instance`.

### `Instance.DescendantAdded(descendant: [Instance](Instance.md))`
- **Summary:** Fires after a descendant is added to the `Class.Instance`.

### `Instance.DescendantRemoving(descendant: [Instance](Instance.md))`
- **Summary:** Fires immediately before a descendant of the `Class.Instance` is removed.

### `Instance.Destroying()`
- **Summary:** Fires immediately before (or is deferred until after) the instance is destroyed via `Class.Instance:Destroy()`.

### `Instance.StyledPropertiesChanged()`
- **Summary:** Fires whenever any style property is changed on the instance, including when a property is set to `nil`.

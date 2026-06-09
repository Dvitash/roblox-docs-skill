# Tool

**Superclass:** [BackpackItem](BackpackItem.md)

The `Tool` class defines how a `Class.Humanoid` object can equip weapons, controlling whether they are dropped and affecting their behavior in the `Class.Workspace`.

## Properties
### `Tool.CanBeDropped`
- **Type:** `boolean`
- **Summary:** Controls whether the player can drop the tool.

### `Tool.Enabled`
- **Type:** `boolean`
- **Summary:** Relates to whether or not the tool can be used.

### `Tool.Grip`
- **Type:** `CFrame`
- **Summary:** Stores the tool's "grip" properties as one `Datatype.CFrame`.

### `Tool.GripForward`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Represents the `R02`, `R12`, and `R22` values of the grip `Datatype.CFrame` rotation matrix.

### `Tool.GripPos`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** The positional offset of the tool's weld matrix.

### `Tool.GripRight`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Represents the `R00`, `R10`, and `R20` values of the grip `Datatype.CFrame` rotation matrix.

### `Tool.GripUp`
- **Type:** `Vector3`
- **Tags:** Hidden, NotReplicated
- **Summary:** Represents the `R01`, `R11`, and `R21` values of the grip `Datatype.CFrame` rotation matrix.

### `Tool.ManualActivationOnly`
- **Type:** `boolean`
- **Summary:** Controls whether the `Class.Tool` can be activated without executing `Class.Tool:Activate()`.

### `Tool.RequiresHandle`
- **Type:** `boolean`
- **Summary:** Determines whether a `Class.Tool` functions without a handle.

### `Tool.ToolTip`
- **Type:** `string`
- **Summary:** Controls the message displayed when the player's mouse hovers over the tool in their backpack.

## Methods
### `Tool:Activate() -> ()`
- **Summary:** Simulates activation of the `Class.Tool`.

### `Tool:Deactivate() -> ()`
- **Summary:** Simulates deactivation of the `Class.Tool`.

## Events
### `Tool.Activated()`
- **Summary:** Fires when the player clicks while the tool is equipped.

### `Tool.Deactivated()`
- **Summary:** Fires when the player releases their click while the tool is equipped and activated.

### `Tool.Equipped(mouse: [Mouse](Mouse.md))`
- **Summary:** Fires when the tool is equipped.

### `Tool.Unequipped()`
- **Summary:** Fires when the tool is unequipped.

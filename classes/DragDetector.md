# DragDetector

**Superclass:** [ClickDetector](ClickDetector.md)

The `Class.DragDetector` class is designed to facilitate interaction with 3D objects by allowing users to manipulate parts or models. It supports dragging and scripting to drive UI or logical decisions based on motion.

## Properties
### `DragDetector.ActivatedCursorIcon`
- **Type:** `ContentId`
- **Summary:** Sets the cursor icon to display when the mouse is activated over the parent of this `Class.DragDetector`.

### `DragDetector.ActivatedCursorIconContent`
- **Type:** `Content`
- **Summary:** Sets the cursor icon to display when the mouse is activated over the parent of this `Class.DragDetector`. Only supports asset URIs

### `DragDetector.ApplyAtCenterOfMass`
- **Type:** `boolean`
- **Summary:** Whether constraint force is applied to the object's center of mass.

### `DragDetector.Axis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The primary axis of motion, expressed relative to the reference frame.

### `DragDetector.DragFrame`
- **Type:** `CFrame`
- **Summary:** The `Datatype.CFrame` of the pivot, dependent on the drag detector's `Class.DragDetector.ReferenceInstance|ReferenceInstance`.

### `DragDetector.DragStyle`
- **Type:** `DragDetectorDragStyle`
- **Summary:** The paradigm used to generate proposed motion.

### `DragDetector.Enabled`
- **Type:** `boolean`
- **Summary:** Whether the `Class.DragDetector` responds to user input.

### `DragDetector.GamepadModeSwitchKeyCode`
- **Type:** `KeyCode`
- **Summary:** During gamepad input, the modifier `Enum.KeyCode` for the secondary mode of motion.

### `DragDetector.KeyboardModeSwitchKeyCode`
- **Type:** `KeyCode`
- **Summary:** During keyboard input, the modifier `Enum.KeyCode` for the secondary mode of motion.

### `DragDetector.MaxDragAngle`
- **Type:** `float`
- **Summary:** Along with `Class.DragDetector.MinDragAngle|MinDragAngle`, impedes the drag detector's attempts to generate motion.

### `DragDetector.MaxDragTranslation`
- **Type:** `Vector3`
- **Summary:** Along with `Class.DragDetector.MinDragTranslation|MinDragTranslation`, impedes the drag detector's attempts to generate motion.

### `DragDetector.MaxForce`
- **Type:** `float`
- **Summary:** Maximum force applied for the object to reach its goal.

### `DragDetector.MaxTorque`
- **Type:** `float`
- **Summary:** Maximum torque applied for the object to reach its goal.

### `DragDetector.MinDragAngle`
- **Type:** `float`
- **Summary:** Along with `Class.DragDetector.MaxDragAngle|MaxDragAngle`, impedes the drag detector's attempts to generate motion.

### `DragDetector.MinDragTranslation`
- **Type:** `Vector3`
- **Summary:** Along with `Class.DragDetector.MaxDragTranslation|MaxDragTranslation`, impedes the drag detector's attempts to generate motion.

### `DragDetector.Orientation`
- **Type:** `Vector3`
- **Summary:** Specifies the **YXZ** rotation of axes of motion relative to the reference frame.

### `DragDetector.PermissionPolicy`
- **Type:** `DragDetectorPermissionPolicy`
- **Summary:** Controls the permission level for which players can interact with the `Class.DragDetector`.

### `DragDetector.ReferenceInstance`
- **Type:** `[Instance](Instance.md)`
- **Summary:** An instance whose `Datatype.CFrame` is the reference frame for the drag detector.

### `DragDetector.ResponseStyle`
- **Type:** `DragDetectorResponseStyle`
- **Summary:** The paradigm used to move, or not move, the objects affected by the drag detector.

### `DragDetector.Responsiveness`
- **Type:** `float`
- **Summary:** Higher values cause the object to reach its goal more rapidly.

### `DragDetector.RunLocally`
- **Type:** `boolean`
- **Summary:** Whether user input on a `Class.DragDetector` replicates to the server or remains local to the specific client.

### `DragDetector.SecondaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The secondary axis of the motion.

### `DragDetector.TrackballRadialPullFactor`
- **Type:** `float`
- **Summary:** If `Class.DragDetector.DragStyle|DragStyle` is `Enum.DragDetectorDragStyle.RotateTrackball`, multiplier for adding a radial pull rotation as a contribution to the total.

### `DragDetector.TrackballRollFactor`
- **Type:** `float`
- **Summary:** If `Class.DragDetector.DragStyle|DragStyle` is `Enum.DragDetectorDragStyle.RotateTrackball`, multiplier for adding roll rotation to the total.

### `DragDetector.VRSwitchKeyCode`
- **Type:** `KeyCode`
- **Summary:** During VR input, the modifier `Enum.KeyCode` for the secondary mode of motion.

### `DragDetector.WorldAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The `Class.DragDetector.Axis|Axis` expressed in world space.

### `DragDetector.WorldSecondaryAxis`
- **Type:** `Vector3`
- **Tags:** NotReplicated
- **Summary:** The `Class.DragDetector.SecondaryAxis|SecondaryAxis` expressed in world space.

## Methods
### `DragDetector:AddConstraintFunction(priority: int, function: Function) -> RBXScriptConnection`
- **Summary:** Adds a function to modify or constrain proposed motion.

### `DragDetector:GetReferenceFrame() -> CFrame`
- **Summary:** Returns the reference `Datatype.CFrame` in which motion is expressed.

### `DragDetector:RestartDrag() -> ()`
- **Summary:** May be invoked from a script to restart the drag using new parameters.

### `DragDetector:SetDragStyleFunction(function: Function) -> ()`
- **Summary:** Passes a function to be used if and only if `Class.DragDetector.DragStyle|DragStyle` is set to `Enum.DragDetectorDragStyle.Scriptable`.

### `DragDetector:SetPermissionPolicyFunction(function: Function) -> ()`
- **Summary:** Passes a function to be used if and only if `Class.DragDetector.PermissionPolicy|PermissionPolicy` is set to `Enum.DragDetectorPermissionPolicy.Scriptable`.

## Events
### `DragDetector.DragContinue(playerWhoDragged: [Player](Player.md), cursorRay: Ray, viewFrame: CFrame, vrInputFrame: OptionalCoordinateFrame, isModeSwitchKeyDown: boolean)`
- **Summary:** Fires when a user continues dragging the object after `Class.DragDetector.DragStart|DragStart` has been initiated.

### `DragDetector.DragEnd(playerWhoDragged: [Player](Player.md))`
- **Summary:** Fires when a user stops dragging the object.

### `DragDetector.DragStart(playerWhoDragged: [Player](Player.md), cursorRay: Ray, viewFrame: CFrame, hitFrame: CFrame, clickedPart: [BasePart](BasePart.md), vrInputFrame: OptionalCoordinateFrame, isModeSwitchKeyDown: boolean)`
- **Summary:** Fires when a user starts dragging the object.

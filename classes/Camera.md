# Camera

**Superclass:** [PVInstance](PVInstance.md)

### Camera Class Details - **Class Definition:** - `name`: Camera - `type`: class - `memory_category`: Instances - **Key Properties:** - `Class.Camera.CFrame`: Defines the position and orientation of the camera. - `Class.Camera.CameraType`: Determines how the camera updates each frame. - `Class.Camera.CameraSubject`: Indicates what object the camera follows (e.g., `Class.BasePart`). - `Class.Camera.FieldOfView`: Represents the visible extent of the observable world. - `Class.Camera.Focus`:…

## Tags
- NotReplicated

## Properties
### `Camera.CameraSubject`
- **Type:** `[Instance](Instance.md)`
- **Summary:** The `Class.Humanoid` or `Class.BasePart` that is the `Class.Camera` subject.

### `Camera.CameraType`
- **Type:** `CameraType`
- **Summary:** Specifies the `Enum.CameraType` to be read by the camera scripts.

### `Camera.CFrame`
- **Type:** `CFrame`
- **Summary:** The `Datatype.CFrame` of the `Class.Camera`, defining its position and orientation in the 3D world.

### `Camera.CoordinateFrame`
- **Type:** `CFrame`
- **Tags:** Hidden, NotReplicated, Deprecated

### `Camera.DiagonalFieldOfView`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Sets the angle of the camera's diagonal field of view.

### `Camera.FieldOfView`
- **Type:** `float`
- **Summary:** Sets the angle of the camera's vertical field of view.

### `Camera.FieldOfViewMode`
- **Type:** `FieldOfViewMode`
- **Summary:** Determines the FOV value of the `Class.Camera` that's invariant under viewport size changes.

### `Camera.Focus`
- **Type:** `CFrame`
- **Summary:** Sets the area in 3D space that is prioritized by Roblox's graphical systems.

### `Camera.focus`
- **Type:** `CFrame`
- **Tags:** NotReplicated, Deprecated

### `Camera.HeadLocked`
- **Type:** `boolean`
- **Summary:** Toggles whether the camera will automatically track the head motion of a player using a VR device.

### `Camera.HeadScale`
- **Type:** `float`
- **Summary:** Sets the scale of the user's perspective of the world when using VR.

### `Camera.MaxAxisFieldOfView`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** Sets the angle of the camera's field of view along the longest viewport axis.

### `Camera.NearPlaneZ`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes the negative **Z** offset, in studs, of the camera's near clipping plane.

### `Camera.ViewportSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The dimensions of the device safe area on a Roblox client.

### `Camera.VRTiltAndRollEnabled`
- **Type:** `boolean`
- **Summary:** Toggles whether to apply tilt and roll from the `Class.Camera.CFrame|CFrame` property while the player is using a VR device.

## Methods
### `Camera:GetLargestCutoffDistance(ignoreList: Instances) -> float`
- **Tags:** Deprecated
- **Summary:** Returns how much the `Class.Camera` needs to be pushed towards its `Class.Camera.Focus|Focus` in order to make sure there is no obstructions between the `Class.Camera.Focus|Focus` and `Class.Camera.CFrame|CFrame`.

### `Camera:GetPanSpeed() -> float`
- **Tags:** Deprecated
- **Summary:** Returns the current 'pan' speed of the `Class.Camera`.

### `Camera:GetPartsObscuringTarget(castPoints: Array, ignoreList: Instances) -> Instances`
- **Summary:** Returns an array of `Class.BasePart|BaseParts` that are obscuring the lines of sight between the camera's `Class.Camera.CFrame|CFrame` and the cast points.

### `Camera:GetRenderCFrame() -> CFrame`
- **Summary:** Returns the actual `Datatype.CFrame`where the `Class.Camera` is being rendered, accounting for any roll applied and the impact of VR devices.

### `Camera:GetRoll() -> float`
- **Summary:** Returns in radians the current roll, or rotation around the camera's Z-axis, applied to the `Class.Camera` using `Class.Camera:SetRoll()|SetRoll()`.

### `Camera:GetTiltSpeed() -> float`
- **Tags:** Deprecated
- **Summary:** Returns the current tilt speed of the `Class.Camera`.

### `Camera:Interpolate(endPos: CFrame, endFocus: CFrame, duration: float) -> ()`
- **Tags:** Deprecated
- **Summary:** Tweens the `Class.Camera` in a linear fashion towards a new `Class.Camera.CFrame|CFrame` and `Class.Camera.Focus|Focus` over a given duration.

### `Camera:PanUnits(units: int) -> ()`
- **Tags:** Deprecated
- **Summary:** Pans the `Class.Camera` around the `Class.Camera.Focus|Focus` in 45 degree increments around the **Y** axis.

### `Camera:ScreenPointToRay(x: float, y: float, depth: float) -> Ray`
- **Summary:** Creates a unit `Datatype.Ray` from a position on the screen (in pixels), at a set depth from the `Class.Camera` orientated in the camera's direction. Accounts for the GUI inset.

### `Camera:SetCameraPanMode(mode: CameraPanMode) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the `Enum.CameraPanMode` to be used by the `Class.Camera` on mobile devices.

### `Camera:SetRoll(rollAngle: float) -> ()`
- **Summary:** Sets the current rotation applied around the camera's Z-axis.

### `Camera:TiltUnits(units: int) -> boolean`
- **Tags:** Deprecated
- **Summary:** Tilts the `Class.Camera` around its `Class.Camera.Focus|Focus` in 10 degree increments around the camera's **X** axis.

### `Camera:ViewportPointToRay(x: float, y: float, depth: float) -> Ray`
- **Summary:** Creates a unit `Datatype.Ray` from a position on the viewport (in pixels), at a given depth from the `Class.Camera`, orientated in the camera's direction. Does not account for the `Enum.ScreenInsets|CoreUISafeInsets` inset.

### `Camera:WorldToScreenPoint(worldPoint: Vector3) -> Tuple`
- **Summary:** Returns the screen location and depth of a `Datatype.Vector3` `worldPoint` and whether this point is within the bounds of the screen. Accounts for the GUI inset.

### `Camera:WorldToViewportPoint(worldPoint: Vector3) -> Tuple`
- **Summary:** Returns the screen location and depth of a `Datatype.Vector3` `worldPoint` and whether this point is within the bounds of the screen. Does not account for the GUI inset.

### `Camera:ZoomToExtents(boundingBoxCFrame: CFrame, boundingBoxSize: Vector3) -> ()`
- **Summary:** Adjusts the `Class.Camera.CFrame|CFrame` so that the specified bounding box is fully visible within the camera's viewport.

## Events
### `Camera.InterpolationFinished()`
- **Summary:** Fired when the `Class.Camera` has finished interpolating using`Class.Camera:Interpolate()|Interpolate()`.

# UIDragDetector

**Superclass:** [UIComponent](UIComponent.md)

The `UIDragDetector` class facilitates interaction with UI elements by allowing scripts to place objects and define how they respond to motion.

## Properties
### `UIDragDetector.ActivatedCursorIcon`
- **Type:** `ContentId`
- **Summary:** Sets the cursor icon to display when the mouse is activated over the parent of this `Class.UIDragDetector`.

### `UIDragDetector.ActivatedCursorIconContent`
- **Type:** `Content`
- **Summary:** Sets the cursor icon to display when the mouse is activated over the parent of this `Class.UIDragDetector`. Only supports asset URIs

### `UIDragDetector.BoundingBehavior`
- **Type:** `UIDragDetectorBoundingBehavior`
- **Summary:** Determines bounding behavior of the dragged UI object when the detector's `Class.UIDragDetector.BoundingUI|BoundingUI` is set.

### `UIDragDetector.BoundingUI`
- **Type:** `[GuiBase2d](GuiBase2d.md)`
- **Summary:** Instance whose bounding area defines the drag boundaries for the parent `Class.GuiObject`.

### `UIDragDetector.CursorIcon`
- **Type:** `ContentId`
- **Summary:** Sets the cursor icon to display when the mouse is hovered over the parent of this `Class.UIDragDetector`.

### `UIDragDetector.CursorIconContent`
- **Type:** `Content`
- **Summary:** Sets the cursor icon to display when the mouse is hovered over the parent of this `Class.UIDragDetector`. Only asset URIs are supported.

### `UIDragDetector.DragAxis`
- **Type:** `Vector2`
- **Summary:** The drag axis for the `Class.UIDragDetector` instance when `Class.UIDragDetector.DragStyle|DragStyle` is set to `Enum.UIDragDetectorDragStyle.TranslateLine`.

### `UIDragDetector.DragRelativity`
- **Type:** `UIDragDetectorDragRelativity`
- **Summary:** Sets the paradigm which defines the relativity of inputs/outputs from a custom drag function.

### `UIDragDetector.DragRotation`
- **Type:** `float`
- **Summary:** The rotation performed by the current drag.

### `UIDragDetector.DragSpace`
- **Type:** `UIDragDetectorDragSpace`
- **Summary:** Sets the paradigm which defines the space of inputs/outputs from a custom drag function.

### `UIDragDetector.DragStyle`
- **Type:** `UIDragDetectorDragStyle`
- **Summary:** The paradigm used to generate proposed motion.

### `UIDragDetector.DragUDim2`
- **Type:** `UDim2`
- **Summary:** The translation performed by the current drag expressed in a `Datatype.UDim2` value.

### `UIDragDetector.Enabled`
- **Type:** `boolean`
- **Summary:** Whether the `Class.UIDragDetector` responds to user input.

### `UIDragDetector.MaxDragAngle`
- **Type:** `float`
- **Summary:** Along with `Class.UIDragDetector.MinDragAngle|MinDragAngle`, impedes the detector's attempts to generate rotational motion.

### `UIDragDetector.MaxDragTranslation`
- **Type:** `UDim2`
- **Summary:** Along with `Class.UIDragDetector.MinDragTranslation|MinDragTranslation`, impedes the detector's attempts to generate linear/planar motion.

### `UIDragDetector.MinDragAngle`
- **Type:** `float`
- **Summary:** Along with `Class.UIDragDetector.MaxDragAngle|MaxDragAngle`, impedes the detector's attempts to generate rotational motion.

### `UIDragDetector.MinDragTranslation`
- **Type:** `UDim2`
- **Summary:** Along with `Class.UIDragDetector.MaxDragTranslation|MaxDragTranslation`, impedes the detector's attempts to generate linear/planar motion.

### `UIDragDetector.ReferenceUIInstance`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** A `Class.GuiObject` instance whose local space and absolute center position is the reference space and origin for the detector.

### `UIDragDetector.ResponseStyle`
- **Type:** `UIDragDetectorResponseStyle`
- **Summary:** The paradigm used to define the response to proposed motion.

### `UIDragDetector.SelectionModeDragSpeed`
- **Type:** `UDim2`
- **Summary:** Maximum drag speed for translation.

### `UIDragDetector.SelectionModeRotateSpeed`
- **Type:** `float`
- **Summary:** Maximum angle per second the `Class.UIDragDetector` can rotate at.

### `UIDragDetector.UIDragSpeedAxisMapping`
- **Type:** `UIDragSpeedAxisMapping`
- **Summary:** `Enum.UIDragSpeedAxisMapping` value that determines the **X**/**Y** dimension dragging speeds.

## Methods
### `UIDragDetector:AddConstraintFunction(priority: int, function: Function) -> RBXScriptConnection`
- **Summary:** Adds a function to modify or constrain proposed motion.

### `UIDragDetector:GetReferencePosition() -> UDim2`
- **Summary:** Returns the reference `Datatype.UDim2` position of the current drag's reference origin.

### `UIDragDetector:GetReferenceRotation() -> float`
- **Summary:** Returns the reference rotation of the current drag's reference element.

### `UIDragDetector:SetDragStyleFunction(function: Function) -> ()`
- **Summary:** Passes a function to be used if and only if `Class.UIDragDetector.DragStyle|DragStyle` is set to `Enum.UIDragDetectorDragStyle.Scriptable`.

## Events
### `UIDragDetector.DragContinue(inputPosition: Vector2)`
- **Summary:** Fires when a user continues dragging the UI element after `Class.UIDragDetector.DragStart|DragStart` has been initiated.

### `UIDragDetector.DragEnd(inputPosition: Vector2)`
- **Summary:** Fires when a user stops dragging the UI element.

### `UIDragDetector.DragStart(inputPosition: Vector2)`
- **Summary:** Fires when a user starts dragging the UI element.

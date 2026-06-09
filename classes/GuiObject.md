# GuiObject

**Superclass:** [GuiBase2d](GuiBase2d.md)

The `GuiObject` class defines 2D user interface objects, including `Class.GuiButton`, `Class.GuiLabel`, and `Class.GuiImage`, and provides methods for managing their layout and styling.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `GuiObject.Active`
- **Type:** `boolean`
- **Summary:** Determines whether this UI element sinks input.

### `GuiObject.AnchorPoint`
- **Type:** `Vector2`
- **Summary:** Determines the origin point of a `Class.GuiObject`, relative to its absolute size.

### `GuiObject.AutomaticSize`
- **Type:** `AutomaticSize`
- **Summary:** Determines whether resizing occurs based on child content.

### `GuiObject.BackgroundColor`
- **Type:** `BrickColor`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Determines the color of the `Class.GuiObject` background.

### `GuiObject.BackgroundColor3`
- **Type:** `Color3`
- **Summary:** Determines the `Class.GuiObject` background color.

### `GuiObject.BackgroundTransparency`
- **Type:** `float`
- **Summary:** Determines the transparency of the `Class.GuiObject` background and border.

### `GuiObject.BorderColor`
- **Type:** `BrickColor`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** Determines the color of the `Class.GuiObject` border.

### `GuiObject.BorderColor3`
- **Type:** `Color3`
- **Summary:** Determines the color of the `Class.GuiObject` border.

### `GuiObject.BorderMode`
- **Type:** `BorderMode`
- **Summary:** Determines in what manner the `Class.GuiObject` border is laid out relative to its dimensions.

### `GuiObject.BorderSizePixel`
- **Type:** `int`
- **Summary:** Determines the pixel width of the `Class.GuiObject` border.

### `GuiObject.ClipsDescendants`
- **Type:** `boolean`
- **Summary:** Determines if descendant `Class.GuiObject|GuiObjects` outside of the bounds of a parent GUI element should render.

### `GuiObject.Draggable`
- **Type:** `boolean`
- **Tags:** Deprecated
- **Summary:** Determines whether a `Class.GuiObject` (and its descendants) can be dragged around the screen.

### `GuiObject.GuiState`
- **Type:** `GuiState`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines whether the player's mouse is being actively pressed on the `Class.GuiObject` or not.

### `GuiObject.InputSink`
- **Type:** `InputSink`

### `GuiObject.Interactable`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.GuiButton` can be interacted with or not, or if the `Enum.GuiState|GuiState` of the `Class.GuiObject` is changing or not.

### `GuiObject.LayoutOrder`
- **Type:** `int`
- **Summary:** Controls the sort order of the `Class.GuiObject` when used with a `Class.UIGridStyleLayout`.

### `GuiObject.NextSelectionDown`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Sets the `Class.GuiObject` which will be selected when the gamepad selector is moved downward.

### `GuiObject.NextSelectionLeft`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Sets the `Class.GuiObject` which will be selected when the gamepad selector is moved to the left.

### `GuiObject.NextSelectionRight`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Sets the `Class.GuiObject` which will be selected when the gamepad selector is moved to the right.

### `GuiObject.NextSelectionUp`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Sets the `Class.GuiObject` which will be selected when the gamepad selector is moved upward.

### `GuiObject.Position`
- **Type:** `UDim2`
- **Summary:** Determines the pixel and scalar position of the `Class.GuiObject`.

### `GuiObject.Rotation`
- **Type:** `float`
- **Summary:** Determines the number of degrees by which the `Class.GuiObject` is rotated.

### `GuiObject.Selectable`
- **Type:** `boolean`
- **Summary:** Determine whether the `Class.GuiObject` can be selected by a gamepad.

### `GuiObject.SelectionImageObject`
- **Type:** `[GuiObject](GuiObject.md)`
- **Summary:** Overrides the default selection adornment used for gamepads.

### `GuiObject.SelectionOrder`
- **Type:** `int`
- **Summary:** The order of `Class.GuiObject|GuiObjects` selected by the gamepad UI selection.

### `GuiObject.Size`
- **Type:** `UDim2`
- **Summary:** Determines the pixel and scalar size of the `Class.GuiObject`.

### `GuiObject.SizeConstraint`
- **Type:** `SizeConstraint`
- **Summary:** Sets the `Class.GuiObject.Size|Size` axes that the `Class.GuiObject` will be based on, relative to the size of its parent.

### `GuiObject.Transparency`
- **Type:** `float`
- **Tags:** Hidden, NotReplicated
- **Summary:** A mixed property of `Class.GuiObject.BackgroundTransparency|BackgroundTransparency` and `Class.TextLabel.TextTransparency|TextTransparency`.

### `GuiObject.Visible`
- **Type:** `boolean`
- **Summary:** Determines whether the `Class.GuiObject` and its descendants will be rendered.

### `GuiObject.ZIndex`
- **Type:** `int`
- **Summary:** Determines the order in which a `Class.GuiObject` renders relative to others.

## Methods
### `GuiObject:TweenPosition(endPosition: UDim2, easingDirection: EasingDirection, easingStyle: EasingStyle, time: float, override: boolean, callback: Function) -> boolean`
- **Summary:** Smoothly moves a GUI to a new `Datatype.UDim2`.

### `GuiObject:TweenSize(endSize: UDim2, easingDirection: EasingDirection, easingStyle: EasingStyle, time: float, override: boolean, callback: Function) -> boolean`
- **Summary:** Smoothly resizes a `Class.GuiObject` to a new `Datatype.UDim2`.

### `GuiObject:TweenSizeAndPosition(endSize: UDim2, endPosition: UDim2, easingDirection: EasingDirection, easingStyle: EasingStyle, time: float, override: boolean, callback: Function) -> boolean`
- **Summary:** Smoothly moves a GUI to a new size and position.

## Events
### `GuiObject.DragBegin(initialPosition: UDim2)`
- **Tags:** Deprecated
- **Summary:** Fired when a player begins dragging the object.

### `GuiObject.DragStopped(x: int, y: int)`
- **Tags:** Deprecated
- **Summary:** Fired when a player stops dragging the object.

### `GuiObject.InputBegan(input: [InputObject](InputObject.md))`
- **Summary:** Fired when a user begins interacting via a Human-Computer Interface device (Mouse button down, touch begin, keyboard button down, etc).

### `GuiObject.InputChanged(input: [InputObject](InputObject.md))`
- **Summary:** Fired when a user changes how they're interacting via a Human-Computer Interface device (Mouse button down, touch begin, keyboard button down, etc).

### `GuiObject.InputEnded(input: [InputObject](InputObject.md))`
- **Summary:** Fired when a user stops interacting via a Human-Computer Interface device (Mouse button down, touch begin, keyboard button down, etc).

### `GuiObject.MouseEnter(x: int, y: int)`
- **Summary:** Fires when a user moves their mouse into a GUI element.

### `GuiObject.MouseLeave(x: int, y: int)`
- **Summary:** Fires when a user moves their mouse out of a GUI element.

### `GuiObject.MouseMoved(x: int, y: int)`
- **Summary:** Fires whenever a user moves their mouse while it is inside a GUI element.

### `GuiObject.MouseWheelBackward(x: int, y: int)`
- **Summary:** Fires when a user scrolls their mouse wheel back when the mouse is over a GUI element.

### `GuiObject.MouseWheelForward(x: int, y: int)`
- **Summary:** Fires when a user scrolls their mouse wheel forward when the mouse is over a GUI element.

### `GuiObject.SelectionGained()`
- **Summary:** Fired when the GuiObject is being focused on with the Gamepad selector.

### `GuiObject.SelectionLost()`
- **Summary:** Fired when the Gamepad selector stops focusing on the GuiObject.

### `GuiObject.TouchLongPress(touchPositions: Array, state: UserInputState)`
- **Summary:** Fires when the player starts, continues and stops long-pressing the UI element.

### `GuiObject.TouchPan(touchPositions: Array, totalTranslation: Vector2, velocity: Vector2, state: UserInputState)`
- **Summary:** Fires when the player moves their finger on the UI element.

### `GuiObject.TouchPinch(touchPositions: Array, scale: float, velocity: float, state: UserInputState)`
- **Summary:** Fires when the player performs a pinch or pull gesture using two fingers on the UI element.

### `GuiObject.TouchRotate(touchPositions: Array, rotation: float, velocity: float, state: UserInputState)`
- **Summary:** Fires when the player performs a rotation gesture using two fingers on the UI element.

### `GuiObject.TouchSwipe(swipeDirection: SwipeDirection, numberOfTouches: int)`
- **Summary:** Fires when the player performs a swipe gesture on the UI element.

### `GuiObject.TouchTap(touchPositions: Array)`
- **Summary:** Fires when the player performs a tap gesture on the UI element.

# ContextActionService

**Superclass:** [Instance](Instance.md)

### ContextActionService - **Type:** class - **Memory Category:** Instances - **Description:** This is a service used to bind user input to contextual actions or actions that are only enabled under certain conditions or periods of time. - **Usage Context:** It allows an experience to bind user input to specific actions, allowing for actions like opening doors while being close by. - **Action Handling:** - An action is a string (the name of the action) used by the service to differentiate…

## Tags
- NotCreatable
- Service

## Methods
### `ContextActionService:BindAction(actionName: string, functionToBind: Function, createTouchButton: boolean, inputTypes: Tuple) -> ()`
- **Summary:** Bind user input to an action given an action handling function.

### `ContextActionService:BindActionAtPriority(actionName: string, functionToBind: Function, createTouchButton: boolean, priorityLevel: int, inputTypes: Tuple) -> ()`
- **Summary:** Behaves like `Class.ContextActionService:BindAction()|BindAction` but also allows a priority to be assigned to the bound action for overlapping input types (higher before lower).

### `ContextActionService:BindActionToInputTypes(actionName: string, functionToBind: Function, createTouchButton: boolean, inputTypes: Tuple) -> ()`
- **Tags:** Deprecated
- **Summary:** Binds _functionToBind_ to input events such as key presses, mouse movement, or controller input.

### `ContextActionService:BindActivate(userInputTypeForActivation: UserInputType, keyCodesForActivation: Tuple) -> ()`
- **Summary:** Bind a `Enum.KeyCode` with a specific `Enum.UserInputType` to trigger `Class.Tool.Activation` and `Class.ClickDetector` events.

### `ContextActionService:GetAllBoundActionInfo() -> Dictionary`
- **Summary:** Get a table of information about all bound actions (key is the name passed to `Class.ContextActionService:BindAction()|BindAction`, value is a table from `Class.ContextActionService:GetBoundActionInfo()|GetBoundActionInfo` when called with the key).

### `ContextActionService:GetBoundActionInfo(actionName: string) -> Dictionary`
- **Summary:** Get a table of information about a bound action given its name originally passed to `Class.ContextActionService:BindAction()|BindAction`.

### `ContextActionService:GetButton(actionName: string) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Retrieves a `Class.ImageButton` of a `Class.ContextActionService:BindAction()|bound` action that had a touch input button created.

### `ContextActionService:GetCurrentLocalToolIcon() -> string`
- **Summary:** Return the `Class.BackpackItem.TextureId` of a `Class.Tool` currently `Class.Tool.Equipped|equipped` by the `Class.Player`.

### `ContextActionService:SetDescription(actionName: string, description: string) -> ()`
- **Summary:** Given the name of a bound action with a touch button, sets the description of the action.

### `ContextActionService:SetImage(actionName: string, image: string) -> ()`
- **Summary:** If `actionName` key contains a bound action, then `image` is set as the image of the touch button.

### `ContextActionService:SetPosition(actionName: string, position: UDim2) -> ()`
- **Summary:** Given the name of a bound action with a touch button, sets the position of the button within the ContextButtonFrame.

### `ContextActionService:SetTitle(actionName: string, title: string) -> ()`
- **Summary:** Given the name of a bound action with a touch button, sets the text shown on the button.

### `ContextActionService:UnbindAction(actionName: string) -> ()`
- **Summary:** Unbind an action from input given its name.

### `ContextActionService:UnbindActivate(userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode) -> ()`
- **Summary:** Unbind a `Enum.KeyCode` with a specific `Enum.UserInputType` from triggering `Class.Tool.Activation` when bound with `Class.ContextActionService:BindActivate()`.

### `ContextActionService:UnbindAllActions() -> ()`
- **Summary:** Removes all functions bound. No actionNames will remain. All touch buttons will be removed.

## Events
### `ContextActionService.LocalToolEquipped(toolEquipped: [Instance](Instance.md))`
- **Summary:** Fires when the current player equips a `Class.Tool`.

### `ContextActionService.LocalToolUnequipped(toolUnequipped: [Instance](Instance.md))`
- **Summary:** Fires when the current player unequips a `Class.Tool`.

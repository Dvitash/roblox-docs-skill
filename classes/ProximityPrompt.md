# ProximityPrompt

**Superclass:** [Instance](Instance.md)

ProximityPrompt is an object that allows players to interact with objects in the 3D world, such as opening doors or picking up items. It can be controlled by three primary elements and can be customized with properties like `Class.ProximityPrompt.Style`.

## Properties
### `ProximityPrompt.ActionText`
- **Type:** `string`
- **Summary:** The action text shown to the user.

### `ProximityPrompt.AutoLocalize`
- **Type:** `boolean`
- **Summary:** Whether the prompt's `Class.ProximityPrompt.ActionText` and `Class.ProximityPrompt.ObjectText` will be localized according to the `Class.ProximityPrompt.RootLocalizationTable`.

### `ProximityPrompt.ClickablePrompt`
- **Type:** `boolean`
- **Summary:** Whether the prompt can be activated by clicking/tapping on the prompt UI.

### `ProximityPrompt.Enabled`
- **Type:** `boolean`
- **Summary:** Whether or not this prompt should be shown.

### `ProximityPrompt.Exclusivity`
- **Type:** `ProximityPromptExclusivity`
- **Summary:** Used to customize which prompts can be shown at the same time.

### `ProximityPrompt.GamepadKeyCode`
- **Type:** `KeyCode`
- **Summary:** The gamepad button the player should press to trigger the prompt.

### `ProximityPrompt.HoldDuration`
- **Type:** `float`
- **Summary:** The duration, in seconds, that the player must hold the button/key down to trigger the prompt.

### `ProximityPrompt.KeyboardKeyCode`
- **Type:** `KeyCode`
- **Summary:** The key the player should press to trigger the prompt.

### `ProximityPrompt.MaxActivationDistance`
- **Type:** `float`
- **Summary:** The maximum distance a Player's `Class.Player.Character|character` can be from the `Class.ProximityPrompt` for the prompt to appear.

### `ProximityPrompt.MaxIndicatorDistance`
- **Type:** `float`

### `ProximityPrompt.ObjectText`
- **Type:** `string`
- **Summary:** An optional property that determines the object name text shown to the user.

### `ProximityPrompt.RequiresLineOfSight`
- **Type:** `boolean`
- **Summary:** Whether the prompt is hidden if the path between the player's `Class.Camera` and object parented to the `Class.ProximityPrompt` is obstructed.

### `ProximityPrompt.RootLocalizationTable`
- **Type:** `[LocalizationTable](LocalizationTable.md)`
- **Summary:** A reference to a `Class.LocalizationTable` to be used to apply automated localization to this prompt's `Class.ProximityPrompt.ActionText` and `Class.ProximityPrompt.ObjectText`.

### `ProximityPrompt.Style`
- **Type:** `ProximityPromptStyle`
- **Summary:** The style of the prompt's UI.

### `ProximityPrompt.UIOffset`
- **Type:** `Vector2`
- **Summary:** The pixel offset applied to the prompt's UI.

## Methods
### `ProximityPrompt:InputHoldBegin() -> ()`
- **Summary:** Fires a signal indicating that the user began pressing the prompt GUI button.

### `ProximityPrompt:InputHoldEnd() -> ()`
- **Summary:** Fires a signal indicating that the user ended pressing the prompt GUI button.

## Events
### `ProximityPrompt.IndicatorHidden()`

### `ProximityPrompt.IndicatorShown()`

### `ProximityPrompt.PromptButtonHoldBegan(playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggered when a player begins holding down the `Class.ProximityPrompt.KeyboardKeyCode|key`/button connected to a prompt with a non-zero `Class.ProximityPrompt.HoldDuration`.

### `ProximityPrompt.PromptButtonHoldEnded(playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when the player ends holding down the button on a prompt with a non-zero `Class.ProximityPrompt.HoldDuration`.

### `ProximityPrompt.PromptHidden()`
- **Summary:** Triggers when the `Class.ProximityPrompt|prompt` becomes hidden.

### `ProximityPrompt.PromptShown(inputType: ProximityPromptInputType)`
- **Summary:** Triggers when the `Class.ProximityPrompt|prompt` becomes visible.

### `ProximityPrompt.Triggered(playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggered when the prompt `Class.ProximityPrompt.KeyboardKeyCode|key`/button is pressed, or after a specified amount of time holding the button, if `Class.ProximityPrompt.HoldDuration` is used.

### `ProximityPrompt.TriggerEnded(playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when `Class.ProximityPrompt.KeyboardKeyCode|key`/button is released, for longer events where the user is required to hold down the button.

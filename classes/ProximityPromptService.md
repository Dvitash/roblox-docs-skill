# ProximityPromptService

**Superclass:** [Instance](Instance.md)

ProximityPromptService is a class in Rookie Blox that allows developers to interact with `Class.ProximityPrompt` objects globally, which can be useful for managing proximity-based interactions.

## Tags
- Service
- NotBrowsable

## Properties
### `ProximityPromptService.Enabled`
- **Type:** `boolean`
- **Summary:** Whether `Class.ProximityPrompt|ProximityPrompts` are enabled, and therefore shown, in-experience.

### `ProximityPromptService.MaxIndicatorsVisible`
- **Type:** `int`

### `ProximityPromptService.MaxPromptsVisible`
- **Type:** `int`
- **Summary:** Maximum number of `Class.ProximityPrompt|ProximityPrompts` that will be shown to the player.

## Events
### `ProximityPromptService.IndicatorHidden(prompt: [ProximityPrompt](ProximityPrompt.md))`

### `ProximityPromptService.IndicatorShown(prompt: [ProximityPrompt](ProximityPrompt.md))`

### `ProximityPromptService.PromptButtonHoldBegan(prompt: [ProximityPrompt](ProximityPrompt.md), playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when the player begins holding down the `Class.ProximityPrompt.KeyboardKeyCode|KeyboardKeyCode` key/button on a prompt with a non-zero `Class.ProximityPrompt.HoldDuration|HoldDuration`.

### `ProximityPromptService.PromptButtonHoldEnded(prompt: [ProximityPrompt](ProximityPrompt.md), playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when the player stops holding down the `Class.ProximityPrompt.KeyboardKeyCode|KeyboardKeyCode` key/button on a prompt with a non-zero `Class.ProximityPrompt.HoldDuration|HoldDuration`.

### `ProximityPromptService.PromptHidden(prompt: [ProximityPrompt](ProximityPrompt.md))`
- **Summary:** Triggers client-side when a prompt becomes hidden.

### `ProximityPromptService.PromptShown(prompt: [ProximityPrompt](ProximityPrompt.md), inputType: ProximityPromptInputType)`
- **Summary:** Triggers client-side when a prompt becomes visible.

### `ProximityPromptService.PromptTriggered(prompt: [ProximityPrompt](ProximityPrompt.md), playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when the user interacts with this prompt.

### `ProximityPromptService.PromptTriggerEnded(prompt: [ProximityPrompt](ProximityPrompt.md), playerWhoTriggered: [Player](Player.md))`
- **Summary:** Triggers when the player stops holding down the `Class.ProximityPrompt.KeyboardKeyCode|KeyboardKeyCode` key/button while triggering a prompt.

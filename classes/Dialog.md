# Dialog

**Superclass:** [Instance](Instance.md)

The `Dialog` class is a class for creating NPC billboard-style dialog bubbles, which can be used by players to interact with NPCs. It allows the creator to set whether multiple players can interact simultaneously or if only one player can initiate a conversation.

## Properties
### `Dialog.BehaviorType`
- **Type:** `DialogBehaviorType`
- **Summary:** Sets whether the Dialog can be used by multiple players at once.

### `Dialog.ConversationDistance`
- **Type:** `float`
- **Summary:** The furthest distance that a player can be from the Dialog's parent to start a conversation.

### `Dialog.GoodbyeChoiceActive`
- **Type:** `boolean`
- **Summary:** Toggles whether the goodbye option will be displayed.

### `Dialog.GoodbyeDialog`
- **Type:** `string`
- **Summary:** Sets the sentence that the dialog will show to the player when the chat ends.

### `Dialog.InitialPrompt`
- **Type:** `string`
- **Summary:** Sets the first sentence that the dialog will show to the player, once a chat is commenced.

### `Dialog.InUse`
- **Type:** `boolean`
- **Summary:** If true, this dialog is being used by at least one player.

### `Dialog.Purpose`
- **Type:** `DialogPurpose`
- **Summary:** Sets the icon that the initial dialog displays.

### `Dialog.Tone`
- **Type:** `DialogTone`
- **Summary:** Sets the color of the NPC's speech bubble.

### `Dialog.TriggerDistance`
- **Type:** `float`
- **Summary:** Sets the maximum distance that a dialog can be triggered from.

### `Dialog.TriggerOffset`
- **Type:** `Vector3`
- **Summary:** Sets the offset of the dialog relative to the dialog's parent.

## Methods
### `Dialog:GetCurrentPlayers() -> Instances`
- **Summary:** Returns a list of players currently using the Dialog.

## Events
### `Dialog.DialogChoiceSelected(player: [Instance](Instance.md), dialogChoice: [Instance](Instance.md))`
- **Summary:** Fired when a player chooses something to say, through a `Class.Dialog` instance.

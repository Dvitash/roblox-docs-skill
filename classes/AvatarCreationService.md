# AvatarCreationService

**Superclass:** [Instance](Instance.md)

The `AvatarCreationService` is a service that supports developer avatar creators by providing methods for prompting avatar creation from within experiences.

## Tags
- NotCreatable
- Service

## Methods
### `AvatarCreationService:AutoSetupAvatarAsync(player: [Player](Player.md), autoSetupParams: Dictionary, progressCallback: Function?) -> string`
- **Tags:** Yields
- **Summary:** Automatically sets up a custom `Class.Model` and/or avatar accessories.

### `AvatarCreationService:GenerateAvatar2DPreviewAsync(avatarGeneration2dPreviewParams: Dictionary) -> string`
- **Tags:** Yields
- **Summary:** Creates a 2D avatar preview and returns a `previewId`.

### `AvatarCreationService:GenerateAvatarAsync(avatarGenerationParams: Dictionary) -> string`
- **Tags:** Yields
- **Summary:** Generates an avatar and returns a generationId.

### `AvatarCreationService:GetBatchTokenDetailsAsync(tokenIds: Array) -> Array`
- **Tags:** Yields
- **Summary:** Gets the avatar creation token details for a list of avatar creation tokens at once.

### `AvatarCreationService:GetValidationRules() -> Dictionary`
- **Tags:** CustomLuaState
- **Summary:** Gets data regarding rules that assets must abide by to pass UGC validation.

### `AvatarCreationService:LoadAvatar2DPreviewAsync(previewId: string) -> [EditableImage](EditableImage.md)`
- **Tags:** Yields
- **Summary:** Load an AvatarGeneration 2D preview on the client from a previewId.

### `AvatarCreationService:LoadGeneratedAvatarAsync(generationId: string) -> [HumanoidDescription](HumanoidDescription.md)`
- **Tags:** Yields
- **Summary:** Loads a generated avatar using an avatar generation ID.

### `AvatarCreationService:PrepareAvatarForPreviewAsync(humanoidModel: [Model](Model.md)) -> ()`
- **Tags:** Yields
- **Summary:** Prepares in-experience avatar for preview.

### `AvatarCreationService:PromptCreateAvatarAssetAsync(tokenId: string, player: [Player](Player.md), assetInstance: [Instance](Instance.md), assetType: AvatarAssetType) -> Tuple`
- **Tags:** Yields
- **Summary:** Prompts a `Class.Player` to purchase and create an avatar asset from an `Class.Instance`.

### `AvatarCreationService:PromptCreateAvatarAsync(tokenId: string, player: [Player](Player.md), humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> Tuple`
- **Tags:** Yields
- **Summary:** Prompts a `Class.Player` to purchase and create an avatar from a `Class.HumanoidDescription`.

### `AvatarCreationService:PromptSelectAvatarGenerationImageAsync(player: [Player](Player.md)) -> string`
- **Tags:** Yields
- **Summary:** Prompt the `Class.Player` to take a selfie and return the FileId.

### `AvatarCreationService:RequestAvatarGenerationSessionAsync(player: [Player](Player.md), callback: Function) -> Tuple`
- **Tags:** Yields
- **Summary:** Request an AvatarGeneration session for a `Class.Player`.

### `AvatarCreationService:ValidateUGCAccessoryAsync(player: [Player](Player.md), accessory: [Instance](Instance.md), accessoryType: AccessoryType) -> Tuple`
- **Tags:** Yields
- **Summary:** Studio only. Runs UGC validation for an `Enum.AccessoryType`.

### `AvatarCreationService:ValidateUGCBodyPartAsync(player: [Player](Player.md), instance: [Instance](Instance.md), bodyPart: BodyPart) -> Tuple`
- **Tags:** Yields
- **Summary:** Studio only. Runs UGC validation for an `Enum.BodyPart`.

### `AvatarCreationService:ValidateUGCFullBodyAsync(player: [Player](Player.md), humanoidDescription: [HumanoidDescription](HumanoidDescription.md)) -> Tuple`
- **Tags:** Yields
- **Summary:** Studio only. Runs UGC validation for a whole body.

## Events
### `AvatarCreationService.AvatarAssetModerationCompleted(assetId: int64, moderationStatus: ModerationStatus)`
- **Summary:** Fires when an in-experience-created avatar asset's moderation status has been updated from pending.

### `AvatarCreationService.AvatarModerationCompleted(outfitId: int64, moderationStatus: ModerationStatus)`
- **Summary:** Fires when an in-experience-created avatar's moderation status has been updated from pending.

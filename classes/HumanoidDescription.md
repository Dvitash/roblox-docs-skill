# HumanoidDescription

**Superclass:** [Instance](Instance.md)

The `Class.HumanoidDescription` class manages an object that stores details about a character's appearance, including body parts, accessories, and animations.

## Properties
### `HumanoidDescription.AccessoryBlob`
- **Type:** `string`
- **Tags:** NotReplicated, NotScriptable
- **Summary:** A JSON formatted array of Layered clothing where each table in the entry in the array describes an accessory's AssetId, AccessoryType, Order, and (optionally) Puffiness as key-value pairs.

### `HumanoidDescription.BackAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its back (such as capes).

### `HumanoidDescription.BodyTypeScale`
- **Type:** `float`
- **Summary:** Determines the factor by which the shape of a `Class.Humanoid` is interpolated from the standard R15 body shape (0) to a taller and more slender body type (1).

### `HumanoidDescription.ClimbAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Climbing`.

### `HumanoidDescription.DepthScale`
- **Type:** `float`
- **Summary:** Determines by what factor the depth (back-to-front distance) of a `Class.Humanoid` is scaled.

### `HumanoidDescription.Face`
- **Type:** `int64`
- **Summary:** Determines the asset ID of the Face to be applied to the `Class.Humanoid`.

### `HumanoidDescription.FaceAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to the front of its face (such as glasses).

### `HumanoidDescription.FallAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Freefall`.

### `HumanoidDescription.FrontAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to front of its torso (such as medals or ties).

### `HumanoidDescription.GraphicTShirt`
- **Type:** `int64`
- **Summary:** Determines the `Class.ShirtGraphic.Graphic|Graphic` used by a `Class.ShirtGraphic`.

### `HumanoidDescription.HairAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its head resembling hair.

### `HumanoidDescription.HatAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its head.

### `HumanoidDescription.Head`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the Head to be applied to the `Class.Humanoid`.

### `HumanoidDescription.HeadColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.HeadColor3` and `Class.BodyColors.HeadColor` of a `Class.Humanoid` when `Class.Humanoid:ApplyDescriptionAsync()|applied`.

### `HumanoidDescription.HeadScale`
- **Type:** `float`
- **Summary:** Determines by what factor the **Head** object of a `Class.Humanoid` is scaled, as well as any accessories attached to it.

### `HumanoidDescription.HeightScale`
- **Type:** `float`
- **Summary:** Determines by what factor the height (top-to-bottom distance) of a `Class.Humanoid` is scaled, as well as all accessories not attached to its head.

### `HumanoidDescription.IdleAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Running` at a speed near zero.

### `HumanoidDescription.JumpAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Jumping`.

### `HumanoidDescription.LeftArm`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the LeftArm to be applied to the `Class.Humanoid`.

### `HumanoidDescription.LeftArmColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.LeftArmColor3` and `Class.BodyColors.LeftArmColor` of a `Class.Humanoid` when applied.

### `HumanoidDescription.LeftLeg`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the LeftLeg to be applied to the `Class.Humanoid`.

### `HumanoidDescription.LeftLegColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.LeftLegColor3` and `Class.BodyColors.LeftLegColor` of a `Class.Humanoid` when applied.

### `HumanoidDescription.MoodAnimation`
- **Type:** `int64`

### `HumanoidDescription.NeckAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its neck (such as scarves or necklaces).

### `HumanoidDescription.Pants`
- **Type:** `int64`
- **Summary:** Determines the `Class.Pants.PantsTemplate|PantsTemplate` used by a `Class.Pants` instance.

### `HumanoidDescription.ProportionScale`
- **Type:** `float`
- **Summary:** Determines how wide (0) or narrow (1) a `Class.Humanoid` rig is.

### `HumanoidDescription.RightArm`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the RightArm to be applied to the `Class.Humanoid`.

### `HumanoidDescription.RightArmColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.RightArmColor3` and `Class.BodyColors.RightArmColor` of a Humanoid when applied.

### `HumanoidDescription.RightLeg`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the RightLeg to be applied to the `Class.Humanoid`.

### `HumanoidDescription.RightLegColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.RightLegColor3` and `Class.BodyColors.RightLegColor` of a Humanoid when applied.

### `HumanoidDescription.RunAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Running` at a moderate speed.

### `HumanoidDescription.Shirt`
- **Type:** `int64`
- **Summary:** Determines the `Class.Shirt.ShirtTemplate|ShirtTemplate` used by a `Class.Shirt` instance.

### `HumanoidDescription.ShouldersAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its shoulders (such as shoulder-mounted critters).

### `HumanoidDescription.StaticFacialAnimation`
- **Type:** `boolean`
- **Summary:** When `true`, disables facial animations on a Dynamic Head, displaying a static mood pose instead. Defaults to `false`.

### `HumanoidDescription.SwimAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Swimming`.

### `HumanoidDescription.Torso`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Determines the asset ID of the Torso to be applied to the `Class.Humanoid`.

### `HumanoidDescription.TorsoColor`
- **Type:** `Color3`
- **Tags:** NotReplicated
- **Summary:** Determines the `Class.BodyColors.TorsoColor3` and `Class.BodyColors.TorsoColor` of a Humanoid when applied.

### `HumanoidDescription.UseAvatarSettings`
- **Type:** `boolean`

### `HumanoidDescription.WaistAccessory`
- **Type:** `string`
- **Tags:** NotReplicated
- **Summary:** A comma-separated list of asset IDs that will be added as `Class.Accessory|Accessories` to a `Class.Humanoid` rig when `Class.Humanoid:ApplyDescriptionAsync()|applied`, usually those attached to its waist (such as belts).

### `HumanoidDescription.WalkAnimation`
- **Type:** `int64`
- **Summary:** When this description is `Class.Humanoid:ApplyDescriptionAsync()|applied` to a `Class.Humanoid`, this determines the `Class.Animation.AnimationId` to play when its `Class.Humanoid:GetState()|state` is `Enum.HumanoidStateType|Running` at a low speed.

### `HumanoidDescription.WidthScale`
- **Type:** `float`
- **Summary:** Determines by what factor the width (left-to-right distance) of a `Class.Humanoid` is scaled, as well as all accessories not attached to its head.

## Methods
### `HumanoidDescription:AddEmote(name: string, assetId: int64) -> ()`
- **Summary:** Adds the emote to the description given a name and its asset ID.

### `HumanoidDescription:GetAccessories(includeRigidAccessories: boolean) -> Array`
- **Summary:** Returns a table of an avatar's current accessories.

### `HumanoidDescription:GetEmotes() -> Dictionary`
- **Summary:** Returns a dictionary of emotes that have been `Class.HumanoidDescription:AddEmote()|added` or `Class.HumanoidDescription:SetEmotes()|set` to this description.

### `HumanoidDescription:GetEquippedEmotes() -> Array`
- **Summary:** Returns an array of tables describing the equipped emotes that have been `Class.HumanoidDescription:SetEquippedEmotes()|set`.

### `HumanoidDescription:RemoveEmote(name: string) -> ()`
- **Summary:** Removes any emotes that have been added under the given name.

### `HumanoidDescription:SetAccessories(accessories: Array, includeRigidAccessories: boolean) -> ()`
- **Summary:** Accepts a table that sets the accessories and related properties for an avatar.

### `HumanoidDescription:SetEmotes(emotes: Dictionary) -> ()`
- **Summary:** Sets all of the emotes on this description.

### `HumanoidDescription:SetEquippedEmotes(equippedEmotes: Array) -> ()`
- **Summary:** Sets the currently equipped emotes given an array of emote names.

## Events
### `HumanoidDescription.EmotesChanged(newEmotes: Dictionary)`
- **Summary:** Fires when emotes are added, removed or set on this description.

### `HumanoidDescription.EquippedEmotesChanged(newEquippedEmotes: Array)`
- **Summary:** Fires when the equipped emotes are `Class.HumanoidDescription:SetEquippedEmotes()|set` on this description.

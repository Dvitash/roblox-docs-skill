# Lighting

**Superclass:** [Instance](Instance.md)

The `Lighting` service controls global lighting in an experience by managing adjustable properties for hue and intensity. It also includes effects like atmospheric rendering and post-processing effects.

## Tags
- NotCreatable
- Service

## Properties
### `Lighting.Ambient`
- **Type:** `Color3`
- **Summary:** The lighting hue applied to areas that are occluded from the sky, such as indoor areas.

### `Lighting.Brightness`
- **Type:** `float`
- **Summary:** The intensity of illumination in the place.

### `Lighting.ClockTime`
- **Type:** `float`
- **Tags:** NotReplicated
- **Summary:** A numerical representation (in hours) of the current time of day used by `Lighting`.

### `Lighting.ColorShift_Bottom`
- **Type:** `Color3`
- **Summary:** The hue represented in light reflected in the opposite surfaces to those facing the sun or moon.

### `Lighting.ColorShift_Top`
- **Type:** `Color3`
- **Summary:** The hue represented in light reflected from surfaces facing the sun or moon.

### `Lighting.EnvironmentDiffuseScale`
- **Type:** `float`
- **Summary:** Ambient light that is derived from the environment.

### `Lighting.EnvironmentSpecularScale`
- **Type:** `float`
- **Summary:** Specular light derived from environment.

### `Lighting.ExposureCompensation`
- **Type:** `float`
- **Summary:** The exposure compensation value.

### `Lighting.ExtendLightRangeTo120`
- **Type:** `RolloutState`
- **Tags:** NotScriptable

### `Lighting.FogColor`
- **Type:** `Color3`
- **Summary:** A `Datatype.Color3` value giving the hue of `Lighting` fog.

### `Lighting.FogEnd`
- **Type:** `float`
- **Summary:** The depth from the `Class.Workspace.CurrentCamera`, in studs, at which fog will be completely opaque.

### `Lighting.FogStart`
- **Type:** `float`
- **Summary:** The depth from the `Class.Workspace.CurrentCamera`, in studs, at which fog begins to show.

### `Lighting.GeographicLatitude`
- **Type:** `float`
- **Summary:** The geographic latitude, in degrees, of the scene, influencing the result of `Lighting` time on the position of the sun and moon.

### `Lighting.GlobalShadows`
- **Type:** `boolean`
- **Summary:** Toggles voxel-based dynamic lighting for the place.

### `Lighting.LightingStyle`
- **Type:** `LightingStyle`
- **Summary:** The artistic intent behind lighting in the experience.

### `Lighting.OutdoorAmbient`
- **Type:** `Color3`
- **Summary:** The lighting hue applied to outdoor areas.

### `Lighting.Outlines`
- **Type:** `boolean`
- **Tags:** Deprecated
- **Summary:** Determines whether outlines are enabled or disabled in a place.

### `Lighting.PrioritizeLightingQuality`
- **Type:** `boolean`
- **Summary:** Indicates whether you prefer lighting/shading quality or view distance to scale down first.

### `Lighting.ShadowColor`
- **Type:** `Color3`
- **Tags:** NotReplicated, Deprecated
- **Summary:** This is supposed to change the color of player shadows, but currently doesn't do anything.

### `Lighting.ShadowSoftness`
- **Type:** `float`
- **Summary:** Controls how blurry the shadows are.

### `Lighting.Technology`
- **Type:** `Technology`
- **Summary:** Determines the lighting system for rendering the 3D world. Non-scriptable.

### `Lighting.TimeOfDay`
- **Type:** `string`
- **Summary:** A 24-hour string representation of the current time of day used by `Lighting`.

## Methods
### `Lighting:GetMinutesAfterMidnight() -> double`
- **Summary:** Returns the number of minutes that have passed after midnight for the purposes of lighting.

### `Lighting:getMinutesAfterMidnight() -> double`
- **Tags:** Deprecated

### `Lighting:GetMoonDirection() -> Vector3`
- **Summary:** Returns a `Datatype.Vector3` representing the direction of the moon.

### `Lighting:GetMoonPhase() -> float`
- **Summary:** Returns the moon's current phase.

### `Lighting:GetSunDirection() -> Vector3`
- **Summary:** Returns a `Datatype.Vector3` representing the direction of the sun.

### `Lighting:SetMinutesAfterMidnight(minutes: double) -> ()`
- **Summary:** Sets `Class.Lighting.TimeOfDay|TimeOfDay` and `Class.Lighting.ClockTime|ClockTime` to the given number of minutes after midnight.

### `Lighting:setMinutesAfterMidnight(minutes: double) -> ()`
- **Tags:** Deprecated

## Events
### `Lighting.LightingChanged(skyChanged: boolean)`
- **Summary:** This event fires when a `Lighting` property is changed or a `Class.Sky` is added or removed from `Lighting`.

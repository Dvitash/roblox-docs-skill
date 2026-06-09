# Atmosphere

**Superclass:** [Instance](Instance.md)

The `Class.Atmosphere` object simulates realistic "aerial perspective" by controlling light transmission and haze, allowing users to control the amount of sunlight scattering and foggy effects in Roblox environments.

## Properties
### `Atmosphere.Color`
- **Type:** `Color3`
- **Summary:** Changes the `Class.Atmosphere` hue for subtle environmental moods.

### `Atmosphere.Decay`
- **Type:** `Color3`
- **Summary:** When used with increased `Class.Atmosphere.Haze` and `Class.Atmosphere.Glare`, defines the hue of the `Class.Atmosphere` away from the sun, gradually falling off from `Class.Atmosphere.Color` towards this value.

### `Atmosphere.Density`
- **Type:** `float`
- **Summary:** Defines the amount of particles in the `Class.Atmosphere` and essentially controls how much in-game objects/terrain will be obscured by them.

### `Atmosphere.Glare`
- **Type:** `float`
- **Summary:** When used with increased `Class.Atmosphere.Haze`, specifies the glow/glare of the `Class.Atmosphere` around the sun. More glare results in an increased effect of sunlight cast onto the sky and world.

### `Atmosphere.Haze`
- **Type:** `float`
- **Summary:** Defines the haziness of the `Class.Atmosphere` with a visible effect both above the horizon and into the distance.

### `Atmosphere.Offset`
- **Type:** `float`
- **Summary:** Controls how light transmits between the camera and the sky background.

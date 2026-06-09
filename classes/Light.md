# Light

**Superclass:** [Instance](Instance.md)

Light is a root class for dynamic lighting objects in RBPF. It defines properties like Brightness and Color, and includes methods for emitting light and shadow projection.

## Tags
- NotCreatable

## Properties
### `Light.Brightness`
- **Type:** `float`
- **Summary:** Sets how bright the emitted light is, defaults to 1.

### `Light.Color`
- **Type:** `Color3`
- **Summary:** The color of the emitted light.

### `Light.Enabled`
- **Type:** `boolean`
- **Summary:** If set to true, light will be emitted from the source object.

### `Light.Shadows`
- **Type:** `boolean`
- **Summary:** If set to true, will project shadows if light is blocked by an obstacle.

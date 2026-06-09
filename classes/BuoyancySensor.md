# BuoyancySensor

**Superclass:** [SensorBase](SensorBase.md)

This file defines `BuoyancySensor` classes that output data on the interaction of a `Class.BasePart` with `Class.Terrain` water, allowing for determining if an object is or is not in water.

## Properties
### `BuoyancySensor.FullySubmerged`
- **Type:** `boolean`
- **Summary:** True when the entirety of the `Class.BasePart` is submerged in `Class.Terrain` water with at least one voxel of water above it.

### `BuoyancySensor.TouchingSurface`
- **Type:** `boolean`
- **Summary:** True when any position on the `Class.BasePart` is touching `Class.Terrain` water.

# FluidForceSensor

**Superclass:** [SensorBase](SensorBase.md)

FluidForceSensor is a `Class.SensorBase` that outputs the results of fluid force simulation from the last physics frame for a specific attachment point.

## Properties
### `FluidForceSensor.CenterOfPressure`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Assembly center of pressure offset from its center of mass in world coordinates.

### `FluidForceSensor.Force`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Assembly fluid force in world coordinates.

### `FluidForceSensor.Torque`
- **Type:** `Vector3`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Assembly fluid torque in world coordinates.

## Methods
### `FluidForceSensor:EvaluateAsync(linearVelocity: Vector3, angularVelocity: Vector3, cframe: CFrame) -> Tuple`
- **Tags:** Yields
- **Summary:** Asynchronously computes force, torque, and center of pressure for the parent part of a sensor given provided inputs.

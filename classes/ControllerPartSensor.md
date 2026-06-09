# ControllerPartSensor

**Superclass:** [ControllerSensor](ControllerSensor.md)

A `ControllerPartSensor` class is a `Class.SensorBase` that outputs data based on `Class.Humanoid` floor and ladder detection logic, allowing for sending sensor data to character controllers.

## Properties
### `ControllerPartSensor.HitFrame`
- **Type:** `CFrame`
- **Summary:** The position in world space where the sensor hit the `Class.ControllerPartSensor.SensedPart`.

### `ControllerPartSensor.HitNormal`
- **Type:** `Vector3`
- **Summary:** The surface normal at the position where the sensor hit the `Class.ControllerPartSensor.SensedPart`.

### `ControllerPartSensor.LadderSearchHeight`
- **Type:** `float`

### `ControllerPartSensor.LadderSearchOffset`
- **Type:** `float`

### `ControllerPartSensor.SearchDistance`
- **Type:** `float`
- **Summary:** The distance from the sensor's parent `Class.BasePart` to use when sensing other parts.

### `ControllerPartSensor.SensedMaterial`
- **Type:** `Material`

### `ControllerPartSensor.SensedPart`
- **Type:** `[BasePart](BasePart.md)`
- **Summary:** A reference to the `Class.BasePart` hit by the sensor.

### `ControllerPartSensor.SensorMode`
- **Type:** `SensorMode`
- **Summary:** Determines what behavior this `Class.SensorBase` uses when sensing other parts.

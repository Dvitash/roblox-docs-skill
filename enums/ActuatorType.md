# Enum.ActuatorType

The active physics component of the constraint.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `None` | 0 |  | The motor and servo components are both disabled. |
| `Motor` | 1 |  | The motor component is enabled. Motor properties are active and the actuator will apply continuous force. |
| `Servo` | 2 |  | The servo component is enabled. Servo properties are active and the actuator will apply force to approach the servo's target. |

**Valid values:** `Enum.ActuatorType.None`, `Enum.ActuatorType.Motor`, `Enum.ActuatorType.Servo`

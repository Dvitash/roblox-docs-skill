# JointsService

**Superclass:** [Instance](Instance.md)

JointsService is a class for storing joint information from surface connections, along with methods to manage visibility and set connections.

## Tags
- NotCreatable
- Service
- Deprecated

## Methods
### `JointsService:ClearJoinAfterMoveJoints() -> ()`
- **Summary:** Will remove any 'create joints' that were made visible via the `Class.JointsService:ShowPermissibleJoints()` method.

### `JointsService:CreateJoinAfterMoveJoints() -> ()`
- **Summary:** Updates all visible joints for the parts assigned by the `Class.JointsService:SetJoinAfterMoveTarget()` and `Class.JointsService:SetJoinAfterMoveInstance()` methods.

### `JointsService:SetJoinAfterMoveInstance(joinInstance: [Instance](Instance.md)) -> ()`
- **Summary:** Sets the PVInstance that will be connected with the target PVInstance specified by `Class.JointsService:SetJoinAfterMoveTarget()`.

### `JointsService:SetJoinAfterMoveTarget(joinTarget: [Instance](Instance.md)) -> ()`
- **Summary:** Sets the PVInstance that will be connected with the PVInstance specified by `Class.JointsService:SetJoinAfterMoveInstance()`.

### `JointsService:ShowPermissibleJoints() -> ()`
- **Summary:** When used it will visibly display a potential surface connection between the two `Class.BasePart`, which were set with `Class.JointsService:SetJoinAfterMoveTarget()` and `Class.JointsService:SetJoinAfterMoveInstance()`.

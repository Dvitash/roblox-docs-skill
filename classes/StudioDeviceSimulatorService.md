# StudioDeviceSimulatorService

**Superclass:** [Instance](Instance.md)

The `StudioDeviceSimulatorService` is a class that provides programmatic control over Studio's Device Simulator, allowing users to switch presets, override resolution, and manage orientation and scaling.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `StudioDeviceSimulatorService:CreateDeviceAsync(config: Dictionary) -> string`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetDeviceAsync() -> string`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetDeviceInfoAsync(deviceId: string) -> Dictionary`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetDeviceListAsync() -> Array`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetOrientationAsync() -> ScreenOrientation`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetPixelDensityAsync() -> float`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetResolutionAsync() -> Vector2`
- **Tags:** Yields

### `StudioDeviceSimulatorService:GetScalingModeAsync() -> DeviceSimulatorScalingMode`
- **Tags:** Yields

### `StudioDeviceSimulatorService:RemoveDeviceAsync(deviceId: string) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:SetDeviceAsync(deviceId: string) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:SetOrientationAsync(orientation: ScreenOrientation) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:SetPixelDensityAsync(density: float) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:SetResolutionAsync(width: int, height: int) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:SetScalingModeAsync(mode: DeviceSimulatorScalingMode) -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:StopSimulationAsync() -> ()`
- **Tags:** Yields

### `StudioDeviceSimulatorService:UpdateDeviceAsync(deviceId: string, config: Dictionary) -> ()`
- **Tags:** Yields

## Events
### `StudioDeviceSimulatorService.ConfigurationChanged()`

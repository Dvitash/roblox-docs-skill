# VRService

**Superclass:** [Instance](Instance.md)

The `VRService` class is a class responsible for handling interactions between Roblox and Virtual Reality (VR) devices. It provides methods, properties, and events to ensure the best user experience for VR users.

## Tags
- NotCreatable
- Service

## Properties
### `VRService.AutomaticScaling`
- **Type:** `VRScaling`
- **Summary:** Automatically adjusts scaling in VR to align the player with their avatar.

### `VRService.AvatarGestures`
- **Type:** `boolean`
- **Summary:** When true, a VR player will be able to animate their hands and head using their controllers and headset.

### `VRService.ControllerModels`
- **Type:** `VRControllerModelMode`

### `VRService.FadeOutViewOnCollision`
- **Type:** `boolean`
- **Summary:** When true, a VR player's view will fade to black when their head collides with an object.

### `VRService.GuiInputUserCFrame`
- **Type:** `UserCFrame`
- **Tags:** NotReplicated
- **Summary:** Describes what `Enum.UserCFrame` is responsible for input in VR.

### `VRService.LaserPointer`
- **Type:** `VRLaserPointerMode`

### `VRService.ThirdPersonFollowCamEnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `VRService.VREnabled`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Describes whether the user is using a virtual reality device.

## Methods
### `VRService:GetTouchpadMode(pad: VRTouchpad) -> VRTouchpadMode`
- **Summary:** Returns the VRTouchpadMode indicating the mode of a specified VRTouchpad.

### `VRService:GetUserCFrame(type: UserCFrame) -> CFrame`
- **Summary:** Returns a CFrame describing the position &amp; orientation of a specified virtual reality device as an offset from a point in real world space.

### `VRService:GetUserCFrameEnabled(type: UserCFrame) -> boolean`
- **Summary:** Returns true if the specified `Enum.UserCFrame` is available to be listened to.

### `VRService:RecenterUserHeadCFrame() -> ()`
- **Summary:** Re-centers the `Datatype.CFrame` to the current location of the VR headset being worn by the user.

### `VRService:RequestNavigation(cframe: CFrame, inputUserCFrame: UserCFrame) -> ()`
- **Summary:** Requests navigation to the specified `Datatype.CFrame` using the specified `Enum.UserCFrame` as the origin for the visualizer parabola.

### `VRService:SetTouchpadMode(pad: VRTouchpad, mode: VRTouchpadMode) -> ()`
- **Summary:** Sets the mode of the specified `Enum.VRTouchpad` to the specified `Enum.VRTouchpadMode`.

## Events
### `VRService.NavigationRequested(cframe: CFrame, inputUserCFrame: UserCFrame)`
- **Summary:** Fired when navigation is requested from `Class.VRService`.

### `VRService.TouchpadModeChanged(pad: VRTouchpad, mode: VRTouchpadMode)`
- **Summary:** Fires if the `Enum.VRTouchpadMode` of a `Enum.VRTouchpad` is changed.

### `VRService.UserCFrameChanged(type: UserCFrame, value: CFrame)`
- **Summary:** Fires when a `Enum.UserCFrame` is changed.

### `VRService.UserCFrameEnabled(type: UserCFrame, enabled: boolean)`
- **Summary:** Fires when a `Enum.UserCFrame` is enabled or disabled.

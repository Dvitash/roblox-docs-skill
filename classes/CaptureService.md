# CaptureService

**Superclass:** [Instance](Instance.md)

The `CaptureService` is a client-side service that allows developers to control how screenshot and video capture features integrate with their experiences, enabling preset moments where captures are automatically taken and saved.

## Tags
- NotCreatable
- Service

## Methods
### `CaptureService:CaptureScreenshot(onCaptureReady: Function) -> ()`
- **Summary:** Takes a screenshot and provides a temporary `contentId` to identify it.

### `CaptureService:CheckUploadCaptureStatusAsync(token: string) -> Tuple`
- **Tags:** Yields

### `CaptureService:PromptCaptureGalleryPermissionAsync(captureGalleryPermission: CaptureGalleryPermission) -> boolean`
- **Tags:** Yields

### `CaptureService:PromptSaveCapturesToGallery(captures: Array, resultCallback: Function) -> ()`
- **Summary:** Prompts the user to save specified captures to their gallery.

### `CaptureService:PromptShareCapture(captureContent: Content, launchData: string, onAcceptedCallback: Function, onDeniedCallback: Function) -> ()`
- **Summary:** Prompts the user to share a specified capture.

### `CaptureService:ReadCapturesFromGalleryAsync(captureTypeFilters: Array, readFromAllEligibleExperiences: boolean) -> Tuple`
- **Tags:** Yields

### `CaptureService:StartUploadCaptureAsync(capture: [Capture](Capture.md)) -> Tuple`
- **Tags:** Yields

### `CaptureService:StartVideoCaptureAsync(onCaptureReady: Function, captureParams: Dictionary) -> VideoCaptureStartedResult`
- **Tags:** Yields
- **Summary:** Initiates a video capture recording.

### `CaptureService:StopVideoCapture() -> ()`
- **Summary:** Ends a video capture initiated by `Class.CaptureService:StartVideoCaptureAsync()|StartVideoCaptureAsync()`.

### `CaptureService:TakeScreenshotCaptureAsync(onCaptureReady: Function, captureParams: Dictionary) -> ()`
- **Summary:** Initiates a screenshot capture.

### `CaptureService:UploadCaptureAsync(capture: [Capture](Capture.md)) -> Tuple`
- **Tags:** Yields

## Events
### `CaptureService.CaptureBegan(captureType: CaptureType)`
- **Summary:** Fires immediately before a capture begins.

### `CaptureService.CaptureEnded(captureType: CaptureType)`
- **Summary:** Fires after a capture finishes.

### `CaptureService.CaptureSaved(captureInfo: Dictionary)`
- **Tags:** Deprecated

### `CaptureService.UserCaptureSaved(captureContentId: ContentId)`
- **Summary:** Fires when the user saves a capture.

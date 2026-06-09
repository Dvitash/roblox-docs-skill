# StudioScreenshotCapture

**Superclass:** [Instance](Instance.md)

This file contains documentation for the `StudioScreenshotCapture` class, detailing its memory categories, properties, and methods related to capturing screenshots.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `StudioScreenshotCapture.BufferFormat`
- **Type:** `StudioCaptureScreenshotFormat`
- **Tags:** ReadOnly, NotReplicated

### `StudioScreenshotCapture.BufferStatus`
- **Type:** `StudioCaptureBufferStatus`
- **Tags:** ReadOnly, NotReplicated

### `StudioScreenshotCapture.OriginalSize`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated

### `StudioScreenshotCapture.Position`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated

### `StudioScreenshotCapture.Resolution`
- **Type:** `Vector2`
- **Tags:** ReadOnly, NotReplicated

### `StudioScreenshotCapture.UICaptureMode`
- **Type:** `UICaptureMode`
- **Tags:** ReadOnly, NotReplicated

## Methods
### `StudioScreenshotCapture:GetBuffer() -> buffer`

### `StudioScreenshotCapture:GetErrors() -> Array`

### `StudioScreenshotCapture:ScaleAsync(strategy: ResamplerMode, newSize: Vector2) -> [StudioScreenshotCapture](StudioScreenshotCapture.md)`
- **Tags:** Yields

# VideoSampler

**Superclass:** [Object](Object.md)

VideoSampler is an object that allows sampling frames from a video's `VideoContent` at specific timestamps. It can be created by calling `Class.VideoService:CreateVideoSamplerAsync()`.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `VideoSampler.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The length of the `Class.VideoSampler.VideoContent|VideoContent` in seconds.

### `VideoSampler.VideoContent`
- **Type:** `Content`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The asset loaded into the `Class.VideoSampler`.

## Methods
### `VideoSampler:GetSamplesAtTimesAsync(times: Array) -> Array`
- **Tags:** Yields
- **Summary:** Gets image frames at the specified timestamps.

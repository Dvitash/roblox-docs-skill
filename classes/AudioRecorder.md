# AudioRecorder

**Superclass:** [Instance](Instance.md)

This file contains documentation for the `AudioRecorder` class, which records audio streams in-experience with a fixed time limit of 60 seconds.

## Tags
- NotBrowsable

## Properties
### `AudioRecorder.IsRecording`
- **Type:** `boolean`
- **Summary:** Whether the `AudioRecorder` is currently recording.

### `AudioRecorder.TimeLength`
- **Type:** `double`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current length of the recording in seconds.

## Methods
### `AudioRecorder:CanRecordAsync() -> boolean`
- **Tags:** Yields
- **Summary:** Returns whether the `AudioRecorder` can currently record.

### `AudioRecorder:Clear() -> ()`
- **Summary:** Clears out the recording from the `AudioRecorder`.

### `AudioRecorder:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

### `AudioRecorder:GetInputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.TargetName` to connect to this instance via its `Class.Wire.TargetInstance` property.

### `AudioRecorder:GetOutputPins() -> Array`
- **Summary:** Gets the list of pins that `Class.Wire` can use in `Class.Wire.SourceName` to connect to this instance via its `Class.Wire.SourceInstance` property.

### `AudioRecorder:GetTemporaryContent() -> Content`
- **Summary:** Returns a `Content` object representing the current audio recording.

### `AudioRecorder:GetUnrecordableInstancesAsync() -> List<[Instance](Instance.md)>`
- **Tags:** Yields
- **Summary:** Returns any instances which cannot be recorded.

### `AudioRecorder:RecordAsync() -> ()`
- **Tags:** Yields
- **Summary:** Starts recording audio.

### `AudioRecorder:Stop() -> ()`
- **Summary:** Stops recording audio.

## Events
### `AudioRecorder.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioRecorder` via a `Class.Wire`.

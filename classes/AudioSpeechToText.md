# AudioSpeechToText

**Superclass:** [Instance](Instance.md)

Converts spoken audio into text using a class called `AudioSpeechToText`. This function uses a single input pin to connect to other pins for processing speech.

## Properties
### `AudioSpeechToText.Enabled`
- **Type:** `boolean`
- **Summary:** Whether the `Class.AudioSpeechToText` object is enabled for processing input audio into text.

### `AudioSpeechToText.Text`
- **Type:** `string`
- **Summary:** The text resulting from the conversion of speech audio.

### `AudioSpeechToText.VoiceDetected`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Whether the `Class.AudioSpeechToText` object is detecting speech in the incoming audio signal.

## Methods
### `AudioSpeechToText:GetConnectedWires(pin: string) -> List<[Wire](Wire.md)>`
- **Summary:** Returns an array of `Class.Wire|Wires` that are connected to the specified pin.

## Events
### `AudioSpeechToText.WiringChanged(connected: boolean, pin: string, wire: [Wire](Wire.md), instance: [Instance](Instance.md))`
- **Summary:** Fires when another instance is connected to or disconnected from the `Class.AudioSpeechToText` via a `Class.Wire`.

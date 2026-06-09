# Enum.AudioFilterType

Filter types used for `Class.AudioFilter` instances.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Peak` | 0 |  | Filter that boosts or reduces sound near a specified `Class.AudioFilter.Frequency\|Frequency`. |
| `LowShelf` | 1 |  | Filter that boosts or reduces sound below a specified `Class.AudioFilter.Frequency\|Frequency`. |
| `HighShelf` | 2 |  | Filter that boosts or reduces sound above a specified `Class.AudioFilter.Frequency\|Frequency`. |
| `Lowpass12dB` | 3 |  | Filter that cuts sound above a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -12dB/octave. |
| `Lowpass24dB` | 4 |  | Filter that cuts sound above a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -24dB/octave. |
| `Lowpass48dB` | 5 |  | Filter that cuts sound above a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -48dB/octave. |
| `Highpass12dB` | 6 |  | Filter that cuts sound below a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -12dB/octave. |
| `Highpass24dB` | 7 |  | Filter that cuts sound below a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -24dB/octave. |
| `Highpass48dB` | 8 |  | Filter that cuts sound below a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -48dB/octave. |
| `Bandpass` | 9 |  | Filter that only allows sound near a specified `Class.AudioFilter.Frequency\|Frequency` to be heard. |
| `Notch` | 10 |  | Filter that cuts sound near a specified `Class.AudioFilter.Frequency\|Frequency`. |
| `Lowpass6dB` | 11 |  | Filter that cuts sound above a specified `Class.AudioFilter.Frequency\|Frequency`, at a slope of -6dB/octave. |

**Valid values:** `Enum.AudioFilterType.Peak`, `Enum.AudioFilterType.LowShelf`, `Enum.AudioFilterType.HighShelf`, `Enum.AudioFilterType.Lowpass12dB`, `Enum.AudioFilterType.Lowpass24dB`, `Enum.AudioFilterType.Lowpass48dB`, `Enum.AudioFilterType.Highpass12dB`, `Enum.AudioFilterType.Highpass24dB`, `Enum.AudioFilterType.Highpass48dB`, `Enum.AudioFilterType.Bandpass`, `Enum.AudioFilterType.Notch`, `Enum.AudioFilterType.Lowpass6dB`

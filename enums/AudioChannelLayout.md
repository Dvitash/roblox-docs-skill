# Enum.AudioChannelLayout

Describes the channel layout of an audio stream.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Mono` | 0 |  | Monaural audio streams contain only one **Center** channel. <img src="/assets/engine-api/enums/AudioChannelLayout/Mono.jpg" width="810" alt="Diagram showing position of channels for Mono layout." /> |
| `Stereo` | 1 |  | Stereophonic audio streams consist of two channels: **Left** and **Right**. <img src="/assets/engine-api/enums/AudioChannelLayout/Stereo.jpg" width="810" alt="Diagram showing position of channels for Stereo layout." /> |
| `Quad` | 2 |  | Quadrophonic audio streams consist of four channels: **Left**, **Right**, **BackLeft**, and **BackRight**. Quadrophonic streams can encode forward/backward spatial information that stereo streams might struggle with. <img src="/assets/engine-api/enums/AudioChannelLayout/Quad.jpg" width="810" alt="Diagram showing position of channels for Quad layout." /> |
| `Surround_5` | 3 |  | Surround sound audio streams consist of five channels: **Left**, **Right**, **Center**, **BackLeft**, and **BackRight**. Surround sound streams encode spatial information with better resolution front and center. <img src="/assets/engine-api/enums/AudioChannelLayout/Surround_5.jpg" width="810" alt="Diagram showing position of channels for Surround 5 layout." /> |
| `Surround_5_1` | 4 |  | 5.1 surround sound consists of six channels: **Left**, **Right**, **Center**, **BackLeft**, **BackRight**, and a **Sub** (subsonic) low‑frequency channel. 5.1 surround sound benefits from low frequencies being less directional in order to encode higher resolution spatial information versus simple 5‑channel surround sound. <img src="/assets/engine-api/enums/AudioChannelLayout/Surround_5_1.jpg" width="810" alt="Diagram showing position of channels for Surround 5.1 layout." /> |
| `Surround_7_1` | 5 |  | 7.1 surround sound consists of eight channels: **Left**, **Right**, **Center**, **SurroundLeft**, **SurroundRight**, **BackLeft**, **BackRight**, and a **Sub** (subsonic) low‑frequency channel. 7.1 surround sound is an improvement over 5.1 surround sound, offering better spatial resolution directly to the left and right as well. <img src="/assets/engine-api/enums/AudioChannelLayout/Surround_7_1.jpg" width="810" alt="Diagram showing position of channels for Surround 7.1 layout." /> |
| `Surround_7_1_4` | 6 |  | 7.1.4 surround sound consists of twelve channels: **Left**, **Right**, **Center**, **SurroundLeft**, **SurroundRight**, **BackLeft**, **BackRight**, **Sub**, **TopLeft**, **TopRight**, **TopBackLeft**, and **TopBackRight**. 7.1.4 is the only currently supported channel layout that encodes height information. <img src="/assets/engine-api/enums/AudioChannelLayout/Surround_7_1_4.jpg" width="810" alt="Diagram showing position of channels for Surround 7.1.4 layout." /> |

**Valid values:** `Enum.AudioChannelLayout.Mono`, `Enum.AudioChannelLayout.Stereo`, `Enum.AudioChannelLayout.Quad`, `Enum.AudioChannelLayout.Surround_5`, `Enum.AudioChannelLayout.Surround_5_1`, `Enum.AudioChannelLayout.Surround_7_1`, `Enum.AudioChannelLayout.Surround_7_1_4`

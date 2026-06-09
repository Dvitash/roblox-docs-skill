# Enum.ModelStreamingBehavior

Controls how `Class.Model|Models` are sent to clients in experiences with instance streaming enabled.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Default` | 0 |  | Default behavior (subject to change). |
| `Legacy` | 1 |  | Models are sent when their parent is sent, typically during player join. Models are never streamed out unless an ancestor of the model is streamed out. |
| `Improved` | 2 |  | Models are never sent during player join. See [model streaming controls](../../../workspace/streaming/index.md#model-streaming-controls) for detailed behavioral notes. |

**Valid values:** `Enum.ModelStreamingBehavior.Default`, `Enum.ModelStreamingBehavior.Legacy`, `Enum.ModelStreamingBehavior.Improved`

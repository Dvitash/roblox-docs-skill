# Enum.DebuggerStatus

Result of a debugger request.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Success` | 0 |  | Request has completed successfully. |
| `Timeout` | 1 |  | Timed out while waiting for response. |
| `ConnectionLost` | 2 |  | Connection to the debugger was lost. |
| `InvalidResponse` | 3 |  | Failed to parse response. |
| `InternalError` | 4 |  | Exception encountered while processing response. |
| `InvalidState` | 5 |  | The request was not appropriate for the current debugger state. |
| `RpcError` | 6 |  | Response was an error. |
| `InvalidArgument` | 7 |  | One of the request arguments was invalid. |
| `ConnectionClosed` | 8 |  | Connection closed while waiting for response. |

**Valid values:** `Enum.DebuggerStatus.Success`, `Enum.DebuggerStatus.Timeout`, `Enum.DebuggerStatus.ConnectionLost`, `Enum.DebuggerStatus.InvalidResponse`, `Enum.DebuggerStatus.InternalError`, `Enum.DebuggerStatus.InvalidState`, `Enum.DebuggerStatus.RpcError`, `Enum.DebuggerStatus.InvalidArgument`, `Enum.DebuggerStatus.ConnectionClosed`

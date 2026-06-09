# Enum.DebuggerEndReason

Reason for the end of the debugger session.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `ClientRequest` | 0 |  | Client requested connection termination. |
| `Timeout` | 1 |  | Connection timed out. |
| `InvalidHost` | 2 |  | Invalid host:port combination. |
| `Disconnected` | 3 |  | Connection was lost. |
| `ServerShutdown` | 4 |  | Server terminated the connection because it shut down. |
| `ServerProtocolMismatch` | 5 |  | Server has wrong version of protocol. |
| `ConfigurationFailed` | 6 |  | Got a failure response when trying to configure the server. |
| `RpcError` | 7 |  | An error occurred in the RPC layer. |

**Valid values:** `Enum.DebuggerEndReason.ClientRequest`, `Enum.DebuggerEndReason.Timeout`, `Enum.DebuggerEndReason.InvalidHost`, `Enum.DebuggerEndReason.Disconnected`, `Enum.DebuggerEndReason.ServerShutdown`, `Enum.DebuggerEndReason.ServerProtocolMismatch`, `Enum.DebuggerEndReason.ConfigurationFailed`, `Enum.DebuggerEndReason.RpcError`

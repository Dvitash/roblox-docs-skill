# Enum.ReceiptType

`ReceiptType` is used to work with server-sided receipt processing.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `DeveloperProduct` | 0 |  |  |
| `RobuxTransferSender` | 1 |  | Used for processing receipts for the user who initiated a Robux transfer. The receipt's `PlayerId` is the sender's user ID and includes a `TransferRequestId` field. Delivered immediately if the transfer settles synchronously. If receiver approval is required, delivered to the server the sender is currently in once the receiver accepts, or on the sender's next session join if they are offline. |
| `RobuxTransferReceiver` | 2 |  | Used for processing receipts for the user who received Robux via a transfer. The receipt's `PlayerId` is the receiver's user ID and includes a `TransferRequestId` field. Delivered to the server the receiver is currently in once the transfer settles, or on their next session join if they are offline. |

**Valid values:** `Enum.ReceiptType.DeveloperProduct`, `Enum.ReceiptType.RobuxTransferSender`, `Enum.ReceiptType.RobuxTransferReceiver`

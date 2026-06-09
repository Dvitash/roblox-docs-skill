# Enum.ReceiptDecision

`ReceiptDecision` works with `Class.MarketplaceService` to indicate the acknowledgement of receipts.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `NotProcessedYet` | 0 |  | The receipt has not been processed yet. Returning this value keeps the receipt unresolved so it will be redelivered to the user's handler later, either during their existing session or the next time they join a server if they have disconnected. |
| `Processed` | 1 |  | The receipt has been processed and all benefits have been granted. The receipt is marked as complete and will not be delivered again. |

**Valid values:** `Enum.ReceiptDecision.NotProcessedYet`, `Enum.ReceiptDecision.Processed`

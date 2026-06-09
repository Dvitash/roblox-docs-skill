# Enum.MarketplaceBulkPurchasePromptStatus

The status of the BulkPurchasePrompt after player interaction.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Completed` | 1 |  | User confirmed the purchase and the transaction has been processed. |
| `Aborted` | 2 |  | User closed the prompt. |
| `Error` | 3 |  | User confirmed the purchase, but the transaction cannot be sent to the backend for processing. |

**Valid values:** `Enum.MarketplaceBulkPurchasePromptStatus.Completed`, `Enum.MarketplaceBulkPurchasePromptStatus.Aborted`, `Enum.MarketplaceBulkPurchasePromptStatus.Error`

# Enum.MarketplaceItemPurchaseStatus

The status of the item purchase through MarketplaceService.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Success` | 1 |  | The item is purchased successfully. |
| `SystemError` | 2 |  | Unable to purchase item due to Roblox system error. |
| `AlreadyOwned` | 3 |  | Unable to purchase item because user already owns the item. Users can only own one copy of non-limited item. |
| `InsufficientRobux` | 4 |  | Unable to purchase item because of insufficient Robux. |
| `QuantityLimitExceeded` | 5 |  | User has reached the max quantity allowed per user set by the creator for limited items. |
| `QuotaExceeded` | 6 |  | The user has exceeded our [purchase request limit](../../../marketplace/marketplace-fees-and-commissions.md#rate-limits). |
| `NotForSale` | 7 |  | Item is not for sale. |
| `NotAvailableForPurchaser` | 8 |  | This item is restricted to a group of users and the purchaser is not in this group. |
| `PriceMismatch` | 9 |  | The provided price does not match the item price. Most likely the price changed since displayed to the user. |
| `SoldOut` | 10 |  | The item is sold out. |
| `PurchaserIsSeller` | 11 |  | The purchaser is the same user as the seller, for a resale purchase. |
| `InsufficientMembership` | 12 |  | The user does not have sufficient premium membership to purchase this item. |
| `PlaceInvalid` | 13 |  | The item is not allowed to be sold in the place. |

**Valid values:** `Enum.MarketplaceItemPurchaseStatus.Success`, `Enum.MarketplaceItemPurchaseStatus.SystemError`, `Enum.MarketplaceItemPurchaseStatus.AlreadyOwned`, `Enum.MarketplaceItemPurchaseStatus.InsufficientRobux`, `Enum.MarketplaceItemPurchaseStatus.QuantityLimitExceeded`, `Enum.MarketplaceItemPurchaseStatus.QuotaExceeded`, `Enum.MarketplaceItemPurchaseStatus.NotForSale`, `Enum.MarketplaceItemPurchaseStatus.NotAvailableForPurchaser`, `Enum.MarketplaceItemPurchaseStatus.PriceMismatch`, `Enum.MarketplaceItemPurchaseStatus.SoldOut`, `Enum.MarketplaceItemPurchaseStatus.PurchaserIsSeller`, `Enum.MarketplaceItemPurchaseStatus.InsufficientMembership`, `Enum.MarketplaceItemPurchaseStatus.PlaceInvalid`

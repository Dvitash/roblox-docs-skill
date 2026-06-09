# Enum.DataStoreRequestType

Indicates the type of data store request being made.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `GetAsync` | 0 |  | Refers to `Class.GlobalDataStore:GetAsync()\|GetAsync()` and the read of `Class.GlobalDataStore:UpdateAsync()\|UpdateAsync()`. |
| `SetIncrementAsync` | 1 |  | Refers to `Class.DataStore:SetAsync()\|SetAsync()`, `Class.DataStore:IncrementAsync()\|IncrementAsync()`, `Class.DataStore:RemoveAsync()\|RemoveAsync()`, and the write of `Class.DataStore:UpdateAsync()\|UpdateAsync()` when it returns a non-`nil` value. |
| `UpdateAsync` | 2 |  | Refers to `Class.GlobalDataStore:UpdateAsync()\|UpdateAsync()`. |
| `GetSortedAsync` | 3 |  | Refers to `Class.OrderedDataStore:GetSortedAsync()\|GetSortedAsync()`. |
| `SetIncrementSortedAsync` | 4 |  | Refers to `Class.OrderedDataStore:SetAsync()\|SetAsync()` `Class.OrderedDataStore:IncrementAsync()\|IncrementAsync()`, `Class.OrderedDataStore:RemoveAsync()\|RemoveAsync()`, and the write of `Class.OrderedDataStore:UpdateAsync()\|UpdateAsync()` while using an `Class.OrderedDataStore`. |
| `OnUpdate` | 5 |  | Refers to `Class.GlobalDataStore:OnUpdate()\|OnUpdate()`. |
| `ListAsync` | 6 |  | Refers to `Class.DataStore:ListKeysAsync()\|ListKeysAsync()` and `Class.DataStore:ListVersionsAsync()\|ListVersionsAsync()`. |
| `GetVersionAsync` | 7 |  | Refers to `Class.DataStore:GetVersionAsync()\|GetVersionAsync()`. |
| `RemoveVersionAsync` | 8 |  | Refers to `Class.DataStore:RemoveVersionAsync()\|RemoveVersionAsync()`. |
| `StandardRead` | 9 |  | Refers to `Class.DataStore:GetAsync()\|GetAsync()`, `Class.DataStore:GetVersionAsync()\|GetVersionAsync()`, `Class.DataStore:GetVersionAtTimeAsync()\|GetVersionAtTimeAsync()`, and the read of `Class.DataStore:UpdateAsync()\|UpdateAsync()` for `Class.DataStore\|DataStore`. |
| `StandardWrite` | 10 |  | Refers to `Class.DataStore:SetAsync()\|SetAsync()`, `Class.DataStore:IncrementAsync()\|IncrementAsync()`, and the write of `Class.DataStore:UpdateAsync()\|UpdateAsync()` for `Class.DataStore\|DataStore`. |
| `StandardList` | 11 |  | Refers to `Class.DataStoreService:ListDataStoresAsync()\|ListDataStoresAsync()`, and `Class.DataStore:ListKeysAsync()\|ListKeysAsync()` and `Class.DataStore:ListVersionsAsync()\|ListVersionsAsync()` for `Class.DataStore\|DataStore`. |
| `StandardRemove` | 12 |  | Refers to `Class.DataStore:RemoveAsync()\|RemoveAsync()` for `Class.DataStore\|DataStore`. |
| `OrderedRead` | 13 |  | Refers to `Class.OrderedDataStore:GetAsync()\|GetAsync()` and the read of `Class.OrderedDataStore:UpdateAsync()\|UpdateAsync()` for `Class.OrderedDataStore\|OrderedDataStore`. |
| `OrderedWrite` | 14 |  | Refers to `Class.OrderedDataStore:SetAsync()\|SetAsync()`, `Class.OrderedDataStore:IncrementAsync()\|IncrementAsync()`, and the write of `Class.OrderedDataStore:UpdateAsync()\|UpdateAsync()` for `Class.OrderedDataStore\|OrderedDataStore`. |
| `OrderedList` | 15 |  | Refers to `Class.OrderedDataStore:GetSortedAsync()\|GetSortedAsync()` for `Class.OrderedDataStore\|OrderedDataStore`. GetRequestBudgetForRequestType()`with this enum will return`0`. |
| `OrderedRemove` | 16 |  | Refers to `Class.OrderedDataStore:RemoveAsync()\|RemoveAsync()` for `Class.OrderedDataStore\|OrderedDataStore`. |

**Valid values:** `Enum.DataStoreRequestType.GetAsync`, `Enum.DataStoreRequestType.SetIncrementAsync`, `Enum.DataStoreRequestType.UpdateAsync`, `Enum.DataStoreRequestType.GetSortedAsync`, `Enum.DataStoreRequestType.SetIncrementSortedAsync`, `Enum.DataStoreRequestType.OnUpdate`, `Enum.DataStoreRequestType.ListAsync`, `Enum.DataStoreRequestType.GetVersionAsync`, `Enum.DataStoreRequestType.RemoveVersionAsync`, `Enum.DataStoreRequestType.StandardRead`, `Enum.DataStoreRequestType.StandardWrite`, `Enum.DataStoreRequestType.StandardList`, `Enum.DataStoreRequestType.StandardRemove`, `Enum.DataStoreRequestType.OrderedRead`, `Enum.DataStoreRequestType.OrderedWrite`, `Enum.DataStoreRequestType.OrderedList`, `Enum.DataStoreRequestType.OrderedRemove`

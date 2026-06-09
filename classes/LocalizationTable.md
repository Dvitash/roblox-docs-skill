# LocalizationTable

**Superclass:** [Instance](Instance.md)

LocalizationTables are databases containing translations for various languages, used by `Class.Translator` and `Class.LocalizationService` to control text translations in the game.

## Properties
### `LocalizationTable.DevelopmentLanguage`
- **Type:** `string`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** The default IETF tag to use if the ''languageKey'' parameter is excluded from the `Class.LocalizationTable:GetString()` method.

### `LocalizationTable.Root`
- **Type:** `[Instance](Instance.md)`
- **Tags:** Hidden, NotReplicated, Deprecated
- **Summary:** The object that is being targeted for localization by this table. Localization is applied to it and all of it's descendants.

### `LocalizationTable.SourceLocaleId`
- **Type:** `string`
- **Summary:** The locale of source strings.

## Methods
### `LocalizationTable:GetContents() -> string`
- **Tags:** Deprecated

### `LocalizationTable:GetEntries() -> Array`
- **Summary:** Returns an array of dictionaries, where each dictionary represents an entry of localization data.

### `LocalizationTable:GetString(targetLocaleId: string, key: string) -> string`
- **Tags:** Deprecated
- **Summary:** Returns a translation based on the specified language and key.

### `LocalizationTable:GetTranslator(localeId: string) -> [Instance](Instance.md)`
- **Summary:** Returns a `Class.Translator` for entries in this LocalizationTable, in the specified locale.

### `LocalizationTable:RemoveEntry(key: string, source: string, context: string) -> ()`
- **Summary:** Removes an entry from the LocalizationTable, using the specified `key`, `source`, and `context` to narrow down the specific entry to be removed.

### `LocalizationTable:RemoveEntryValue(key: string, source: string, context: string, localeId: string) -> ()`
- **Summary:** Removes a single language translation from the LocalizationTable, using the provided `key`, `source`, `context`, and `localeId` to narrow down the specific entry to be removed.

### `LocalizationTable:RemoveKey(key: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Deprecated in favor of `Class.LocalizationTable:RemoveEntry()`.

### `LocalizationTable:RemoveTargetLocale(localeId: string) -> ()`
- **Summary:** Removes all translations from the LocalizationTable with the specified localeId.

### `LocalizationTable:SetContents(contents: string) -> ()`
- **Tags:** Deprecated
- **Summary:** Sets the contents of the LocalizationTable, via the legacy JSON format.

### `LocalizationTable:SetEntries(entries: Variant) -> ()`
- **Summary:** Sets the contents of the LocalizationTable.

### `LocalizationTable:SetEntry(key: string, targetLocaleId: string, text: string) -> ()`
- **Tags:** Deprecated

### `LocalizationTable:SetEntryContext(key: string, source: string, context: string, newContext: string) -> ()`
- **Summary:** Sets the **Context** field of a LocalizationTable entry to `newContext`, using the specified `key`, `source`, and `context` to narrow down the entry that will have this change applied.

### `LocalizationTable:SetEntryExample(key: string, source: string, context: string, example: string) -> ()`
- **Summary:** Sets the **Example** field of a LocalizationTable entry to `example`, using the specified `key`, `source`, and `context` to narrow down the entry that will have this change applied.

### `LocalizationTable:SetEntryKey(key: string, source: string, context: string, newKey: string) -> ()`
- **Summary:** Sets the **Key** field of a LocalizationTable entry to `newKey`, using the specified `key`, `source`, and `context` to narrow down the entry that will have this change applied.

### `LocalizationTable:SetEntrySource(key: string, source: string, context: string, newSource: string) -> ()`
- **Summary:** Sets the **Source** field of a LocalizationTable entry to `newSource`, using the specified `key`, `source`, and `context` to narrow down the entry that will have this change applied.

### `LocalizationTable:SetEntryValue(key: string, source: string, context: string, localeId: string, text: string) -> ()`
- **Summary:** Sets the text of the specified localeId in a LocalizationTable entry, using the specified `key`, `source`, and `context` to narrow down the entry that will have this change applied.

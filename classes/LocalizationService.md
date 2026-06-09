# LocalizationService

**Superclass:** [Instance](Instance.md)

LocalizationService is a class responsible for handling automated translation, storing `Class.LocalizationTable` objects for core scripts, and returning a list of localized `Class.LocalizationTable` objects based on the player's location.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `LocalizationService.RobloxLocaleId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The locale ID used for localizing core and internal features.

### `LocalizationService.SystemLocaleId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The locale ID that the local player has set for their operating system.

## Methods
### `LocalizationService:GetCorescriptLocalizations() -> Instances`
- **Summary:** Returns a list of `Class.LocalizationTable` objects used for localizing core scripts.

### `LocalizationService:GetCountryRegionForPlayerAsync(player: [Instance](Instance.md)) -> string`
- **Tags:** Yields
- **Summary:** Returns country/region code string according to player's client IP geolocation.

### `LocalizationService:GetTableEntries(instance: [Instance](Instance.md)) -> Array`
- **Summary:** Gets all entries used for automated localization.

### `LocalizationService:GetTranslatorForLocaleAsync(locale: string) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Yields until the cloud `Class.LocalizationTable` for the argument locale has been loaded - if available. Returns a `Class.Translator` instance to be used for translations for the provided locale.

### `LocalizationService:GetTranslatorForPlayer(player: [Instance](Instance.md)) -> [Instance](Instance.md)`
- **Summary:** Returns a `Class.Translator` to be used for translations using the locale data loaded.

### `LocalizationService:GetTranslatorForPlayerAsync(player: [Instance](Instance.md)) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Yields until the cloud `Class.LocalizationTable` for the player's locale has been loaded - if available. Returns a `Class.Translator` instance to be used for translations for the provided locale.

# TextFilterTranslatedResult

**Superclass:** [Instance](Instance.md)

TextFilterTranslatedResult is a class representing the result of a TextFilter, which can be translated based on the source language.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `TextFilterTranslatedResult.SourceLanguage`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated

### `TextFilterTranslatedResult.SourceText`
- **Type:** `[TextFilterResult](TextFilterResult.md)`
- **Tags:** ReadOnly, NotReplicated

## Methods
### `TextFilterTranslatedResult:GetTranslationForLocale(locale: string) -> [TextFilterResult](TextFilterResult.md)`

### `TextFilterTranslatedResult:GetTranslations() -> Dictionary`

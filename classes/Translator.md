# Translator

**Superclass:** [Instance](Instance.md)

The Translator class is defined to manage the manufacturing of localized strings for the viewing player. It allows retrieving display-ready strings from a `Class.LocalizationTable` and supports inserting data replacements based on context.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `Translator.LocaleId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The locale of translated strings.

## Methods
### `Translator:FormatByKey(key: string, args: Variant) -> string`
- **Summary:** Returns the localized text string in a `Class.LocalizationTable` based on its `Class.Translator` locale, by key.

### `Translator:Translate(context: [Instance](Instance.md), text: string) -> string`
- **Summary:** Returns the localized text string in a `Class.LocalizationTable` based on its `Class.Translator` locale, by source lookup.

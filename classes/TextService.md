# TextService

**Superclass:** [Instance](Instance.md)

The `TextService` class manages the internal handling of text display, including filtering and translating strings. It provides methods for filtering and calculating bounds, and includes a note on deprecated functions.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `TextService:FilterAndTranslateStringAsync(stringToFilter: string, fromUserId: int64, targetLocales: Array, textContext: TextFilterContext) -> [TextFilterTranslatedResult](TextFilterTranslatedResult.md)`
- **Tags:** Yields
- **Summary:** Filters and translates a string.

### `TextService:FilterStringAsync(stringToFilter: string, fromUserId: int64, textContext: TextFilterContext) -> [TextFilterResult](TextFilterResult.md)`
- **Tags:** Yields
- **Summary:** Filters a string being received from a user and returns a `Class.TextFilterResult` which can be used to distribute the correctly filtered text accordingly.

### `TextService:GetFamilyInfoAsync(assetId: ContentId) -> Dictionary`
- **Tags:** Yields
- **Summary:** Returns a table containing the name and faces of a font family.

### `TextService:GetTextBoundsAsync(params: [GetTextBoundsParams](GetTextBoundsParams.md)) -> Vector2`
- **Tags:** Yields
- **Summary:** Computes the `Datatype.Vector2` dimensions (in pixels) that will be taken up with text when using a `Class.GetTextBoundsParams` object.

### `TextService:GetTextSize(string: string, fontSize: int, font: Enum.Font, frameSize: Vector2) -> Vector2`
- **Summary:** Computes the `Datatype.Vector2` dimensions (in pixels) that will be taken up with text when using the specified formatting parameters and size constraints.

### `TextService:GetTextSizeOffsetAsync(fontSize: int, font: Datatype.Font) -> float`
- **Tags:** Yields
- **Summary:** Returns the offset used to up-scale text based on the current `Class.GuiService.PreferredTextSize` setting.

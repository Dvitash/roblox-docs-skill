# StudioService

**Superclass:** [Instance](Instance.md)

This file defines `StudioService` as a class for managing Roblox Studio configuration and importing files, providing methods for accessing system settings and handling file import.

## Tags
- NotCreatable
- Service
- NotReplicated

## Properties
### `StudioService.ActiveScript`
- **Type:** `[Instance](Instance.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Reflects the `Class.LuaSourceContainer` currently being edited (if any).

### `StudioService.DraggerSolveConstraints`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `StudioService.DrawConstraintsOnTop`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated, Deprecated

### `StudioService.GridSize`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines the distance in studs by which Studio's drag and move tools move objects each tick.

### `StudioService.RotateIncrement`
- **Type:** `float`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Determines the degrees by which Studio's rotation tool will rotate selected objects each tick.

### `StudioService.Secrets`
- **Type:** `string`

### `StudioService.ShowConstraintDetails`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `StudioService.ShowWeldDetails`
- **Type:** `boolean`
- **Tags:** ReadOnly, NotReplicated

### `StudioService.StudioLocaleId`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The locale currently in-use by Studio, e.g. `en_US`.

### `StudioService.UseLocalSpace`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Determines whether Studio tools will use local space of an object or global space.

## Methods
### `StudioService:GetClassIcon(className: string) -> Dictionary`
- **Summary:** Provides a dictionary that allows the display of a class' Explorer window icon.

### `StudioService:GetUserId() -> int64`
- **Summary:** Returns the Studio user's userId if they're logged in, otherwise returns 0.

### `StudioService:PromptImportFile(fileTypeFilter: Array) -> [Instance](Instance.md)`
- **Tags:** Yields, Deprecated
- **Summary:** Prompts the current Studio user to select one file to add as a `Class.File`.

### `StudioService:PromptImportFileAsync(fileTypeFilter: Array) -> [Instance](Instance.md)`
- **Tags:** Yields
- **Summary:** Prompts the current Studio user to select one file to add as a `Class.File`.

### `StudioService:PromptImportFiles(fileTypeFilter: Array) -> Instances`
- **Tags:** Yields, Deprecated
- **Summary:** Prompts the current Studio user to select files to add as `Class.File|Files`.

### `StudioService:PromptImportFilesAsync(fileTypeFilter: Array) -> Instances`
- **Tags:** Yields
- **Summary:** Prompts the current Studio user to select files to add as `Class.File|Files`.

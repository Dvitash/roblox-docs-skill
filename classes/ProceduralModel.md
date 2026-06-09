# ProceduralModel

**Superclass:** [Model](Model.md)

Procedural models are procedural models that automatically generate their contents based on parameter changes. They inherit from `Class.Model` and support generation using a `generator module`.

## Properties
### `ProceduralModel.GenerationError`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** Stores errors that the generator module might encounter during generation.

### `ProceduralModel.Generator`
- **Type:** `[ModuleScript](ModuleScript.md)`
- **Summary:** A reference to a `Class.ModuleScript` that contains code which defines how the `ProceduralModel` generates its contents in response to parameter changes.

### `ProceduralModel.Size`
- **Type:** `Vector3`
- **Summary:** Defines the bounding volume used for generation.

## Methods
### `ProceduralModel:ForceGeneration() -> boolean`

### `ProceduralModel:WaitForGenerationAsync() -> boolean`
- **Tags:** Yields
- **Summary:** Waits for generation to complete after making parameter changes.

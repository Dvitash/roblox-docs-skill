# ReflectionMetadataItem

**Superclass:** [Instance](Instance.md)

This file defines `ReflectionMetadataItem` classes that represent abstract properties for generic information about classes, members, enumerations, and enum items. These classes inherit from `ReflectionClass` and `ReflectionEnum`.

## Tags
- NotCreatable

## Properties
### `ReflectionMetadataItem.Browsable`
- **Type:** `boolean`
- **Summary:** Whether or not this can be seen in studio.

### `ReflectionMetadataItem.ClassCategory`
- **Type:** `string`
- **Summary:** Describes the category of this class.

### `ReflectionMetadataItem.ClientOnly`
- **Type:** `boolean`

### `ReflectionMetadataItem.Constraint`
- **Type:** `string`
- **Summary:** Describes a constraint for a single-argument function whose argument type is a `Class.Object.ClassName`.

### `ReflectionMetadataItem.Deprecated`
- **Type:** `boolean`
- **Summary:** Whether or not this item is deprecated.

### `ReflectionMetadataItem.EditingDisabled`
- **Type:** `boolean`
- **Summary:** Toggles whether this property can be edited from the Properties window.

### `ReflectionMetadataItem.EditorType`
- **Type:** `string`

### `ReflectionMetadataItem.FFlag`
- **Type:** `string`

### `ReflectionMetadataItem.IsBackend`
- **Type:** `boolean`
- **Summary:** Vague value for showing if this depends on backend stuff.

### `ReflectionMetadataItem.PropertyOrder`
- **Type:** `int`

### `ReflectionMetadataItem.ScriptContext`
- **Type:** `string`
- **Summary:** Describes the context where this member can be used. If set to "Server", this member will not be available to auto fill when editing a `Class.LocalScript`. If set to "Client", this member will not be available to auto fill when editing a `Class.Script`.

### `ReflectionMetadataItem.ServerOnly`
- **Type:** `boolean`

### `ReflectionMetadataItem.SliderScaling`
- **Type:** `string`

### `ReflectionMetadataItem.UIMaximum`
- **Type:** `double`
- **Summary:** The maximum value of this property. Used with `Class.ReflectionMetadataItem.UIMinimum` to control the slider bar of this property in the `Properties` window.

### `ReflectionMetadataItem.UIMinimum`
- **Type:** `double`
- **Summary:** The minimum value of this property. Used with `Class.ReflectionMetadataItem.UIMaximum` to control the slider bar of this property in the `Properties` window.

### `ReflectionMetadataItem.UINumTicks`
- **Type:** `double`
- **Summary:** The number of potential values the property's slider bar can be set to, `Class.ReflectionMetadataItem.UIMinimum` and `Class.ReflectionMetadataItem.UIMaximum`.

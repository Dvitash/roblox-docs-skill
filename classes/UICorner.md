# UICorner

**Superclass:** [UIComponent](UIComponent.md)

UICorner is a UI modifier that applies deformation to the corners of a parent object, allowing descendants to be clipped. It calculates individual corner radii based on the `Datatype.UDim` properties, and can be used with slices for decorative borders.

## Properties
### `UICorner.BottomLeftRadius`
- **Type:** `UDim`
- **Summary:** Determines the radius of the bottom-left corner.

### `UICorner.BottomRightRadius`
- **Type:** `UDim`
- **Summary:** Determines the radius of the bottom-right corner.

### `UICorner.CornerRadius`
- **Type:** `UDim`
- **Tags:** NotReplicated
- **Summary:** Sets all four corner radii at once and reads from `Class.UICorner.TopLeftRadius|TopLeftRadius`.

### `UICorner.TopLeftRadius`
- **Type:** `UDim`
- **Summary:** Determines the radius of the top-left corner.

### `UICorner.TopRightRadius`
- **Type:** `UDim`
- **Summary:** Determines the radius of the top-right corner.

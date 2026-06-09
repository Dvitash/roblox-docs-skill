# PackageLink

**Superclass:** [Instance](Instance.md)

The `Class.PackageLink` class is used to link a `Class.DataModel` instance to a corresponding asset in the cloud, enhancing collaboration and version control.

## Tags
- NotCreatable
- NotBrowsable

## Properties
### `PackageLink.AutoUpdate`
- **Type:** `boolean`
- **Summary:** When this property is set to true, the package associated with the given `Class.PackageLink` automatically updates to the latest version.

### `PackageLink.Creator`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** The creator of the package asset.

### `PackageLink.DefaultName`
- **Type:** `string`

### `PackageLink.PackageAssetName`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** The asset name of the package.

### `PackageLink.PackageId`
- **Type:** `ContentId`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The ID of the asset this package corresponds to.

### `PackageLink.PermissionLevel`
- **Type:** `PackagePermission`
- **Tags:** ReadOnly, NotReplicated, NotScriptable
- **Summary:** The package permission for the current Studio user.

### `PackageLink.SerializedDefaultAttributes`
- **Type:** `BinaryString`

### `PackageLink.Status`
- **Type:** `string`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The status of the package.

### `PackageLink.VersionNumber`
- **Type:** `int64`
- **Tags:** NotReplicated
- **Summary:** Refers to a revision of a specific package.

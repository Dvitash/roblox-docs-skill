# MaterialService

**Superclass:** [Instance](Instance.md)

The MaterialService is a class responsible for managing `Class.MaterialVariant` instances, which are used to store and manage game materials. It provides methods for overriding built-in material names and handling legacy terrain materials.

## Tags
- NotCreatable
- Service

## Properties
### `MaterialService.AsphaltName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Asphalt.

### `MaterialService.BasaltName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Basalt.

### `MaterialService.BrickName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Brick.

### `MaterialService.CardboardName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.CarpetName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.CeramicTilesName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.ClayRoofTilesName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.CobblestoneName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Cobblestone.

### `MaterialService.ConcreteName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Concrete.

### `MaterialService.CorrodedMetalName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in CorrodedMetal.

### `MaterialService.CrackedLavaName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in CrackedLava.

### `MaterialService.DiamondPlateName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in DiamondPlate.

### `MaterialService.FabricName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Fabric.

### `MaterialService.FoilName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Foil.

### `MaterialService.GlacierName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Glacier.

### `MaterialService.GraniteName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Granite.

### `MaterialService.GrassName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Grass.

### `MaterialService.GroundName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Ground.

### `MaterialService.IceName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Ice.

### `MaterialService.LeafyGrassName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in LeafyGrass.

### `MaterialService.LeatherName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.LimestoneName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Limestone.

### `MaterialService.MarbleName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Marble.

### `MaterialService.MetalName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Metal.

### `MaterialService.MudName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Mud.

### `MaterialService.PavementName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Pavement.

### `MaterialService.PebbleName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Pebble.

### `MaterialService.PlasterName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.PlasticName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Plastic.

### `MaterialService.RockName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Rock.

### `MaterialService.RoofShinglesName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.RubberName`
- **Type:** `string`
- **Tags:** NotScriptable

### `MaterialService.SaltName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Salt.

### `MaterialService.SandName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Sand.

### `MaterialService.SandstoneName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Sandstone.

### `MaterialService.SlateName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Slate.

### `MaterialService.SmoothPlasticName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in SmoothPlastic.

### `MaterialService.SnowName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Snow.

### `MaterialService.Use2022Materials`
- **Type:** `boolean`
- **Tags:** NotReplicated
- **Summary:** Switch built-in material pack.

### `MaterialService.WoodName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in Wood.

### `MaterialService.WoodPlanksName`
- **Type:** `string`
- **Tags:** NotScriptable
- **Summary:** Specify `Class.MaterialVariant` name to override built-in WoodPlanks.

## Methods
### `MaterialService:GetBaseMaterialOverride(material: Material) -> string`
- **Summary:** Get the override `Class.MaterialVariant` name of specified Material type.

### `MaterialService:GetMaterialVariant(material: Material, name: string) -> [MaterialVariant](MaterialVariant.md)`
- **Summary:** Get the effective MaterialVariant reference given a name and Material.

### `MaterialService:SetBaseMaterialOverride(material: Material, name: string) -> ()`
- **Summary:** Set a `Class.MaterialVariant` name that overrides a built-in material.

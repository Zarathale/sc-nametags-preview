# ScaenaCraft — Name Tags Preview (v0.6)

This datapack adds a **preview** crafting recipe for **Name Tags** on **Minecraft Java 1.21.11 (Data Pack 94.1)**.

It also includes a simple test recipe so you can quickly confirm the pack is actually registering recipes.

## What this adds

### 1) Test recipe (sanity check)
- **1x Oak Planks** -> **64x Sticks**

### 2) Name Tag preview recipe
- **1x Paper** + **1x Iron Nugget** -> **1x Name Tag**

Layout (2x2 or crafting table):

```
[ N ]
[P  ]
```

## Install

1. Put the zip into:
   `world/datapacks/`
2. In-game or console:
   - `/reload`
   - `/datapack list`

## Verify it loaded

Try giving the recipes to yourself:

- `/minecraft:recipe give @p scaenacraft_preview:test_stick`
- `/minecraft:recipe give @p scaenacraft_preview:name_tag_preview`

If those work, open the recipe book and try crafting.

## Notes

- This is meant as a temporary "lean forward" preview. Remove the datapack once the official name tag recipe exists in vanilla.
- Namespace used: `scaenacraft_preview`

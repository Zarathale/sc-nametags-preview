# ScaenaCraft Name Tags Preview (Datapack)

Test pack for **Minecraft Java 1.21.11** that adds a craftable Name Tag recipe.

## Included recipes

### Sanity check: 64 sticks
- **Input:** 1x Oak Planks
- **Output:** 64x Sticks
- Recipe ID: `scaenacraft_preview:test_stick`

### Name Tag
- **Input:** 1x Paper + 1x Iron Nugget
- **Pattern (2x2 or 3x3):**

```
 N
P
```

- Recipe ID: `scaenacraft_preview:name_tag_preview`

## Install
1. Put the zip in: `world/datapacks/`
2. Run `/reload` or restart.
3. Verify: `/datapack list`

## Troubleshooting
If `/minecraft:recipe give @p scaenacraft_preview:test_stick` says **Unknown recipe**, the pack’s files are not being loaded (wrong folder, wrong world, or pack metadata rejected).

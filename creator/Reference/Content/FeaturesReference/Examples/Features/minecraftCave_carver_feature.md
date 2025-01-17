---
author: JimSeaman42
ms.author: mikeam
title: Features Documentation - minecraft:cave_carver_feature
ms.service: minecraft-bedrock-edition
---

# Features Documentation - minecraft:cave_carver_feature

`minecraft:cave_carver_feature` carves a cave through the world in the current chunk, and in every chunk around the current chunk in an 8 radial pattern. This feature only works when placed in the pass "pregeneration_pass".

## Example

### Carve caves normally

```json
{
"format_version": "1.16.100",
  "minecraft:cave_feature": {
    "description": {
      "identifier": "minecraft:underground_cave_carver_feature"
    },
    "fill_with": "minecraft:air",
    "width_modifier": 0.0,
  "skip_carve_chance": 15
  }
}
```

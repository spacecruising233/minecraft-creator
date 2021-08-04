---
author: v-josjones
ms.author: v-josjones
title: Furnace Recipe
ms.prod: gaming
---

# Furnace Recipe

Represents a furnace recipe for a furnace. `Input` items will burn and transform into items specified in `output`.

## Parameters

|Name| Type| Description |
|:-----------|:-----------|:-----------|
|input| item names| Items used as input for the furnace recipe. |
|output| item names| Items used as output for the furnace recipe. |
|tags |String array| Item used as input for the furnace recipe. |

## Furnace Recipe Example

```json
{
"format_version": "1.17",
"minecraft:recipe_furnace": {
    "description": {
        "identifier": "minecraft:furnace_beef"
        },
    "tags": ["furnace", "smoker", "campfire", "soul_campfire"],
    "input": {
        "item": "minecraft:beef",
        "data": 0,
        "count": 4
        },
    "output ": "minecraft:cooked_beef"
    }
}
```

## Vanilla Example

:::code language="json" source="../../../../Source/VanillaBehaviorPack/recipes/furnace_cobblestone.json":::
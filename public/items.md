---
title: Item Database API
layout: page
categories: ["API"]
---

## Item Database API
The item database API acts like the `Item Guide` on `http://wynncraft.com` and allows a search of current items in our database. 

### Valid Parameters
* `command` - The search query, this can be: a level, a quality, a item type or an item name. 

### Example Request
`http://api.wynncraft.com/public_api.php?action=items&command=75`

### Example Response
```json
[
    {
        "item_name": "Bob's Mythic Bow",
        "item_type": "Legendary",
        "item_mineraft": "Bow",
        "item_min_lvl": "75",
        "identification": {
            "health_regen": "1.5",
            "mana_regen": "1",
            "spell_dam": "30%",
            "life_steal": "0.4",
            "mana_steal": "1",
            "xp_bonus": "20%",
            "loot_bonus": "20%"
        },
        "min_dam": "566",
        "max_dam": "463"
    },
    {
        "item_name": "Bob's Mythic Daggers",
        "item_type": "Legendary",
        "item_mineraft": "Shears",
        "item_min_lvl": "75",
        "identification": {
            "health_regen": "1.5",
            "mana_regen": "1",
            "spell_dam": "30%",
            "life_steal": "0.4",
            "mana_steal": "1",
            "xp_bonus": "20%",
            "loot_bonus": "20%"
        },
        "min_dam": "420",
        "max_dam": "389"
    },
    {
        "item_name": "Bob's Mythic Spear",
        "item_type": "Legendary",
        "item_mineraft": "Shovel",
        "item_min_lvl": "75",
        "identification": {
            "health_regen": "1.5",
            "mana_regen": "1",
            "spell_dam": "30%",
            "life_steal": "0.4",
            "mana_steal": "1",
            "xp_bonus": "20%",
            "loot_bonus": "20%"
        },
        "min_dam": "368",
        "max_dam": "311"
    },
    {
        "item_name": "Bob's Mythic Wand",
        "item_type": "Legendary",
        "item_mineraft": "Stick",
        "item_min_lvl": "75",
        "identification": {
            "health_regen": "1.5",
            "mana_regen": "1",
            "spell_dam": "30%",
            "life_steal": "0.4",
            "mana_steal": "1",
            "xp_bonus": "20%",
            "loot_bonus": "20%"
        },
        "min_dam": "278",
        "max_dam": "204"
    }
]
```
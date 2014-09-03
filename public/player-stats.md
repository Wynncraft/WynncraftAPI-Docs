---
title: Player Stats API
layout: page
categories: ["API"]
---

## Player Stats API
The player stats API returns publically available data about a player.

### Valid Parameters
* `command` - The player name

### Example Request
`http://api.wynncraft.com/public_api.php?action=playerStats&command=Acer78`

### Example Response
```json
{
    "username": "Acer78",
    "rank": "Moderator",
    "since_last_login": "0 year(s) 0 month(s) 0 day(s)",
    "playtime": "308.75",
    "first_join": "2013-05-02 19:56:05",
    "last_join": "2014-09-03 15:33:27",
    "current_server": "GM1",
    "global": {
        "items_identified": 966,
        "mobs_killed": 235392,
        "pvp_kills": 2188,
        "pvp_deaths": 1750,
        "chests_found": 1592,
        "blocks_walked": 1162612,
        "logins": 6271,
        "deaths": 397,
        "total_level": 521
    },
    "classes": {
        "archer": {
            "items_identified": 115,
            "mobs_killed": 80894,
            "pvp_kills": 88,
            "pvp_deaths": 140,
            "chests_found": 348,
            "blocks_walked": 325988,
            "logins": 1150,
            "deaths": 117,
            "level": 75
        },
        "assassin": {
            "items_identified": 184,
            "mobs_killed": 74284,
            "pvp_kills": 148,
            "pvp_deaths": 107,
            "chests_found": 237,
            "blocks_walked": 232761,
            "logins": 1148,
            "deaths": 45,
            "level": 75
        },
        "mage": {
            "items_identified": 224,
            "mobs_killed": 24418,
            "pvp_kills": 1289,
            "pvp_deaths": 970,
            "chests_found": 135,
            "blocks_walked": 53564,
            "logins": 1330,
            "deaths": 41,
            "level": 75
        },
        "warrior": {
            "items_identified": 204,
            "mobs_killed": 25344,
            "pvp_kills": 657,
            "pvp_deaths": 528,
            "chests_found": 643,
            "blocks_walked": 549409,
            "logins": 1697,
            "deaths": 89,
            "level": 75
        },
        "darkwizard": {
            "items_identified": 65,
            "mobs_killed": 8296,
            "pvp_kills": 0,
            "pvp_deaths": 0,
            "chests_found": 62,
            "blocks_walked": 209,
            "logins": 236,
            "deaths": 20,
            "level": 56
        },
        "hunter": {
            "items_identified": 52,
            "mobs_killed": 6299,
            "pvp_kills": 6,
            "pvp_deaths": 3,
            "chests_found": 46,
            "blocks_walked": 233,
            "logins": 246,
            "deaths": 32,
            "level": 54
        },
        "knight": {
            "items_identified": 87,
            "mobs_killed": 9261,
            "pvp_kills": 0,
            "pvp_deaths": 0,
            "chests_found": 66,
            "blocks_walked": 228,
            "logins": 219,
            "deaths": 15,
            "level": 57
        },
        "ninja": {
            "items_identified": 35,
            "mobs_killed": 6596,
            "pvp_kills": 0,
            "pvp_deaths": 2,
            "chests_found": 55,
            "blocks_walked": 220,
            "logins": 245,
            "deaths": 38,
            "level": 54
        }
    },
    "request": {
        "timestamp": 1409774640,
        "ip": "127.0.0.1"
    }
}
```

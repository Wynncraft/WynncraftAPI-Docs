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
`http://api.wynncraft.com/public_api.php?action=playerStats&command=Tama63`

### Example Response
```json
{
    "username": "Tama63",
    "rank": "Administrator",
    "since_last_login": "0 month(s) 9 day(s)",
    "playtime": "11.52",
    "first_join": "2013-10-12 18:07:56",
    "last_join": "2014-05-26 14:22:56",
    "current_server": "null",
    "items_identified": 22,
    "mobs_killed": 1092,
    "emeralds_collected": 0,
    "pvp_kills": 1,
    "chests_found": 68,
    "blocks_walked": 45991,
    "logins": 146,
    "deaths": 8,
    "warrior_level": 75,
    "mage_level": 1,
    "archer_level": 1,
    "assassin_level": 25,
    "total_level": 102,
    "request": {
        "timestamp": 1401914766,
        "ip": "127.0.0.1"
    }
}
```

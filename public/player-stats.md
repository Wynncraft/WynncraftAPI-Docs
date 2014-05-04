---
title: Player Stats API
layout: page
categories: ["API"]
---

## Player Stats API
The player stats API returns publically available data about a player.

### Example Request
`http://api.wynncraft.com/public_api.php?action=playerStats&command=Tama63`

### Example Response
```json
{
    "rank": "Administrator",
    "since_last_login": "0 month(s) 7 day(s)",
    "playtime": "11.50",
    "first_join": "2013-10-12 18:07:56",
    "last_join": "2014-04-27 04:40:45",
    "current_server": "null",
    "items_identified": 22,
    "mobs_killed": 1086,
    "emeralds_collected": 0,
    "pvp_kills": 1,
    "chests_found": 68,
    "blocks_walked": 45990,
    "logins": 142,
    "deaths": 8,
    "warrior_level": 75,
    "mage_level": 1,
    "archer_level": 1,
    "assassin_level": 25,
    "total_level": 102
}
```
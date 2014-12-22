---
title: Guild Stats API
layout: page
categories: ["API"]
---

## Guild Stats API
The guild stats API returns publically available data about a guild.

### Valid Parameters
* `command` - The guild name

### Example Request
`http://api.wynncraft.com/public_api.php?action=guildStats&command=NwLunarRepublic`

### Example Response
```json
{
    "owner": "alfiearmadillo",
    "tag": "NLR",
    "member_count": 9,
    "member_cap": 37,
    "level": 37,
    "exp": null,
    "stats": {
        "pvp_kills": 1207,
        "pvp_deaths": 448,
        "mobs_killed": 60218,
        "items_identified": 1046,
        "deaths": 205,
        "avg_total_level": 24
    },
    "members": {
        "alfiearmadillo": {
            "name": "alfiearmadillo",
            "rank": "OWNER",
            "contributed": 1268287,
            "joined": {
                "sec": 1419216278,
                "usec": 67000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "kolleden12346": {
            "name": "kolleden12346",
            "rank": "CHIEF",
            "contributed": 686930,
            "joined": {
                "sec": 1419242834,
                "usec": 798000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "gay1324": {
            "name": "gay1324",
            "rank": "CAPTAIN",
            "contributed": 3435,
            "joined": {
                "sec": 1419244978,
                "usec": 728000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "LukeW2464": {
            "name": "LukeW2464",
            "rank": "CHIEF",
            "contributed": 203378,
            "joined": {
                "sec": 1419260553,
                "usec": 860000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "H4vyC0ldpl4y": {
            "name": "H4vyC0ldpl4y",
            "rank": "RECRUIT",
            "contributed": 60451,
            "joined": {
                "sec": 1419268768,
                "usec": 560000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "BETA2"
        },
        "ToxicDemon_": {
            "name": "ToxicDemon_",
            "rank": "RECRUIT",
            "contributed": 64027,
            "joined": {
                "sec": 1419270176,
                "usec": 789000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "LocusAzzurro": {
            "name": "LocusAzzurro",
            "rank": "RECRUIT",
            "contributed": 98139,
            "joined": {
                "sec": 1419272740,
                "usec": 812000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "null"
        },
        "PhoenixoftheSky": {
            "name": "PhoenixoftheSky",
            "rank": "RECRUIT",
            "contributed": 554151,
            "joined": {
                "sec": 1419273713,
                "usec": 926000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "BETA2"
        },
        "The_Best_4ever": {
            "name": "The_Best_4ever",
            "rank": "CHIEF",
            "contributed": 2817636,
            "joined": {
                "sec": 1419274040,
                "usec": 951000
            },
            "date_joined": "1969-12-31 19:00:00",
            "currentServer": "WC9"
        }
    },
    "request": {
        "timestamp": 1419291360,
        "ip": "127.0.0.1"
    }
}
```

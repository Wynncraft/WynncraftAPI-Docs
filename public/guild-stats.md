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
`https://api.wynncraft.com/public_api.php?action=guildStats&command=NwLunarRepublic`

### Example Response
```json
{
    "owner": "alfiearmadillo",
    "tag": "NLR",
    "member_count": 37,
    "member_cap": 41,
    "level": 37,
    "exp": null,
    "stats": {
        "pvp_kills": 10492,
        "pvp_deaths": 6352,
        "mobs_killed": 2408983,
        "items_identified": 8522,
        "deaths": 5614,
        "avg_total_level": 67
    },
    "members": {
        "alfiearmadillo": {
            "name": "alfiearmadillo",
            "rank": "OWNER",
            "contributed": 1287704,
            "date_joined": "2014-12-21 21:44:38",
            "currentServer": "WC1"
        },
        "kolleden12346": {
            "name": "kolleden12346",
            "rank": "CHIEF",
            "contributed": 697632,
            "date_joined": "2014-12-22 05:07:14",
            "currentServer": "null"
        },
        "gay1324": {
            "name": "gay1324",
            "rank": "CAPTAIN",
            "contributed": 3435,
            "date_joined": "2014-12-22 05:42:58",
            "currentServer": "null"
        },
        "LukeW2464": {
            "name": "LukeW2464",
            "rank": "CHIEF",
            "contributed": 210383,
            "date_joined": "2014-12-22 10:02:33",
            "currentServer": "null"
        },
        "H4vyC0ldpl4y": {
            "name": "H4vyC0ldpl4y",
            "rank": "CAPTAIN",
            "contributed": 118083,
            "date_joined": "2014-12-22 12:19:28",
            "currentServer": "WC10"
        },
        "ToxicDemon_": {
            "name": "ToxicDemon_",
            "rank": "RECRUIT",
            "contributed": 64027,
            "date_joined": "2014-12-22 12:42:56",
            "currentServer": "null"
        },
        "LocusAzzurro": {
            "name": "LocusAzzurro",
            "rank": "RECRUIT",
            "contributed": 98409,
            "date_joined": "2014-12-22 13:25:40",
            "currentServer": "WC5"
        },
        "PhoenixoftheSky": {
            "name": "PhoenixoftheSky",
            "rank": "RECRUITER",
            "contributed": 1096907,
            "date_joined": "2014-12-22 13:41:53",
            "currentServer": "WC1"
        },
        "The_Best_4ever": {
            "name": "The_Best_4ever",
            "rank": "CHIEF",
            "contributed": 3012055,
            "date_joined": "2014-12-22 13:47:20",
            "currentServer": "WC1"
        },
        "CyberPixelZ": {
            "name": "CyberPixelZ",
            "rank": "RECRUITER",
            "contributed": 407768,
            "date_joined": "2014-12-22 20:29:09",
            "currentServer": "null"
        },
        "b9baconator": {
            "name": "b9baconator",
            "rank": "RECRUIT",
            "contributed": 119858,
            "date_joined": "2014-12-22 22:33:26",
            "currentServer": "null"
        },
        "Swuggles": {
            "name": "Swuggles",
            "rank": "RECRUIT",
            "contributed": 2759,
            "date_joined": "2014-12-23 01:35:58",
            "currentServer": "null"
        },
        "badrock_2000": {
            "name": "badrock_2000",
            "rank": "RECRUIT",
            "contributed": 3830,
            "date_joined": "2014-12-23 03:31:10",
            "currentServer": "null"
        },
        "TheDollarBill": {
            "name": "TheDollarBill",
            "rank": "RECRUIT",
            "contributed": 339,
            "date_joined": "2014-12-23 03:36:01",
            "currentServer": "null"
        },
        "greenpinguin153": {
            "name": "greenpinguin153",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 03:40:12",
            "currentServer": "null"
        },
        "MarioMan9613": {
            "name": "MarioMan9613",
            "rank": "CAPTAIN",
            "contributed": 29706,
            "date_joined": "2014-12-23 03:40:30",
            "currentServer": "null"
        },
        "Lalala_hey": {
            "name": "Lalala_hey",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 03:50:38",
            "currentServer": "null"
        },
        "Zsozso2": {
            "name": "Zsozso2",
            "rank": "RECRUITER",
            "contributed": 17327,
            "date_joined": "2014-12-23 05:01:36",
            "currentServer": "null"
        },
        "jor27": {
            "name": "jor27",
            "rank": "RECRUITER",
            "contributed": 994,
            "date_joined": "2014-12-23 06:16:27",
            "currentServer": "null"
        },
        "blackbird64": {
            "name": "blackbird64",
            "rank": "RECRUIT",
            "contributed": 240,
            "date_joined": "2014-12-23 06:31:00",
            "currentServer": "null"
        },
        "cornecorne22": {
            "name": "cornecorne22",
            "rank": "RECRUIT",
            "contributed": 39,
            "date_joined": "2014-12-23 06:53:57",
            "currentServer": "null"
        },
        "thebest263": {
            "name": "thebest263",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 06:44:48",
            "currentServer": "null"
        },
        "kevinbittner123": {
            "name": "kevinbittner123",
            "rank": "RECRUIT",
            "contributed": 784,
            "date_joined": "2014-12-23 07:24:17",
            "currentServer": "null"
        },
        "BlockHeader00": {
            "name": "BlockHeader00",
            "rank": "RECRUIT",
            "contributed": 8450,
            "date_joined": "2014-12-23 07:53:11",
            "currentServer": "null"
        },
        "Jbip": {
            "name": "Jbip",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 08:29:39",
            "currentServer": "WC9"
        },
        "DamageDude63": {
            "name": "DamageDude63",
            "rank": "RECRUIT",
            "contributed": 1023,
            "date_joined": "2014-12-23 08:57:47",
            "currentServer": "WC1"
        },
        "tyrell113": {
            "name": "tyrell113",
            "rank": "RECRUIT",
            "contributed": 3732,
            "date_joined": "2014-12-23 09:43:00",
            "currentServer": "null"
        },
        "xXJetstreamXx": {
            "name": "xXJetstreamXx",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 09:48:55",
            "currentServer": "null"
        },
        "Minecr4ftDude": {
            "name": "Minecr4ftDude",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 09:48:12",
            "currentServer": "WC2"
        },
        "TheKillerKing21": {
            "name": "TheKillerKing21",
            "rank": "RECRUIT",
            "contributed": 362,
            "date_joined": "2014-12-23 10:09:50",
            "currentServer": "WC2"
        },
        "tatanyom": {
            "name": "tatanyom",
            "rank": "RECRUIT",
            "contributed": 100,
            "date_joined": "2014-12-23 10:10:02",
            "currentServer": "null"
        },
        "JoNaS1245": {
            "name": "JoNaS1245",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 10:20:38",
            "currentServer": "null"
        },
        "yojan999": {
            "name": "yojan999",
            "rank": "RECRUIT",
            "contributed": 0,
            "date_joined": "2014-12-23 10:24:01",
            "currentServer": "null"
        },
        "Dutch_Gh0st": {
            "name": "Dutch_Gh0st",
            "rank": "RECRUIT",
            "contributed": 983,
            "date_joined": "2014-12-23 10:29:58",
            "currentServer": "null"
        },
        "Shootboy545": {
            "name": "Shootboy545",
            "rank": "RECRUIT",
            "contributed": 39,
            "date_joined": "2014-12-23 10:21:54",
            "currentServer": "WC7"
        },
        "FighterZ_": {
            "name": "FighterZ_",
            "rank": "RECRUIT",
            "contributed": 12636,
            "date_joined": "2014-12-23 10:30:38",
            "currentServer": "null"
        },
        "Daniel240400": {
            "name": "Daniel240400",
            "rank": "RECRUIT",
            "contributed": 152,
            "date_joined": "2014-12-23 10:38:20",
            "currentServer": "WC2"
        }
    },
    "request": {
        "timestamp": 1419291360,
        "ip": "127.0.0.1"
    }
}
```

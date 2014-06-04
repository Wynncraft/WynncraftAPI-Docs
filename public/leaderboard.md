---
title: PVP Leaderboard API
layout: page
categories: ["API"]
---

## PVP Leaderboard API
The PvP leaderboard API returns the raw data used on the `http://wynncraft.com` Nether leaderboard. The response returns in order of PvP kills.

#### Response Notice
The response returns a duplicate keys for internal use.

### Valid Parameters
* `command` - The group to fetch from can be: `daily`, `weekly` or `all`.
* `limit` - The limit to fetch from (max 100)

### Example Request
`http://api.wynncraft.com/public_api.php?action=pvpLeaderboard&command=all&limit=12`

### Example Response
```json
{
    "0": {
        "0": "Yzzero",
        "1": "Archer",
        "2": "75",
        "3": "13940",
        "4": "7450",
        "username": "Yzzero",
        "class": "Archer",
        "level": "75",
        "kills": "13940",
        "deaths": "7450"
    },
    "1": {
        "0": "Francis12qwasyx",
        "1": "Archer",
        "2": "75",
        "3": "10276",
        "4": "6280",
        "username": "Francis12qwasyx",
        "class": "Archer",
        "level": "75",
        "kills": "10276",
        "deaths": "6280"
    },
    "2": {
        "0": "CreepersAmongUs",
        "1": "Assassin",
        "2": "75",
        "3": "8143",
        "4": "5234",
        "username": "CreepersAmongUs",
        "class": "Assassin",
        "level": "75",
        "kills": "8143",
        "deaths": "5234"
    },
    "3": {
        "0": "youngmonster5",
        "1": "Archer",
        "2": "75",
        "3": "8080",
        "4": "4991",
        "username": "youngmonster5",
        "class": "Archer",
        "level": "75",
        "kills": "8080",
        "deaths": "4991"
    },
    "4": {
        "0": "GhostArcherFTW",
        "1": "Archer",
        "2": "75",
        "3": "7518",
        "4": "5713",
        "username": "GhostArcherFTW",
        "class": "Archer",
        "level": "75",
        "kills": "7518",
        "deaths": "5713"
    },
    "5": {
        "0": "OneOfThoseDays",
        "1": "Mage",
        "2": "75",
        "3": "6402",
        "4": "2999",
        "username": "OneOfThoseDays",
        "class": "Mage",
        "level": "75",
        "kills": "6402",
        "deaths": "2999"
    },
    "6": {
        "0": "trainkid64",
        "1": "Assassin",
        "2": "75",
        "3": "6390",
        "4": "3118",
        "username": "trainkid64",
        "class": "Assassin",
        "level": "75",
        "kills": "6390",
        "deaths": "3118"
    },
    "7": {
        "0": "goodvibrations1",
        "1": "Archer",
        "2": "75",
        "3": "5957",
        "4": "4754",
        "username": "goodvibrations1",
        "class": "Archer",
        "level": "75",
        "kills": "5957",
        "deaths": "4754"
    },
    "8": {
        "0": "jacobjames02",
        "1": "Archer",
        "2": "72",
        "3": "5409",
        "4": "4873",
        "username": "jacobjames02",
        "class": "Archer",
        "level": "72",
        "kills": "5409",
        "deaths": "4873"
    },
    "9": {
        "0": "Croix464",
        "1": "Archer",
        "2": "75",
        "3": "5382",
        "4": "5084",
        "username": "Croix464",
        "class": "Archer",
        "level": "75",
        "kills": "5382",
        "deaths": "5084"
    },
    "10": {
        "0": "LeonardDathMaul",
        "1": "Mage",
        "2": "75",
        "3": "5249",
        "4": "2448",
        "username": "LeonardDathMaul",
        "class": "Mage",
        "level": "75",
        "kills": "5249",
        "deaths": "2448"
    },
    "11": {
        "0": "TheBeastNL",
        "1": "Archer",
        "2": "75",
        "3": "5203",
        "4": "3995",
        "username": "TheBeastNL",
        "class": "Archer",
        "level": "75",
        "kills": "5203",
        "deaths": "3995"
    },
    "request": {
        "timestamp": 1401914878,
        "ip": "127.0.0.1"
    }
}
```

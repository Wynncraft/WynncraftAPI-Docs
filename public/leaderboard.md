---
title: PVP Leaderboard API
layout: page
categories: ["API"]
---

## PVP Leaderboard API
The PvP leaderboard API returns the raw data used on the `http://wynncraft.com` Nether leaderboard. The response returns in order of PvP kills.

### Valid Parameters
* `command` - The group to fetch from can be: `daily`, `weekly` or `all`.
* `limit` - The limit to fetch from (max 100)

### Example Request
`http://api.wynncraft.com/public_api.php?action=pvpLeaderboard&command=all&limit=12`

### Example Response
```json
[
    {
        "0": "Yzzero",
        "1": "Archer",
        "2": "75",
        "3": "10627",
        "4": "5942",
        "username": "Yzzero",
        "class": "Archer",
        "level": "75",
        "kills": "10627",
        "deaths": "5942"
    },
    {
        "0": "GhostArcherFTW",
        "1": "Archer",
        "2": "75",
        "3": "6674",
        "4": "5273",
        "username": "GhostArcherFTW",
        "class": "Archer",
        "level": "75",
        "kills": "6674",
        "deaths": "5273"
    },
    {
        "0": "OneOfThoseDays",
        "1": "Mage",
        "2": "75",
        "3": "6360",
        "4": "2989",
        "username": "OneOfThoseDays",
        "class": "Mage",
        "level": "75",
        "kills": "6360",
        "deaths": "2989"
    },
    {
        "0": "CreepersAmongUs",
        "1": "Assassin",
        "2": "75",
        "3": "6329",
        "4": "4087",
        "username": "CreepersAmongUs",
        "class": "Assassin",
        "level": "75",
        "kills": "6329",
        "deaths": "4087"
    },
    {
        "0": "jacobjames02",
        "1": "Archer",
        "2": "72",
        "3": "5355",
        "4": "4811",
        "username": "jacobjames02",
        "class": "Archer",
        "level": "72",
        "kills": "5355",
        "deaths": "4811"
    },
    {
        "0": "LeonardDathMaul",
        "1": "Mage",
        "2": "75",
        "3": "5222",
        "4": "2430",
        "username": "LeonardDathMaul",
        "class": "Mage",
        "level": "75",
        "kills": "5222",
        "deaths": "2430"
    },
    {
        "0": "Francis12qwasyx",
        "1": "Archer",
        "2": "75",
        "3": "4894",
        "4": "3357",
        "username": "Francis12qwasyx",
        "class": "Archer",
        "level": "75",
        "kills": "4894",
        "deaths": "3357"
    },
    {
        "0": "Croix464",
        "1": "Archer",
        "2": "75",
        "3": "4615",
        "4": "4470",
        "username": "Croix464",
        "class": "Archer",
        "level": "75",
        "kills": "4615",
        "deaths": "4470"
    },
    {
        "0": "trainkid64",
        "1": "Assassin",
        "2": "75",
        "3": "4354",
        "4": "2243",
        "username": "trainkid64",
        "class": "Assassin",
        "level": "75",
        "kills": "4354",
        "deaths": "2243"
    },
    {
        "0": "youngmonster5",
        "1": "Archer",
        "2": "75",
        "3": "4333",
        "4": "2818",
        "username": "youngmonster5",
        "class": "Archer",
        "level": "75",
        "kills": "4333",
        "deaths": "2818"
    },
    {
        "0": "goodvibrations1",
        "1": "Archer",
        "2": "75",
        "3": "4327",
        "4": "3525",
        "username": "goodvibrations1",
        "class": "Archer",
        "level": "75",
        "kills": "4327",
        "deaths": "3525"
    },
    {
        "0": "Compmaster",
        "1": "Warrior",
        "2": "75",
        "3": "4027",
        "4": "3372",
        "username": "Compmaster",
        "class": "Warrior",
        "level": "75",
        "kills": "4027",
        "deaths": "3372"
    }
]
```
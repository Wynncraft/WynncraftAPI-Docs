---
title: WF Leaderboard API
layout: page
categories: ["API"]
---

## WF Leaderboard API
The PvP leaderboard API returns the raw data used on the `http://wynncraft.com` Nether leaderboard. The response returns in order of PvP kills.

#### Response Notice
The response returns a duplicate keys for internal use.

### Valid Parameters
* `command` - The group to fetch from can be: `daily`, `weekly` or `all`.
* `limit` - The limit to fetch from (max 100)

### Example Request
`http://api.wynncraft.com/public_api.php?action=wfLeaderboard&command=all&limit=12`

### Example Response
```json
{
    "0": {
        "username": "chownick",
        "0": "chownick",
        "kills": "4000",
        "1": "4000",
        "deaths": "1380",
        "2": "1380"
    },
    "1": {
        "username": "chownick",
        "0": "chownick",
        "kills": "4000",
        "1": "4000",
        "deaths": "1380",
        "2": "1380"
    },
    "2": {
        "username": "chownick",
        "0": "chownick",
        "kills": "3947",
        "1": "3947",
        "deaths": "1364",
        "2": "1364"
    },
    "3": {
        "username": "chownick",
        "0": "chownick",
        "kills": "3947",
        "1": "3947",
        "deaths": "1364",
        "2": "1364"
    },
    "4": {
        "username": "Pandi1919",
        "0": "Pandi1919",
        "kills": "2429",
        "1": "2429",
        "deaths": "1043",
        "2": "1043"
    },
    "5": {
        "username": "Pandi1919",
        "0": "Pandi1919",
        "kills": "2429",
        "1": "2429",
        "deaths": "1043",
        "2": "1043"
    },
    "6": {
        "username": "Pandi1919",
        "0": "Pandi1919",
        "kills": "2429",
        "1": "2429",
        "deaths": "1043",
        "2": "1043"
    },
    "7": {
        "username": "Pandi1919",
        "0": "Pandi1919",
        "kills": "2429",
        "1": "2429",
        "deaths": "1043",
        "2": "1043"
    },
    "8": {
        "username": "Troopermark1",
        "0": "Troopermark1",
        "kills": "1775",
        "1": "1775",
        "deaths": "559",
        "2": "559"
    },
    "9": {
        "username": "Troopermark1",
        "0": "Troopermark1",
        "kills": "1761",
        "1": "1761",
        "deaths": "558",
        "2": "558"
    },
    "10": {
        "username": "Troopermark1",
        "0": "Troopermark1",
        "kills": "1582",
        "1": "1582",
        "deaths": "532",
        "2": "532"
    },
    "11": {
        "username": "Troopermark1",
        "0": "Troopermark1",
        "kills": "1582",
        "1": "1582",
        "deaths": "532",
        "2": "532"
    },
    "request": {
        "timestamp": 1419291226,
        "ip": "127.0.0.1"
    }
}
```

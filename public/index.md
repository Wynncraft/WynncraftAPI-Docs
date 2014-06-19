---
title: API Overview
layout: page
categories: ["API"]
---

## API Overview

Wynncraft has a simple API that allows external developers to access the same data that we interface with locally.

## Making a Call to the API
Requests to the public api can be made by sending a `GET` request to `http://api.wynncraft.com/public_api.php`. The response will always be in the form of a json document, regardless of query parameters.

### Possible Parameters

Parameter     | Description
---           | ---
`action`      | What action to perform
`command`     | Some actions require an extra command
`limit`       | Some grouped data queries let you define a limit for the response

### Throttling by Cloudflare
If you spam requests to the API you will be automatically blacklisted from querying the API, you may contact `chris@wynncraft.com` to request whitelisting for unlimited calls to the API.

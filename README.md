# LegoProxy
A multipurpose Roblox Proxy for proxying Roblox API and Webhook Requests.

# Features
- list of features, doing it tomorrow.

# LegoProxy Usage
Here's a quick breakdown on how to use LegoProxy.

### Proxying Roblox API Requests
METHODS: `GET`, `POST`

```
https://domain.com/users.roblox.com/v1/users/1
```

### Proxying Webhook Requests
METHODS: `POST`

```
https://domain.com/webhook
```

JSON DATA:
```json
{
    "webhook": "",
    "data": {
        "abcd": "1234"
    }
}
```

### NOTE
My LegoProxy Server is only for small Roblox Games and Applications that doesnt request too much data through the Proxy as it has a 128 Requests Limit in a 5 minute window. You can implement a function where it prevents that limit or Self-Host LegoProxy by yourself.

# LegoProxy Relay Client
The LegoProxy Relay Client is currently not available to the public at this moment as it's still being tested and improved. Once it's good enough to make it public, a link to another repository will be added to this section of the README for you to self-host.

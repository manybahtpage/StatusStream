# Get your Discord status, presence, and activities through the Web API

When you have a server that's essentially a dedicated server lying around idle and doing nothing, why not utilize it for this purpose?

- 😂 Yes, it's like using Lanyard. It's a great project, so please go check it out.
- ☁️ API cached by Cloudflare Edge (1 minute)
- ⚡ Powered by Bun.js and Elysia.js
- ⬆️ Your Discord status will be updated every time your request does not hit the cache.
- 📨 The information we get from Discord, we just pass through it just like that.
- 😲 IT JUST WORKS!

## How to

1. Join this Discord server [StatusStream](https://discord.gg/Bu4rkbaE9f)
2. Get your discord status by using this link : https://statusstream.many.win/users/your-discord-id
For example: https://statusstream.many.win/users/311364847826763776

Cannot be more simple than this

Example output from API:
```json
{
    "statusstream": {
        "user": {
            "id": "311364847826763776",
            "bot": false,
            "system": false,
            "flags": 4326016,
            "username": "justluvi",
            "globalName": "Luvi",
            "discriminator": "0",
            "avatar": "c177a8b24cc362d2128a1347556183f3",
            "avatarDecoration": null,
            "createdTimestamp": 1494305564601,
            "defaultAvatarURL": "https://cdn.discordapp.com/embed/avatars/3.png",
            "tag": "justluvi",
            "avatarURL": "https://cdn.discordapp.com/avatars/311364847826763776/c177a8b24cc362d2128a1347556183f3.webp",
            "displayAvatarURL": "https://cdn.discordapp.com/avatars/311364847826763776/c177a8b24cc362d2128a1347556183f3.webp"
        },
        "presence": "online",
        "activities": [
            {
                "name": "Spotify",
                "type": 2,
                "url": null,
                "details": "EARFQUAKE",
                "state": "Tyler, The Creator",
                "applicationId": null,
                "timestamps": {
                    "start": "2024-05-17T10:03:04.572Z",
                    "end": "2024-05-17T10:06:14.638Z"
                },
                "party": {
                    "id": "spotify:311364847826763776"
                },
                "syncId": "5hVghJ4KaYES3BFUATCYn0",
                "assets": {
                    "largeText": "IGOR",
                    "smallText": null,
                    "largeImage": "spotify:ab67616d0000b2737005885df706891a3c182a57",
                    "smallImage": null
                },
                "flags": 48,
                "emoji": null,
                "buttons": [],
                "createdTimestamp": 1715940186756
            }
        ]
    },
    "status": "user found ;)"
}
```

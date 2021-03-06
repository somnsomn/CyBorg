# CyBorg

[![npm version](https://img.shields.io/npm/v/cyborg-bot.svg)](https://www.npmjs.com/package/cyborg-bot)
[![npm license](https://img.shields.io/npm/l/cyborg-bot.svg)](https://www.npmjs.com/package/cyborg-bot)
[![dependencies](https://img.shields.io/david/carriejv/cyborg.svg)](https://david-dm.org/carriejv/cyborg)
[![devDependencies](https://img.shields.io/david/dev/carriejv/cyborg.svg)](https://david-dm.org/carriejv/cyborg#info=devDependencies)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/carriejv)

CyBorg is a [Discord](https://discordapp.com) bot for [CyTube](https://cytu.be) channels.

It is still early in development, so many features are messy and incomplete. You have been warned.

## Add CyBorg to your Discord server!

To invite the bot to your server, click this link: [https://discordapp.com/api/oauth2/authorize?client_id=422496569489752064&permissions=199680&scope=bot](https://discordapp.com/api/oauth2/authorize?client_id=422496569489752064&permissions=199680&scope=bot)

Once the bot is in your server, you can use `!cy cytube <cytube channel>` to get info about a CyTube channel.

The server owner (and other users promoted with `!cy admin <user mention>`) can also use `!cy announce <cytube channel>` to create automatic announcements for a channel and `!cy channel <channel mention>` to set the Discord channel they appear in.

Admins can also set a custom command prefix with `!cy prefix <prefix>`.

Other commands include:
```
!cy help
!cy info
!cy booyah
!cy chuck
```

## Host your own copy!

If you prefer to locally host your own copy of CyBorg, you can do that too. CyBorg requires the [Node.js](https://nodejs.org/en/) `v11.8.0` runtime.

Register your own Discord app [here](https://nodejs.org/en/) and fill the appropriate information into `./secrets/discord.json`. An example file is provided.

Then, install dependencies with `npm i` and use `npm start` to start the bot. The bot will print your invite link to the console.
# Discord 1337 Bot 🤖

A simple Discord bot that replies "damn it" whenever anyone says "1337"

![](https://cdn.glitch.com/f1b80a31-0733-40fb-a0dd-44c8c80c155d%2Fscreenshot.png?1506425519756)

## Steps to set up:

1. Create an app here: [https://discordapp.com/developers/applications/me](https://discordapp.com/developers/applications/me)
2. Click "Create a Bot User"
3. Add the Bot User to your Discord server using this link: `https://discordapp.com/oauth2/authorize?&client_id=<CLIENT ID>&scope=bot&permissions=0` replacing `<CLIENT_ID>` with the Client ID found on the page of your app
4. Set the `DISCORD_BOT_ID` value in `.env` using the Bot User token (Click to reveal in the app page)

## The code

Check out `server.js` to see how it works ✨

We're using the [Eris](https://npm.im/eris) library to interact with the Discord API
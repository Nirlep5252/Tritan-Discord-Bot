![](https://img.shields.io/badge/Maintained-Yes-%237289DA)
![](https://img.shields.io/badge/Version-4.0.0-7289DA)
![](https://img.shields.io/badge/Library-Discord.js-7289DA)
![](https://img.shields.io/badge/Lead%20Developer-Dylan%20James-7289DA)
![](https://img.shields.io/badge/Developers-Windows%20&%20Crafterzman-7289DA)
![](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%20by-Team%20Tritan-%237289DA)



# 🤖 Tritan Bot 
> Tritan Bot is a Discord general purpose bot built with discord.js and ejs (yes, it has a dashboard included). Please read through the [docs](https://docs.tritanbot.xyz) before even thinking about running this yourself.

[![](https://discordapp.com/api/guilds/732708260519346217/embed.png?style=banner2)](https://discord.gg/ScUgyE2)


# 🔥 Can I Add Tritan Bot To My Server?

Yes, please go [here](https://tritanbot.xyz/invite) to invite the bot. If you require support, or you would like to give any feedback or suggestions, please join [the support server.](https://discord.gg/ScUgyE2).


# 😊 Documentation

While there is no documentation to run Tritan Bot yourself because it's not suggested, please visit [this website](https://docs.tritanbot.xyz) for more information on the commands and setup available.


## 📝 Features & Commands

> Note: The default prefix is '*'
* Play music from YouTube via url
* Play music from YouTube via search query
* Play music from Soundcloud via url
* Search and select music to play
* Play youtube playlists via url
* Play youtube playlists via search query
* Now Playing 
* Queue system 
* Loop / Repeat 
* Shuffle 
* Volume control
* Lyrics 
* Pause 
* Resume 
* Skip to song # in queue 
* Help Command
* Media Controls via Reactions
* Enhanced Logging
* Easy to Use Utilities
* Necessary but Enhanced Infractions
* Join/Leave Logging
* Ban Logging
* Unban Logging
* Kick Logging
* Channel Creation/Deletion Logging
* Channel Update Logging
* Role Creation/Deletion Logging
* Role Update Logging
* Deleted Message Logging
* Message Purging with Logs
* Gifs for everything
* Fact commands
* Topic commands
* Memes
* Quotes
* Suggestions
* User information
* Fetch User ID
* Fetch Avatar
* Moderation Tools
* Clean, Kick, Ban, Warn
* AFK System
* and many more commands! 


# ⚠️ Should I Run Tritan Bot Locally?

Probably not. Tugboat has enough moving pieces that running a local version is complicated. The main purpose of having the source released is to allow others to understand and audit the functionality. The code is by no means meant to be easy to setup or bootstrap, and I don't plan on supporting folks trying to run locally. That said, feel free to run a local version of Tritan for your server (but not a public version please). 

# 📝 Self-hosting Agreement

* You may not use the Tritan logo or name within derivative bots.
* You may not host a public version of Tritan Bot.
* You may not charge for the usage of your instance of Tritan Bot.
* You may not provide support for Tritan Bot.
* You may not remove any credits to the original author anywhere within this bot. I know what code I've written, and I will recognize it.


## 🌿 Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v12.0.0 or newer
4. At least 4GB of Ram 
6. MongoDB **[Guide](https://docs.atlas.mongodb.com/tutorial/deploy-free-tier-cluster/)**  


## 🚀 Getting Started

```
git clone https://github.com/team-tritan/tritan-bot.git 
cd tritan-bot
cd bot
npm i 
```


## ⚙️ Configuration

```
You will need to fill in anything that is blank in the `bot/src/config` directory. It can be confusing, but it's super easy once you know what you're doing. If you require any assistance please join our support server.
```


## 🔛 Start Up

After installation finishes you can use pm2 to run this bot and web dashboard seperately. You must start these scripts from within their own directory, using `node ../../../index.js` will not work!
```
(Bot) Non-Sharding:
cd ./bot/src
pm2 start tritan.js --name Tritan-NonSharding
-- pm2 stop Tritan-NonSharding
-- pm2 restart Tritan-NonSharding

Or

(Bot) Sharding:
cd ./bot/src
pm2 start clusters.js --name Tritan-Sharding
-- pm2 stop Tritan-Sharding
-- pm2 restart Tritan-Sharding

Then

(Web) Dashboard:
cd ./web
pm2 start index.js --name Tritan-Web
-- pm2 stop Tritan-Web
-- pm2 restart Tritan-Web

pm2 save
pm2 startup 
```


## 🤝 Contributing
**Can I contribute?**

Maybe. Feel free to submit PRs and issues, but unless they are explicitly bug fixes that have good documentation and clean code, I likely won't merge. Features will not be accepted through PR unless stated elsewhere. Do not submit feedback on this repository, the server is the right place for that. PRs focused around the frontend and web panel are more likely to be accepted.

1. [Fork the repository](https://github.com/team-tritan/tritan-bot/fork)
2. Clone your fork: `git clone https://gitlab.com/your-username/tritan-bot.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -am 'Add some feature'`
5. Push to the branch: `git push origin my-new-feature`
6. Submit a pull request


## 📝 Credits
* Tritan's Backend was developed by [DylanJames#0420](https://github.com/dylanjamesdev)
* Tritan's Dashboard was developed by Windows#0001 and [DylanJames#0420]((https://github.com/dylanjamesdev)
* Tritan Bot is currently being maintained by [Team Tritan](https://gitlab.com/team-tritan) and their team of developers which includes Crafterzman#8726.

## 📝 Inspiration
* The music aspect of this bot is inspired by [Evobot](https://github.com/eritislami/evobot). 

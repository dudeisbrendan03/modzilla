# modzilla
A custom version of awesomebot

Welcome to Modzilla, a version of AwesomeBot! 
This repo will be mostly focused on new features. The official Modzilla instance, will always run the latest code from this repo.

# No0b setup

https://github.com/dudeisbrendan03/Dashy-Suite-Launcher

# Quick setup | Manual

1-In a preffered editor (not notepad) edit `Configuration/auth.json` and `Confiuration/config.json`

2-In the home directory of modzilla run `npm install`

3-Run `node bot.js` in the home directory

To prevent web setup confusion:
# Demo config.json

```
    "platform": "discord", #Bot platform/dont change
    "shard_count": 1, #Amount of shards the server hosts
    "hosting_url": "http://website.net:8080", #Url what will be PMed to users
    "httpPort": 8080, #Port for hosting
    "httpsPort": 8443, #Port for https/ssl hosting
    "cert": "", #Only needed for secure hosting
    "privKey": "", #Only needed for secure hosting 
    "httpsRedirect": false, #Redirct unsecure to secure
    "server_ip": "0.0.0.0", #Hosting IP (NOT DOMAIN)
    "db_url": "mongodb://localhost:27017/awesomebot",
    "game": "default", #Game displayed by bot, can be changed here
    "status": "online", #Status BUSY/AWAY/ONLINE/OFFLINE
    "max_voice_channels": 2, #Amount of VCs the bot can be in
    "header_image": "asd.jpg", #Website header image located in home dir of the bot
    "homepage_message_html": "", #Homepage message on hosted site
    "pm_forward": false, #PM all messages to sender
    "version": "Dashy Connect | Modzilla 5.2 | ABCORE4 | (Also using some gAB modules)", #Version of the bot
    "oauth_link": "", #an oauth2 link to add the bot
    "discord_link": "https://discord.gg/yykHgvk", #the bots support server

```

# tiktokdw
A discord bot that allows you to download TikTok videos with or without downloads enabled, it's dm only right now.

To fillout the config you need to edit config.go, I did this because when compiling to a linux binary and running with a service, it seemed to not be able to pickup the config.json file.

You can find the bot in [this server](https://discord.gg/rvzuwcjSbX) or invite it [here](https://discord.com/api/oauth2/authorize?client_id=800657106314461246&permissions=8&scope=bot)

# To run
Make sure you have [go](https://golang.org/doc/install) installed!

```
$ git clone https://github.com/postrequest69/TikTok-Downloader-DiscordBot.git
$ cd TikTok-Downloader-DiscordBot
$ go get github.com/bwmarrin/discordgo
$ go get github.com/PuerkitoBio/goquery
$ go build or go run .
$ run the exe...
```

# TO-DO
Guild side config

![Node build](https://github.com/eritislami/evobot/actions/workflows/node.yml/badge.svg)
![Docker build](https://github.com/eritislami/evobot/actions/workflows/docker.yml/badge.svg)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)



# 🤖 Discord Music bot

> This is a Discord Music Bot built with discord.js & uses Command Handler from [discordjs.guide](https://discordjs.guide)
## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. Node.js 16.9 or newer

## 🚀 Getting Started

```sh
git clone https://github.com/ALviN01010101/Discord-musicBot.git
cd cd Musicbot
npm install
```

After installation finishes follow configuration instructions then run `node index.js` to start the bot.

## ⚙️ Configuration

Copy or Rename `config.json.example` to `config.json` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "LOCALE": "en",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

## 🐬 Docker Configuration

For those who would prefer to use our [Docker container](https://hub.docker.com/repository/ALviN01010101/Discord-musicBot), you may provide values from `config.json` as environment variables.

```shell
docker run -e "TOKEN=<discord-token>"
```

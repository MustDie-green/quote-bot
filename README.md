# quote-bot
Telegram quote bot

Fork of https://github.com/CielNeko/quote-bot that fork of https://github.com/LyoSU/quote-bot
Main difference from the original one:
- You don't need to install prebuild tdlib, docker image already has it
- Installation with only one repo clone and one docker compose

# Docker compose installation
1) Pull this repo

3) Edit `.env-bot.example` and `.env-api.example` and remove `.example`

5) Edit `config/config.json`

6) `docker compose up -d` (maybe you'll need to install/update Docker or use docker-compose instead of docker compose)

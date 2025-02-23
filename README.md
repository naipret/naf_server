## Some important settings!
- First, run these commands:
  ```
  lp import "luckperms-naf-default.json.gz"
  ```
  ```
  gamerule playersSleepingPercentage 50
  ```
  ```
  scoreboard players set #stellarity.config stellarity.config.dragon_health 500
  ```
  ```
  rs install Terralith
  ```
- Then restart and run these commands:
  ```
  rs set spring world
  ```
  ```
  timebar reload
  ```

## Some optional customizations!
- Add bot token for DiscordSRV in `plugins/DiscordSRV/config.yml`
- Add bot token for Discord Voice Chat in `plugins/voicechat-discord/config.yml`
- Add webhook for Grim in `plugins/GrimAC/discord.yml`
- Add webhook for BanWebhook in `plugins/BansWebhook/config.yml`
- Use `/setspawn` and `/setworldspawn` to set the spawn points
- Use `/maintenance on` if you are not ready to open the server yet
- Start preload your world with chunky, use: `/chunk world <world_name>`, `/chunky radius <radius>`, `/chunky start`

## Other information:
- Paper folk optimization: https://paper-chan.moe/paper-optimization/
- Flags generator: https://www.birdflop.com/resources/flags/
- Optimization guide used at: https://minecraftvn.net/cau-hinh-de-giam-lag-va-toi-uu-server-minecraft-de-dat-hieu-nang-tot-nhat.t46151/


# Doge Death Ban

Drop-in Fabric server mod that adds death bans to your server.   

### Features
- Doesn't ban instantly like most mods. Most mods instant-ban you which is jarring. This mod has a configurable timer where you stare at the death screen unable to respawn before it bans you.
- Configurable ban time
- Configurable ban message
- Supports ACTUAL hardcore worlds, shows hardcore hearts to your players, without allowing them to go into spectator. (Must be enabled in your level.dat or server.properties at world generation)

## Commands
`/deathbanreset {username}` to unban someone

## Configuring

`config/PandaDeathBan.json` generated at runtime.
```json
{
  "banDurationSeconds": 604800,
  "disconnectTimerSeconds": 5,
  "banMessage": [
    "<red>☠ You are Dead ☠</red>",
    "",
    "<white>You can join in: <yellow>%death_time_remaining%</yellow></white>",
    "",
    "<gray>Discord: discord.hardcoreanarchy.gay</gray>"
  ]
}
```

## Try it out
`hardcoreanarchy.gay`   (Deathban Anarchy)  

## Support



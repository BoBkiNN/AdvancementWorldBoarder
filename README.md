# AdvancementWorldBoarder
Minercaft plugin that will expand worldborder if advancement gathered
# Config.yml
```yaml
EnabledWorlds:
  - "world_the_end"
  - "world_nether"
  - "world"
DisabledAdv:
  - "minecraft:story/root"
  - "minecraft:recipes"
  - "blazeandcave:technical"
  - "blazeandcave:bacap/root"
#Will disable expanding on this advancements
DivideNether: true
#Divide world_nether`s ExpandBlocks by 8
ChatMsgToggle: true
EnableSound: true
SoundName: "ENTITY_PLAYER_LEVELUP"
#Sound list: https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Sound.html
SoundX: 0
SoundY: 80
SoundZ: 0
SoundVolume: 3000000
SoundPitch: 0.5
OnExpandMsg: "&a&lWorld was expanded by &e%displayname%!"
#Placeholders: %displayname% - player display name, %name% - player original nickname
ExpandBlocks: 10
ExpandSeconds: 5
debug: false
```

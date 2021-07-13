---
description: Here you will learn everything about the Config.json file
---

# Config.json

{% hint style="warning" %}
Here you will have information on most of variables that are easy to understand
{% endhint %}

## General configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| PREFIX | Prefix of most of messages | &fElytraRacing &c&gt;&gt; &f |
| max\_info\_per\_page | Maximum amount of information per page of chat commands | 10 |
| ParticleRatio | Ratio of particle to draw shapes | 4 |
| ER\_SHOW\_TRAIN | Is the command /er train is displayed in the /er help | true |
| ER\_SHOW\_SHOW | Is the command /er play is displayed in the /er help | true |
| ER\_TRAIN\_MAPS | List of maps available for training \(\["map1","map2"\]\) | \[\] |
| ER\_TRAIN\_ENABLE | Is training is available | true |
| SIGN\_RELOAD\_SEC | Interval between sign's refresh \(seconds\) | 3 |
| TELEPORT\_SOLVER | When you teleport to a location, you are teleported 0.5 above to avoid problems.false | false |
| UNLOCK\_DISTANCE | Maximum distance between you are the object that you locked before being unlocked | 100 |
| ITEM\_DEFAULT\_PRECISION\_LOC | Default precision for location mouvement | 0.25 |
| ITEM\_DEFAULT\_PRECISION\_DEGREE | Default precision for angle rotation | 2.5 |
| SEPERATE\_GAMES\_HIDE\_PLAYERS | Is the tab list are separated from other games and the server | true |
| CUSTOM\_AND\_SEPARATED\_CHAT | Separate chat between games and the server \(The players send messages in the game but can see messages from the global server\) | false |
| PARTICLE\_VIEW\_DISTANCE | Maximum distance to show an object | 250 |

## Holograms

| Variable | Description | Default |
| :--- | :--- | :--- |
| HOLOGRAMS\_UPDATEINTERVAL | Interval between hologram's refresh  | 60000 |
| HOLOGRAMS\_LINESPACE | Space between two lines  | 0.29 |
| HOLOGRAMS\_RANK\_LIMIT | Rank limit displayed by an hologram | 15 |
| HOLOGRAMS\_FAKE\_LINES | Is the hologram complete the rank limit with fake lines | false |
| HOLOGRAMS\_PERSONAL\_MAPS\_MAX | Maximum amount of maps statistics displayed for personal hologram | 10 |
| HOLOGRAMS\_0\_SHOW | Is the hologram display player' score equals to 0 | true |
| HOLOGRAMS\_RANK\_DUPLICATION | Is hologram show duplicated ranks \(as for example 2 players at the second place\) | true |
|  |  |  |

## Replay sytem

The replay system is not perfect but does the job



| Variable | Description | Default |
| :--- | :--- | :--- |
| REPLAYS | Is the replay system activated | true |
| REPLAY\_FORMAT\_16MAXCHAR | Replay NPC's username | &7{MINUTES}m {SECONDS}.{MILLISECONDS}s |
| REPLAYS\_SHOWSKINS | Is Replay NPC have skins | true |
| REPLAY\_MAXSIZE\_CHAR | Maximum size of saved text per replay | 1000000 |

## MySQL configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| /database | Path location for SQLite | /database |
| SQL\_STATS\_INTERVAL | Interval between every call to database for player' stats | 10000 |
| SQL\_USE\_CUSTOM\_SQL | Set to true if you want to use your MySQL server | false |
| SQL\_CUSTOM\_SQL\_HOST | Host of your database |  |
| SQL\_CUSTOM\_SQL\_PORT | Port of your database |  |
| SQL\_CUSTOM\_SQL\_DATABASE | Name of the database |  |
| SQL\_CUSTOM\_SQL\_USER | User of your database |  |
| SQL\_CUSTOM\_SQL\_PASSWORD | Password of your database |  |
| SQL\_CUSTOM\_SQL\_TYPE | Database type only support MySQL | mysql |
| SQL\_SAVE\_HOST\_STATS | Is player' stats in hosted game is saved | true |

## Pre-Game configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| TimerStart | Countdown of games | 30 |
| TimerStartFull | Countdown of games if full | 15 |

## Host configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| TimerStart\_host | Countdown of host game | 15 |
| Max\_maps\_per\_games | Maximum number of maps possible | 4 |
| Max\_alert\_host | Maximum number of alert possible | 3 |

## Host configuration \(Map testing\)

| Variable | Description | Default |
| :--- | :--- | :--- |
| GUI\_MAPTESTING\_MAXPLAYER | Maximum number of player in a map testing host | 10 |
| GUI\_MAPTESTING\_PERMISSION | Permission to join a map testing host as default | null |

## Spectators configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| AutoTP\_Spec\_Distance | Distance from the nearest player before being teleported back to the map | 75 |

## Game configuration

| Variable | Description | Default |
| :--- | :--- | :--- |
| TP\_ON\_HIT | Is a player is teleported back if he touches a block | true |
| LineHelper | Is a line is drawn toward the next checkpoint to help the player | true |
| NEXT\_CHECKPOINT\_PARTICLE | Particule used to draw LineHelper | END\_ROD |
| TimerRound | Countdown rounds | 15 |
| MAP\_DIFICULTY | Is difficulty of the map is displayed | true |
| MAP\_DIFFICULTY\_DEFAULT | Default difficulty | 3 |
| MAP\_DIFFICULTY\_MAX | Maximum difficulty | 5 |
| DNF\_POINT | Score that will be given when player DNF in grandprix \(disable: -1\) | -1 |
| TABLIST\_GRANDPRIX | Enable or disable the custom tab list in grandprix | true |
| DNF\_INSTANT\_QUIT | When you DNF you instant quit your game is you are in racemode | false |
| COMMANDS\_WHITELIST | Enable or disable a command whitelist in a game | false |
| SPECTATOR\_ITEM | Give the player the object to become a spectator at the end of his run | true |
| STATIC\_ITEMS | Make items static | true |

## End game

| Variable | Description | Default |
| :--- | :--- | :--- |
| RankingMaxPlayers | Amount of players shown in leader boards | 8 |
| PODIUM\_FIREWORKS | Enable or disable fireworks on podium  | true |
| PODIUM\_FIREWORK\_NUMBER | Number of fireworks fired from the podium | 10 |
| END\_TIME | Time before the game automatically close itself \(seconds\) | 30 |

## Command execution \(COMMAND\_EXECUTION\_PER\_RANK\_\)

{% hint style="info" %}
Commands are executed at the end of the game according to a player rank
{% endhint %}

"1": "\[CONSOLE\]/give {SELF\_PLAYER} minecraft:cookie {SCORE} §%§\[PLAYER\]/tell {SELF\_PLAYER} you executed a command"

{% hint style="info" %}
This mean that the **console** will execute the command **/give {SELF\_PLAYER} minecraft:cookie {SCORE}** and the **player** will execute the command **/tell {SELF\_PLAYER} you executed a command** and replace {SELF\_PLAYER} with the player's name and {SCORE} by the score the player had in a grandprix.

"1" Means that it will work for the player who won

"-999" Means that every players that don't have commands here will execute command
{% endhint %}

\_\_




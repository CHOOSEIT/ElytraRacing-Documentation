---
description: Here you will learn everything about map configuration
---

# ⚙ Map.json

{% hint style="info" %}
Most of the configuration can be done from commands. [here](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-system)
{% endhint %}

| Variable                                            | Description                                                                                                                 |
| --------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| name                                                | Name of the map                                                                                                             |
| Enabled                                             | Enable or disable the map                                                                                                   |
| Checkpoints                                         | List of [checkpoints](https://chooseit.gitbook.io/elytraracing/configuration/map.json/checkpoint-end)                       |
| Ends                                                | List of [ends](https://chooseit.gitbook.io/elytraracing/configuration/map.json/checkpoint-end)                              |
| difficulty                                          | Difficulty of the map                                                                                                       |
| default\_particle\_effect\_random                   | Default particle of every checkpoints of the map                                                                            |
| default\_particle\_effect\_random\_ifnext           | Default particle of every checkpoints of the map if the checkpoint is next of the player                                    |
| default\_particle\_effect\_end                      | Default particle of every ends of the map                                                                                   |
| default\_particle\_effect\_end\_ifnext              | Default particle of every ends of the map if the end is next of the player                                                  |
| location\_lobby                                     | Lobby location of the map                                                                                                   |
| location\_start                                     | Start location of the map                                                                                                   |
| location\_end                                       | End location of the map                                                                                                     |
| uuid                                                | UUID of the map for the database. **Have to be unique in the server, If you duplicate a map make sure to change this UUID** |
| locations\_podium                                   | Locations of podium                                                                                                         |
| podium                                              | Enable or disable podium of the map                                                                                         |
| <p>MAP_TIME_MAX_MINUTES<br>MAP_TIME_MAX_SECONDS</p> | Maximum time for the map                                                                                                    |
| default\_particle\_effect\_additionalObject         | Default particle of every additional objects of the map                                                                     |
| default\_particle\_effect\_additionalObject\_ifnext | Default particle of every additional objects of the map if the end is next of the player                                    |
| spec\_cant\_pass\_through\_wall                     | Boolean is a spec can or not pass through walls in this map                                                                 |
| numberoflaps                                        | Number of laps on this map                                                                                                  |


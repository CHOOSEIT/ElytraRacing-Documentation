---
description: Here you will learn everything about the Autogame.json file
---

# Autogames.json

{% hint style="info" %}
The Queue system works by itself, these variables are only meant to solve duplication queue error
{% endhint %}

| Variable | Description |
| :--- | :--- |
| DEFAULT\_QUEUE | Default queue that will be use with the command [er play](https://chooseit.gitbook.io/elytraracing/commands/command-er#play) |
| ENABLED\_QUEUES | List of queues that are enabled |
| DISABLED\_QUEUES | List of queues that are disabled |

{% hint style="info" %}
To add a new autogames execute [ergames add](https://chooseit.gitbook.io/elytraracing/commands/command-ergames#add)

Next variable are for each autogames in the **autoGamesList** variable list
{% endhint %}

{% hint style="info" %}
Setting the name of a game with **§** makes the game impossible to be joined with the [er join](https://chooseit.gitbook.io/elytraracing/commands/command-er#join) command
{% endhint %}

| Variable | Description |
| :--- | :--- |
| name | Name of the game |
| maps | List of maps in the autogame |
| minplayers | Minimum players required to start the game |
| maxplayers | Maximum players in the game |
| mapnumber | Number of maps chosen among the list of maps |
| randomMapSorting | Enable or disable random choosing map for the map list |
| enabled | Enable or disable autogame \(in game: [ergames set](https://chooseit.gitbook.io/elytraracing/commands/command-ergames#set)\) |
| queue | Queue that the autogame belongs to  |
| permission | Permission to join the game |


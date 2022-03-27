---
description: Here you will learn every information about PlaceholderAPI
---

# PlaceholderAPI

#### PlaceholderAPI is optional

{% hint style="info" %}
Every variable of PlaceholderAPI need be surrounded by %

Exemple: %elytraracing\_self\_playedracemode_%_
{% endhint %}

{% hint style="warning" %}
Not every plugins are compatible with PlaceholderAPI
{% endhint %}

{% hint style="info" %}
ElytraRacing don't support placeholders in its messages.

ElytraRacing support placeholders in its scoreboards.
{% endhint %}

{% hint style="success" %}
**\<player>** argument must be replaced by:

* The actual name of the player
* "self": target the player which the message is sent to

**\<map>** argument must be replaced by:

* The actual name of the map
{% endhint %}

| Variable                                                 | Description                                            |
| -------------------------------------------------------- | ------------------------------------------------------ |
| **elytraracing\_\<player>\_playedracemode**              | Get how many times the player played race mode         |
| **elytraracing\_\<player>\_playedgrandprix**             | Get how many times the player played grandprix         |
| **elytraracing\_\<player>\_wonracemode**                 | Get how many times the player have won a race mode     |
| **elytraracing\_\<player>\_wongrandprix**                | Get how many times the player have won a grandprix     |
| **elytraracing\_\<player>\_mapplayed**                   | Get the total of map played                            |
| **elytraracing\_\<player>\_mapfinished**                 | Get how many times the player have finished maps       |
| **elytraracing\_\<player>\_score**                       | Get the score of the player                            |
| **elytraracing\_\<player>\_rank\_playedracemode**        | Get the rank of the player in racemode (time played)   |
| **elytraracing\_\<player>\_rank\_playedgrandprix**       | Get the rank of the player in grandprix (time played)  |
| **elytraracing\_\<player>\_rank\_score**                 | Get the rank of the player in score                    |
| **elytraracing\_\<player>\_\<map/favorite>\_winrate**    | Get the winrate of the player on a map                 |
| **elytraracing\_\<player>\_\<map/favorite>\_ranking**    | Get the ranking of the player on a map                 |
| **elytraracing\_\<player>\_\<map/favorite>\_playertime** | Get the time of the player on a map                    |
| **elytraracing\_\<player>\_\<map/favorite>\_name**       | Get the name of a map                                  |
| **elytraracing\_lastgame\_\<rank>\_username**            | Get player's username per rank of the last game played |

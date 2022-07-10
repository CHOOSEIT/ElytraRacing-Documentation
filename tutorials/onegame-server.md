---
description: Here you will learn how to use the OneGame system
---

# 📚 "OneGame" server

{% hint style="danger" %}
This feature is experimental, if you have any problems please contact me on my discord
{% endhint %}

## What is OneGame system ?

OneGame system makes your server running only 1 game of ElytraRacing.

&#x20;This system could be associated with a BungeeCord mode.&#x20;

When a player will join the server, it will automatically put the player in a game. When a player leaves the server/ the game is ended. The player will be kicked from the server/ teleported in another server.

## 1. Requirements

#### Create an AutoGame&#x20;

This AutoGame is the game that will be used and restarted at the end of each games. More information [here](https://chooseit.gitbook.io/elytraracing/tutorials/create-game/how-to-use-autogames).

#### (Optional) Have a "lobby" server (BungeeCord)

This server will be the server where the player will be teleported after the game .

## 2. Configuration

The configuration is done in the file "Config.json"

{% hint style="success" %}
Set ONEGAME to true
{% endhint %}

| Variables                           | Description                                                                        |
| ----------------------------------- | ---------------------------------------------------------------------------------- |
| ONEGAME\_AUTOJOINGAME               | Name of the AutoGame                                                               |
| ONEGAME\_KICK\_AFTER\_GAME          | Will the player be kicked from the server after the game/(leave)                   |
| ONEGAME\_LOBBYSERVER                | Name of the "lobby" server                                                         |
| ONEGAME\_REMOVEJOINQUITMESSAGES     | Will the join messages be displayed                                                |
| ONEGAME\_MOTD\_USE                  | This feature provide MOTD customization                                            |
| ONEGAME\_MOTD                       | MOTD content customization                                                         |
| ONEGAME\_MOTD\_CHANGE\_MAX\_PLAYERS | Will the MOTD max player will be changed according to the max players of the game. |

---
description: Here you will learn everything about the Scoreboard.json file
---

# ⚙ Scoreboard.json

{% hint style="success" %}
There is 3 types of list of scoreboard:&#x20;

```
RaceMode -> Scoreboards for Races
```

 

```
GrandPrix -> Scoreboards for GrandPrix
```

 

```
Training -> Scoreboards for Training mode
```

**As default every type possible per mode are setup.** 
{% endhint %}

{% hint style="info" %}
Only the TRAINING state is available in the training mode
{% endhint %}

{% hint style="success" %}
**HOST\_ prefix differentiates between hosted games and Autogames.**
{% endhint %}

### States

| States                  | Description                                                      |
| ----------------------- | ---------------------------------------------------------------- |
| WAITING                 | Waiting players in game                                          |
| STARTING                | Starting countdown                                               |
| STARTED                 | In game.                                                         |
| FINISHED                | The game is ending                                               |
| BETWEENROUND            | **(Only in GrandPrix)** Moment between rounds                    |
| SPECTATOR               | In game (Spectator vision)                                       |
| SPECTATOR\_FINISHED     | The game is ending (Spectator vision)                            |
| SPECTATOR\_BETWEENROUND | **(Only in GrandPrix)** Moment between rounds (Spectator vision) |

### Global variables

{% hint style="success" %}
Remplace {RANK} with the rank of the player you want (between 1 and 15)
{% endhint %}

| Variables                        | Description                                                                          |
| -------------------------------- | ------------------------------------------------------------------------------------ |
| MAP\_WR\_TIME                    | Current map's world record                                                           |
| MAP\_WR\_PLAYER                  | Current map's world record holder username                                           |
| CURRENT\_PLAYER                  | Current number of players                                                            |
| MAX\_PLAYER                      | Max. number of players in the game                                                   |
| MIN\_PLAYER                      | Min. number of players to start the game                                             |
| NEEDED\_PLAYER                   | Players left to start to start the game                                              |
| CURRENT\_MAP                     | Current map's name                                                                   |
| NEXT\_MAP                        | Next map's name                                                                      |
| CURRENT\_MAP\_DIFFICULTY         | Current map's difficulty                                                             |
| NEXT\_MAP\_DIFFICULTY            | Next map's difficulty                                                                |
| STARTING\_COUNTDOWN              | Countdown                                                                            |
| TIME\_LEFT                       | Time left in the game                                                                |
| MAX\_LAPS                        | Number of laps                                                                       |
| MAX\_CPS                         | Number of checkpoints                                                                |
| CURRENT\_ROUND                   | Current round of the game                                                            |
| MAX\_ROUND                       | Number of rounds                                                                     |
| HOST\_NAME                       | Host's name                                                                          |
| HOST                             | Host's username                                                                      |
| **LINK**                         | **Value of the link variable**                                                       |
| RACE\_RANK\_PLAYER\_{RANK}       | Username of the player ranked: {RANK} currently in the race                          |
| RACE\_RANK\_PLAYER\_{RANK}\_LAPS | Current lap of the player ranked: {RANK} currently in the race                       |
| RACE\_RANK\_PLAYER\_{RANK}\_CPS  | Number of checkpoints passed by the player ranked: {RANK} currently in the race      |
| RANK\_PLAYER\_{RANK}             | Username of the player ranked: {RANK} currently in the global rank (GrandPrix score) |
| RANK\_PLAYER\_{RANK}\_SCORE      | Score of the player ranked: {RANK} currently in the global rank (GrandPrix score)    |

### Personal variables

| Variables                 | Description                                                      |
| ------------------------- | ---------------------------------------------------------------- |
| SELF\_LAPS                | Current lap                                                      |
| SELF\_CPS                 | Current checkpoint                                               |
| SELF\_RACE\_RANK\_PLAYER  | Current rank of the player in the race                           |
| SELF\_RANK\_PLAYER        | Current rank of the player in the global rank (GrandPrix score)  |
| SELF\_RANK\_PLAYER\_SCORE | Current score of the player in the global rank (GrandPrix score) |
| SELF\_MAP\_PB             | Personal best on the current map                                 |
| SELF\_MAP\_RANK           | Rank of the personal best on the next map on the server          |
| SELF\_MAP\_WINRATE        | Winrate of the player on the current map                         |
| SELF\_NEXT\_MAP\_PB       | Personal best on the next map                                    |
| SELF\_NEXT\_MAP\_RANK     | Rank of the personal best on the next map on the server          |
| SELF\_NEXT\_MAP\_WINRATE  | Winrate of the player on the next map                            |

---
description: Here you will learn everything about signs
---

# How to use signs

{% hint style="warning" %}
Default permission: elytraracing.sign
{% endhint %}

{% hint style="info" %}
Signs are associated with [autogames system](https://chooseit.gitbook.io/elytraracing/configuration/autogames.json)
{% endhint %}

## Queues

Every autogames are associated to a queue.

![](../.gitbook/assets/image%20%281%29.png)

{% hint style="info" %}
Signs have the same usage as [er play](https://chooseit.gitbook.io/elytraracing/commands/command-er#play) command
{% endhint %}

### Single game per queue

If a queue reference one autogame then the sign will be fixed on that game, show state, players, map.

![](../.gitbook/assets/image%20%282%29.png)

### Multiple game per queue

If a queue reference multiple autogames then the sign will work as [er play](https://chooseit.gitbook.io/elytraracing/commands/command-er#play) command and will display the most interesting game 

![](../.gitbook/assets/image%20%284%29.png)

{% hint style="info" %}
When the game displayed on the sign will start, the sign will show another game from the queue
{% endhint %}

### Disabled queue

{% hint style="success" %}
If there is **no game available** for this queue or if **every game are started** or if **the queue is disabled** then the sign will be disabled and will wait a game to be available
{% endhint %}

![](../.gitbook/assets/image%20%285%29.png)

{% hint style="warning" %}
If a sign reference a queue with one autogame, the sign won't be disabled if you disable the queue
{% endhint %}


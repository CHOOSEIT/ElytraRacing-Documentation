---
description: Here you will learn everything about checkpoint configuration
---

# Checkpoint / End

{% hint style="info" %}
Most of the configuration can be done from commands. [here](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration)
{% endhint %}

| Variable | Description | Checkpoint | End |
| :--- | :--- | :--- | :--- |
| LinkedTo\_id\_order | List of id\_orders linked to | Yes | No |
| enumParticle | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name | Yes | Yes |
| enumParticle\_IFNEXT | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name if the object is next of the player | Yes | Yes |
| x, y, z | Coordinates of the object | Yes | Yes |
| world | World's name | Yes | Yes |
| radius\_size | Radium of the object | Yes | Yes |
| x\_degrees, y\_degrees, z\_degrees | Rotation of the object | Yes | Yes |
| particle\_amount | Particle multiplication | Yes | Yes |
| boostMultiplier | Boost applied to the player when the player pass through the object | Yes | No |

{% hint style="info" %}
**boostMultiplier:** If you want that the checkpoint reduce the speed of the player you can use this parameter like this:

Example: Reduce player speed by 5% : **boostMultiplier: -0.95**
{% endhint %}

\*\*\*\*


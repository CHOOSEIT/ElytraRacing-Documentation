---
description: Here you will learn everything about additional object configuration
---

# Additional Object

{% hint style="info" %}
Most of the configuration can be done from commands. [here](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration)
{% endhint %}

| Variable | Description |
| :--- | :--- |
| ID\_justforindication | This show you the ID of the object when you saved the map. \(Can't be changed\) |
| enumParticle | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name |
| enumParticle\_IFNEXT | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name if the object is next of the player |
| x, y, z | Coordinates of the object |
| world | World's name |
| radius\_size | Radius of the object |
| x\_degrees, y\_degrees, z\_degrees | Rotation of the object |
| particle\_amount | Particle multiplication |
| boostMultiplier | Boost applied to the player when the player pass through the object |
| shape | Only "Circle" or null |
| fireworks | Fireworks given to the player with the player pass through the object |
| lineHelperto | let it as null |

{% hint style="info" %}
**boostMultiplier:** If you want that the checkpoint reduce the speed of the player you can use this parameter like this:

Example: Reduce player speed by 5% : **boostMultiplier: -0.95**
{% endhint %}

\*\*\*\*


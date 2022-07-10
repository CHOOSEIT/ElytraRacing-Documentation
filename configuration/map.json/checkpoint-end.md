---
description: Here you will learn everything about checkpoint and end configuration
---

# Checkpoint / End

{% hint style="info" %}
Most of the configuration can be done from commands. [here](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration)
{% endhint %}

| Variable                           | Description                                                                                                                                                                                                                                                            | Checkpoint | End                 |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------- |
| ID\_justforindication              | This show you the ID of the object when you saved the map. (Can't be changed)                                                                                                                                                                                          | Yes        | Yes                 |
| LinkedTo\_id\_order                | List of id\_orders linked to                                                                                                                                                                                                                                           | Yes        | No                  |
| enumParticle                       | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name                                                                                                                                                          | Yes        | Yes                 |
| enumParticle\_IFNEXT               | [Particle](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration) name if the object is next of the player                                                                                                                      | Yes        | Yes                 |
| x, y, z                            | Coordinates of the object                                                                                                                                                                                                                                              | Yes        | Yes                 |
| world                              | World's name                                                                                                                                                                                                                                                           | Yes        | Yes                 |
| radius\_size                       | Radius of the object                                                                                                                                                                                                                                                   | Yes        | Yes                 |
| x\_degrees, y\_degrees, z\_degrees | Rotation of the object                                                                                                                                                                                                                                                 | Yes        | Yes                 |
| particle\_amount                   | Particle multiplication                                                                                                                                                                                                                                                | Yes        | Yes                 |
| boostMultiplier                    | Boost applied to the player when the player pass through the object                                                                                                                                                                                                    | Yes        | No                  |
| shape                              | Only "Circle" or null                                                                                                                                                                                                                                                  | Yes        | Yes                 |
| lineHelperto                       | <p>List of id of objects that the line helper will draw toward (null or [] (empty)) draw lines to every linked objects and the object</p><p>Set the list as: [1, 2, 3, 4] the line starting from the current object will end on the objects with ids 1, 2, 3 and 4</p> | Yes        | Yes (multiple laps) |

{% hint style="info" %}
**boostMultiplier:** If you want that the checkpoint reduce the speed of the player you can use this parameter like this:

Example: Reduce player speed by 5% : **boostMultiplier: -0.95**
{% endhint %}

****

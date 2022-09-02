---
description: Here you will learn how to create new particle
---

# ℹ Particle informations

## Where to start ?

{% hint style="warning" %}
Too many Mask/Shape could have some loss of performance
{% endhint %}

{% hint style="success" %}
This feature is only available for version 1.5.0 and above
{% endhint %}

{% hint style="info" %}
Share particle channel: [https://discord.gg/ZFxJ6AtVZr](https://discord.gg/ZFxJ6AtVZr)&#x20;

Channel: #🧾-share-particle

Send me a message to add your particle to the list: CHOOSEIT#6056
{% endhint %}

We are going to work in the file: ElytraRacing/particles/particleConfig.json

### Example of a particle (Rainbow circle following player rotation)

```
{
    "name": "RainbowCircle",
    "enable": true,
    "particle": "REDSTONE",
    "removeFromPlayableSet": false,
    "item": "GOLDEN_APPLE:0",
    "showWithParticle": [
        "<ANOTHER PARTICLE>", "<ANOTHER PARTICLE2>"
    ],
    "shapeParticle": [
      {
        "key": "SHAPE_CIRCLE",
        "option": "20;0.66"
      },
      {
        "key": "MASK_PLAYERFOLLOW",
        "option": ""
      }
    ],
    "colorCreator": [
      {
        "key": "RAINBOW",
        "option": "10000;true"
      }
    ]
}
```

Follow:&#x20;

{% content-ref url="parameters-explanations/" %}
[parameters-explanations](parameters-explanations/)
{% endcontent-ref %}


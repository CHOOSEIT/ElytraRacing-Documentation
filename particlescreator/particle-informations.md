---
description: Here you will learn how to create new particle
---

# ℹ Particle informations

## Where to start ?

{% hint style="success" %}
This feature is only available for version 1.5.0 and above
{% endhint %}

We are going to work in the file: ElytraRacing/particles/particleConfig.json

### Example of a particle (Rainbow circle following player rotation)

```
{
      "name": "RainbowCircle",
      "enable": true,
      "particle": "REDSTONE",
      "item": "GOLDEN_APPLE:0",
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


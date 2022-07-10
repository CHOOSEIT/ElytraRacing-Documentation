---
description: Here you will learn how to use every parameters of the particle creator
---

# 💾 Parameters explanations

<details>

<summary>Example particle</summary>

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

</details>

First of all we have basics parameters like name, whether or not the particle is currently enable

{% hint style="info" %}
To see a particle in the particle selector in your games, the player has to have the permission: **elytraracing.particle.\<nameoftheparticle>**
{% endhint %}

{% hint style="info" %}
**Available particles:**

**Support coloration: REDSTONE**

**Others: Printed in the console at start**
{% endhint %}

{% hint style="success" %}
Test your work:&#x20;

* Set **enable** to false
* set **name** as your ingame username

It will apply directly to you the particles after the **/erconfig reload** (you still have to fly to activate)
{% endhint %}

{% hint style="danger" %}
Options of shape and color creator are separated by **;**
{% endhint %}

### **Key customisation**

There are 2 main parameters that we will explain here:

{% content-ref url="shapeparticle.md" %}
[shapeparticle.md](shapeparticle.md)
{% endcontent-ref %}

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

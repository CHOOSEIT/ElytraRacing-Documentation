---
description: >-
  Here you will everything to know on the ShapeParticle parameter of the
  particleCreator
---

# ⭕ ShapeParticle

Example of a shapeParticle

```
"shapeParticle": [
      {
        "key": "SHAPE_CIRCLE",
        "option": "20;0.66"
      },
      {
        "key": "MASK_PLAYERFOLLOW",
        "option": ""
      }
    ]
```

{% hint style="info" %}
Basic shapes can new be reused sequentially multiple times, it will for every displayed particle create the shape
{% endhint %}

{% hint style="success" %}
The shapeParticle parameter can be seen as an list of "instruction" executed sequentially to create the shape wanted
{% endhint %}

Each "instructions" has 2 parameters:

1. A key
2. Options (sometimes optionals)

{% content-ref url="../list-of-available-shapes.md" %}
[list-of-available-shapes.md](../list-of-available-shapes.md)
{% endcontent-ref %}


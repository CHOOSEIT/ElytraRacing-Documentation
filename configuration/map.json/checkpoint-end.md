---
description: Here you will learn everything about checkpoint and end configuration
---

# Checkpoint / End

{% hint style="info" %}
Most of the configuration can be done from commands. [here](https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration)
{% endhint %}

<table>
  <thead>
    <tr>
      <th style="text-align:left">Variable</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Checkpoint</th>
      <th style="text-align:left">End</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">ID_justforindication</td>
      <td style="text-align:left">This show you the ID of the object when you saved the map. (Can&apos;t
        be changed)</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">LinkedTo_id_order</td>
      <td style="text-align:left">List of id_orders linked to</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">No</td>
    </tr>
    <tr>
      <td style="text-align:left">enumParticle</td>
      <td style="text-align:left"><a href="https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration">Particle</a> name</td>
      <td
      style="text-align:left">Yes</td>
        <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">enumParticle_IFNEXT</td>
      <td style="text-align:left"><a href="https://chooseit.gitbook.io/elytraracing/commands/command-ermap#map-checkpoint-configuration">Particle</a> name
        if the object is next of the player</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">x, y, z</td>
      <td style="text-align:left">Coordinates of the object</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">world</td>
      <td style="text-align:left">World&apos;s name</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">radius_size</td>
      <td style="text-align:left">Radius of the object</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">x_degrees, y_degrees, z_degrees</td>
      <td style="text-align:left">Rotation of the object</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">particle_amount</td>
      <td style="text-align:left">Particle multiplication</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">boostMultiplier</td>
      <td style="text-align:left">Boost applied to the player when the player pass through the object</td>
      <td
      style="text-align:left">Yes</td>
        <td style="text-align:left">No</td>
    </tr>
    <tr>
      <td style="text-align:left">shape</td>
      <td style="text-align:left">Only &quot;Circle&quot; or null</td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes</td>
    </tr>
    <tr>
      <td style="text-align:left">lineHelperto</td>
      <td style="text-align:left">
        <p>List of id of objects that the line helper will draw toward (null or []
          (empty)) draw lines to every linked objects and the object</p>
        <p>Set the list as: [1, 2, 3, 4] the line starting from the current object
          will end on the objects with ids 1, 2, 3 and 4</p>
      </td>
      <td style="text-align:left">Yes</td>
      <td style="text-align:left">Yes (multiple laps)</td>
    </tr>
  </tbody>
</table>

{% hint style="info" %}
**boostMultiplier:** If you want that the checkpoint reduce the speed of the player you can use this parameter like this:

Example: Reduce player speed by 5% : **boostMultiplier: -0.95**
{% endhint %}

\*\*\*\*


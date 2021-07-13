---
description: Here you will see every information about the command "/ermap"
---

# Command: Ermap

{% hint style="info" %}
Permission: elytraracing.admin
{% endhint %}

Required argument : \[\]  
Optional argument : &lt;&gt;

{% hint style="success" %}
Using commands is for the most of them outdated, and new feature only works with GUI. Recommendation: Use /ermap map \[map\] config \(GUI\).
{% endhint %}

## MapSystem

| Argument | Description |
| :--- | :--- |
| list | List of map |
| create \[map\] | Create a map |
| map \[map\] config | Map configuration |
| map \[map\] show \[on/off\] | Show a map |
| map \[map\] delete | Delete a map |
| map \[map\] cleardb  | Clear saved information |
| map \[map\] setlobbylocation | Define lobby location |
| map \[map\] setstartlocation | Define start location |
| map \[map\] setendlocation  | Define end location |
| map \[map\] tplobby | Teleport to the lobby location |
| map \[map\] tpstart  | Teleport to the start location |
| map \[map\] tpend  | Teleport to the end location |
| map \[map\] setmaxtime \[minutes\] \[secondes\] | Define maximum time possible |
| map \[map\] enable \[on/off\] | Enable or disable a map |
| map \[map\] podium \[on/off\] | Enable or disable a podium  |
| map \[map\] podium tp \[placement 1, 2..\] | Teleport to a podium placement |
| map \[map\] podium setlocation \[placement 1, 2..\] | Define location of a podium placement |
| map \[map\] setdifficulty \[difficulty\] | Define difficulty of a map |
|  |  |

## CheckpointSystem / EndSystem

Command: /ermap map \[map\] \(Arguments\)

| Argument | Description | Checkpoint / End |
| :--- | :--- | :--- |
| listcheckpoint &lt;page&gt; | List of checkpoint | Yes / No |
| listend &lt;page&gt; | List of end | No / Yes |
| addcheckpoint | Create a checkpoint | Yes / No |
| addend | Create a end | No / Yes |
| removecheckpoint \[id\] | Remove a checkpoint | Yes / No |
| removeend \[id\] | Remove a end | No / Yes |
| insertcheckpoint \[id\_wanted\] | Create a checkpoint with a certain id | Yes / No |

Command: /ermap map \[map\] \[checkpoint/end\] \[id\] \(Argument\)

| Argument | Description | Checkpoint / End |
| :--- | :--- | :--- |
| linkto \[id\_other\] | Remove links between | Yes / No |
| removelinkto \[id\_other\] | Remove links between two checkpoints | Yes / No |
| setparticle | Set particle | Yes / Yes |
| setparticle | Set particle \(if next\) | Yes / Yes |
| tp | Teleport to an object | Yes / Yes |
| setXrotation \[rotation\] | Rotation on the X axis | Yes / Yes |
| setYrotation \[rotation\] | Rotation on the Y axis | Yes / Yes |
| setZrotation \[rotation\] | Rotation on the Z axis | Yes / Yes |
| setboostmultiplier \[amount\] | Set boost multiplier | Yes / No |
| setlocation | Define location | Yes / Yes |
| setparticleamount \[amount\] | Set particle amount visible | Yes / Yes |
| setsize \[size\] | Set size | Yes / Yes |


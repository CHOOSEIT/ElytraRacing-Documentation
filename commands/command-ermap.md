---
description: Here you will see every information about the command "/ermap"
---

# Command: Ermap

{% hint style="info" %}
Permission: elytraracing.admin
{% endhint %}

## Map system

### List

{% hint style="info" %}
"/ermap list"

Display every map created
{% endhint %}

{% hint style="success" %}
This command give you more information about each map as validity
{% endhint %}

### Create

{% hint style="info" %}
"/ermap create &lt;map\_name&gt;"

Create a new map instance
{% endhint %}

### Map \(configuration\)

{% hint style="info" %}
* "/ermap map &lt;map\_name&gt; setlocationlobby

  * Set lobby location of your map

*  "/ermap map &lt;map\_name&gt; setlocationstart"

  * Set start location of your map

*  "/ermap map &lt;map\_name&gt; setlocationend**"**

  * Set end location of your map

* " ****/ermap map &lt;map\_name&gt; tplobby"

  * Teleport to the lobby location of your map

* " /ermap map &lt;map\_name&gt; tpstart**"**

  * Teleport to the start location of your map

* " /ermap map &lt;map\_name&gt; tpend**"**

  * Teleport to the end location of your map

*  "/ermap map &lt;map\_name&gt; settimemax &lt;minutes&gt; &lt;seconds&gt;**"**

  * Set the maximum amount of time you can spend on the map

* " ****/ermap map &lt;map\_name&gt; show &lt;on/off&gt;"

  * Show or hide your map \(Checkpoints, ends\)

* " /ermap map &lt;map\_name&gt; enable &lt;on/off&gt;**"**

  * Enable or disable your map

*  "/ermap map &lt;map\_name&gt; podium &lt;on/off&gt;" 

  * Enable or disable podium

*  "/ermap map &lt;map\_name&gt; podium setlocation &lt;placement \(1, 2 ..\)&gt;"

  * Set podium location per placement of your map

* " /ermap map &lt;map\_name&gt; cleardb**"**

  * Clear informations about your map in your database \(records, timeplayed...\)

* "/ermap map &lt;map\_name&gt; delete"
  * Delete map
{% endhint %}

## Checkpoint system

### Map \(checkpoint configuration\)

{% hint style="info" %}
* "/ermap map &lt;map\_name&gt; listcheckpoint &lt;page&gt;
  * List of checkpoints on your map
{% endhint %}

{% hint style="success" %}
Id orders \(&lt;id\_order&gt;\) __needed for the rest of the commands are provided by the list of checkpoint
{% endhint %}

{% hint style="info" %}
* " /ermap map &lt;map\_name&gt; insertcheckpoint &lt;id\_order\_wanted&gt;**"**

  * Add a checkpoint at a certain id\_order

* "/ermap map &lt;map\_name&gt; removecheckpoint &lt;id\_order&gt;"

  * Remove a checkpoint from your map

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; tp"

  *  Teleport to your checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setXrotation &lt;degrees&gt;"

  * Rotate a checkpoint on the X-axis

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setYrotation &lt;degrees&gt;"

  * Rotate a checkpoint on the Y-axis

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setZrotation &lt;degrees&gt;"

  *  Rotate a checkpoint on the Z-axis

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setboostmultiplier &lt;Multiplier&gt;"

  * Set the boostmultiplier of a checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setlocation"

  * Set the location of a checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setsize &lt;size&gt;"

  * Set the size of a checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setparticleamount &lt;amount&gt;" 

  * Set the amount of particle of a checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; linkto &lt;id\_order\_target&gt;" 

  * Link a checkpoint to another \(Links don't pertain to the checkpoint itself but to its id\_order\)

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; removelinkto &lt;id\_order\_target&gt;"

  * Remove a link between 2 checkpoints

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setparticle " 

  * Set particle type of a checkpoint

* "/ermap map &lt;map\_name&gt; checkpoint &lt;id\_order&gt; setparticleifnext"
  *  Set particle type \(if next\) of a checkpoint
{% endhint %}

{% hint style="success" %}
A checkpoint is "ifnext" for a player when the checkpoint is the next one for a player to pass through
{% endhint %}

## End system

### Map \(end configuration\)

{% hint style="info" %}
* "/ermap map &lt;map\_name&gt; listend &lt;page&gt;
  * List of ends on your map
{% endhint %}

{% hint style="success" %}
Id orders \(&lt;id\_order&gt;\) __needed for the rest of the commands are provided by the list of checkpoint
{% endhint %}

{% hint style="info" %}
* "/ermap map &lt;map\_name&gt; addend"

  *  Add an end to your map

* "/ermap map &lt;map\_name&gt; removeend &lt;id\_order&gt;"

  *  Remove an end from your map

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; tp"

  * Teleport to your end

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setXrotation &lt;degrees&gt;"

  *  Rotate an end on the X-axis

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setYrotation &lt;degrees&gt;"

  *  Rotate an end on the Y-axis

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setZrotation &lt;degrees&gt;" 

  * Rotate an end on the Z-axis

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setsize &lt;size&gt;"

  *  Set size of an end

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setparticle" 

  * Set particle type of an end

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setparticleamount &lt;amount&gt;" 

  * Set the amount of particle of an end

* "/ermap map &lt;map\_name&gt; end &lt;id\_order&gt; setparticleifnext"
  *  Set particle type \(if next\) of an end
{% endhint %}




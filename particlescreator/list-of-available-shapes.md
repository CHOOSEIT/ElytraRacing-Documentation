# 📑 List of available shapes

{% hint style="info" %}
Format:&#x20;

\<Key>(Number of parameters for the option associated to the key)

\<Type and explanations of option>
{% endhint %}

### BASE SHAPE

<table><thead><tr><th>Key</th><th>GIF</th><th data-hidden>Description</th></tr></thead><tbody><tr><td>SHAPE_POINT(0)</td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (1) (2).gif" alt=""></td><td>Point</td></tr><tr><td><p>SHAPE_CIRCLE(2)</p><ul><li>Number of point on the circle</li><li>Radius(Decimal)</li></ul><p></p></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (1).gif" alt=""></td><td>Circle</td></tr><tr><td><p></p><p>SHAPE_LINE(2)</p><ul><li>Number of point on the line</li><li>Length</li></ul><p>The line is as default on the x-axis and is centered on the player</p></td><td>NO GIF</td><td></td></tr><tr><td><p>SHAPE_SQUARE(2)</p><ul><li>Number of point on a side</li><li>Length</li></ul><p>Each side is as default on the x-axis and is centered on the player</p></td><td>NO GIF</td><td></td></tr></tbody></table>

### MASK SHAPE



<table><thead><tr><th>Key</th><th>GIF</th><th data-hidden>Description</th></tr></thead><tbody><tr><td><p>MASK_X_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (2) (1).gif" alt=""></td><td>Point</td></tr><tr><td><p></p><p>MASK_Y_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (3).gif" alt=""></td><td></td></tr><tr><td><p></p><p>MASK_Z_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (4).gif" alt=""></td><td></td></tr><tr><td><p>MASK_TRANSLATION(3)</p><ul><li>DeltaX(Decimal)</li><li>DeltaY(Decimal)</li><li>DeltaZ(Decimal)</li></ul></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (1).gif" alt=""></td><td>Circle</td></tr><tr><td>MASK_PLAYERFOLLOW(0)<br><strong>⚠️⚠ Will follow the rotation of the player during the flight ⚠️⚠️</strong><br><strong>Usually used as last mask</strong></td><td><img src="../.gitbook/assets/ezgif.com-gif-maker (5).gif" alt=""></td><td></td></tr></tbody></table>

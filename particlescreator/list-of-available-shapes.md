# 📑 List of available shapes

{% hint style="info" %}
Format:&#x20;

\<Key>(Number of parameters for the option associated to the key)

\<Type and explanations of option>
{% endhint %}

### BASE SHAPE

| Key                                                                                           | GIF                                                       | Description |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ----------- |
| SHAPE\_POINT(0)                                                                               | ![](<../.gitbook/assets/ezgif.com-gif-maker (1) (2).gif>) | Point       |
| <p>SHAPE_CIRCLE(2)</p><ul><li>Number of point on the circle</li><li>Radius(Decimal)</li></ul> | ![](<../.gitbook/assets/ezgif.com-gif-maker (1).gif>)     | Circle      |

### MASK SHAPE



| Key                                                                                                                                                                                                                                                                                 | GIF                                                       | Description |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ----------- |
| <p>MASK_X_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p>        | ![](<../.gitbook/assets/ezgif.com-gif-maker (2) (1).gif>) | Point       |
| <p></p><p>MASK_Y_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p> | ![](<../.gitbook/assets/ezgif.com-gif-maker (3).gif>)     |             |
| <p></p><p>MASK_Z_ROTATION(2)</p><ul><li>Duration of a entire rotation (in milliseconds)</li><li>Angle Are Increasing(true/false/constant)</li></ul><p>⚠️ If the second argument is "constant" then the first argument is not duration but degree angle that will be constant ⚠️</p> | ![](<../.gitbook/assets/ezgif.com-gif-maker (4).gif>)     |             |
| <p>MASK_TRANSLATION(3)</p><ul><li>DeltaX(Decimal)</li><li>DeltaY(Decimal)</li><li>DeltaZ(Decimal)</li></ul>                                                                                                                                                                         | ![](<../.gitbook/assets/ezgif.com-gif-maker (1).gif>)     | Circle      |
| <p>MASK_PLAYERFOLLOW(0)<br><strong>⚠️⚠ Will follow the rotation of the player during the flight ⚠️⚠️</strong><br><strong>Usually used as last mask</strong></p>                                                                                                                     | ![](<../.gitbook/assets/ezgif.com-gif-maker (5).gif>)     |             |

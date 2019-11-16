# ESPHome-RGB-Breathing-Light-Effect

Simply add the code in effect.txt to your effects section of the light in your esphome configuration file of your node and insert the correct id. For finetuning the effect to your liking, refer to the comment in the code.

The breathing works by setting a long transition time and switching between 1% and 100% brightness, this prevents in HA the
displaying a false-positive offtime especially in the logs.
The rgb breathing extends this by setting a new color from a defined list when the brightness is low.



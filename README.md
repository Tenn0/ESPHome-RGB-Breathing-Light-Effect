# ESPHome-RGB-Breathing-Light-Effect

Simply add the code in effect.txt to your effects section of the light in your esphome configuration file of your node.

It works by cycling from allmost off (to prevent displaying a false-positive off state in HA) to full brightness and back to allmost off
and than to the next color and starting all over again.

By changing the update_interval in the effect and the transition_length inside the lambda you can tune the speed of the breathing to your
liking, but i´ve chosen these values to display a smooth breathing with my NeoPixelBus Light.

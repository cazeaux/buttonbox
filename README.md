# Button Box

This project is inspired from <https://www.instructables.com/id/Sim-Racing-Button-Box/>

The arduino sketch proposes a customization which allows to use a rotary button to control windows volume:

* Left: volume down
* Right: volume up
* Push: sound on/off

# Configuration

Configure the mute button and volume rotary in this code section:

```c
// Change this to configure rotary for windows volume and button for volume mute
#define USE_VOLUME 1
#define BUTTON_MUTE 23
#define ROTARY_VOLUME 3
```

Based on the default wiring, the default configuration corresponds to the right rotary (4th rotary from left to right).

# Installation

Compile, upload to your Arduino Micro, enjoy.

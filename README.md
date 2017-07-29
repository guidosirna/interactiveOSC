interactiveOSC
==============

Interactive instrument in Pure Data using [mrpeach](https://github.com/reduzent/pd-mrpeach) and [OSC](http://opensoundcontrol.org/) messages.

This instrument lets you manipulate different sets of sounds (patches) using your smartphone. The movement of your phone sends accelerometer and gyroscope values to the instrument and the sound changes depending on certain values. It also features other controls as sliders and effects.

*Notes: An external application is required in order to send OSC messages.*

Usage
-----

1. Get [pd-extended](https://puredata.info/downloads/pd-extended)

2. Install mrpeach:
```
    $ sudo apt-get update
    $ sudo apt-get install pd-mrpeach
```
3. Open pd-extended and enable DSP

4. Open interactiveOSC.pd

Meta
----
Guido Sirna - [@guidosirna](https://twitter.com/guidosirna) - https://github.com/guidosirna/interactiveOSC

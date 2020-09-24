# micropython-microbit-kitronik-smart-greenhouse
A collection of MicroPython modules for use with the Kitronik Smart Greenhouse Kit (www.kitronik.co.uk/5699)

## Using Modules in Projects
  
To use any of these modules, they first need to be added to the MicroPython project - follow the instructions here:  
https://support.microbit.org/support/solutions/articles/19000106811-adding-a-module-to-the-python-editor  
  
Then, they can be imported in the normal way:  
```blocks
from KitronikZip import *
from KitronikBME280 import *
from kitronikRTC import *
```
  
## What the Modules Do
  
The 'KitronikZip' module contains functions for controlling both the onboard Status ZIP LEDs and an external ZIP Stick - look inside the file for to see how to use them.  
The 'KitronikBME280' module contains functions for using the barometric sensor on the Environmental Control Board, taking Temperature, Pressure and Humidity readings - look inside the file to see how to use them.  
The 'kitronikRTC' module contains functions for controlling the Real Time Clock (RTC) on the Environmental Control Board - look inside the file to see how to use them.  
  
The other features of the Smart Greenhouse, such as the buzzer, servo output, and broken out micro:bit pins can all be controlled using standard micro:bit MicroPython modules (click [here](https://microbit-micropython.readthedocs.io/en/v1.0.1/index.html) to go to the docs).

## CAUTION
  
Although all the functionality of the Smart Greenhouse is controllable with MicroPython, unfortunately, due to the memory limitations of the BBC micro:bit, it is not possible to use all the features at the same time.
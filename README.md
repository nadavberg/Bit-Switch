# Bit Switch 64
Bit Switch is a JSFX audio effect plugin that enables real-time bitwise manipulation of incoming audio samples.
## Features
* Selectively switch individual bits of incoming samples permanently on or off.
* Choose between the following switch modes:
  * Break: Selected switches will send a constant 0 regardless of the input bit
  * Jam: Selected switches will send a constant 1 regardless of the input bit
  * Reversed: Selected switches will send the logical complement of the input bit
* Choose between fixed-point (with or without two's compliment) or floating-point representation 
* View the transfer curve resulting from the selected transformation
* Craft wild and unique bit-crushing distortion effects
* Self-documenting controls directly on the GUI
* Control input and output gain individualy or reverse-linked
## Screenshot
![screenshot](screenshot.webp)
## Installation
* Download `Bit_Switch.jsfx` from this repository
* In the Options menu in REAPER choose "Show REAPER resource path in explorer/finder..."
* Copy the file into the `Effects` folder
* In REAPER's FX browser press `F5` and the plugin should now appear in the JS effects list

## Version 2

**PCB Design:** My first PCB was a lot smaller than I imagined it would be. It is easy to view it from KiCAD in its full-screen mode and not acknowledge or notice that the board is only 63x65 mm. I also had a problem where my temperature sensor pads were too close together, so JCL did not print them out properly. Also, I had my voltage regulator require an inductor of 3.9 uH, and I accidentally ordered an inductor with a 3.9 nH rating. After all of this, I ended up re-ordering from JLC with a new design as well as a new order from Digikey with the proper size inductor, new ESP32, and some more components that I did not order enough of.

**Buttons:** I continuously mess up the orientation of which side of the buttons are connected, so taking my time and correctly orienting the GND and GPIO connections will be another addition to version 2.

**More test points and headers:** Another addition I would make in future renditions would be more headers for debugging and more test points, especially for my GND, 3.3V, and other power rails included.

**Silkscreen:** I accidentally did not include the silkscreen Gerber file with my order to JLC, which would've been helpful for locating which resistors and capacitors need to go where, without having to constantly reference the schematic and PCB CAD.

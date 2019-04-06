# The Arduino and components wire up.

This schematic was made by using the [Fritzing Software](http://fritzing.org/home/)">

## Schematic
 <img src="https://github.com/pu2clr/VFO_BFO_OLED_ARDUINO/blob/master/schematic/vfobfo_schematic_fritzing_image.jpg" alt="VFO and BFO schematic">

### Si5351A

The __Si5351A__ is connected to D2 (SDA) and  D3 (SCL).

### OLED Display SSD1306 - 128 x 64/0.96

The __OLED__ is connected to D2 (SDA) and  D3 (SCL). Yes, the same Si5351A connections.

### Encoder

Connect Arduino __D8__ and __D9__ pins to the __Encoder__ pin __A__ and pin __B__ respectively.

### Push Button Band

Connect Arduino __D0/Rx__ pin to the __Band__ push button.

### Push Button Step

Connect Arduino __D1/Tx__ pin to the __Step__ push button. 

### Push Button VFO/BFO

Connect Arduino __D7__ pin to the __VFO/BFO__ push button.





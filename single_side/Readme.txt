This is single side version of the board. 
-There are significant electrical changes
-12V needs to be distributed by thick jumper wires
-there are two GND bridges marked with red (top layer)
-serial jumper needs GND/power as jumper wires

features:
-large, single sided board designed for direct milling with f.e. "cyclone pcb factory"
-EEB (Extruder, Extruder, Bed) mosfet setup
-pwm on PB4 with bipolar key transistor for fan PWM (bd139)
-additional heater thermistor input
-built-in SD card reader header( for printing with auto0.g)
-removed FDTI - use esp8266 or just TTL serial cable instead, or bt module - designed with old android phone as display in mind
-there is i2c header for display and 3 pins left for encoder in case you Really need old clunky LCD
-additional E1 axis 
-better thermal design, large traces

TODO : 
-schematic needs tidy up actions. 
-untested yet. prints/etches ok with 0.22mm tool. 
-normalize drill sizes

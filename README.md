# bakeOff
"The missing power button for the Raspberry Pi"
Electronic circuit with On/Off button for Raspberry Pi

These are Eagle schematic and layout files for a circuit that plugs in between the RPi 
micro-USB power jack and the power supply. It has a button that when pressed sends a signal 
to the Raspberry pi to start shutting down safely. When it has shut down, power is cut.

Screw terminals allow you to use your own momentary or regular button. Another pair of screw
terminals let you supply other peripherals with power that is cut at the same time as the Raspberry Pi.
You need to run two wires from the board to the Pi - one for the shutdown signal, and one from Tx to 
sense when the Pi has shut down. There are also two jumpered pins where you can measure the current draw of the Pi.

See the project description on Hackaday: https://hackaday.io/project/9885-raspberry-pi-bake-off

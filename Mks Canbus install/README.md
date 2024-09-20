MKS UTC board installed

![image](https://github.com/user-attachments/assets/0e2a3374-86f7-4d57-9550-5de3941bb33b)
Unplug Stepper cable, hot end fans, filament sensor, hotend heater and thermistor, adxl
Connect usb to UTC. Wire Canbus wires. The color only matters that you match with the other end
old harness can be removed, but may lose functionality of internal connector if you have them.
Utc is ziptied and all wires cleaned up. For mine I have the aux cooling fan wired to Fan2 PB5, the carbon filter wired to fan1 PC12, and a chamber temp fan wired to Fan0 PC9 - could be used to hepa filter exhaust. I have a chamber heater and fan wired to the two hot end power connections PC7 and PC8. I have the board cooling fan plugged into VIN and have a buck converter to run it at 5v for noise. Stuck a nylon spacer in the lower middle bolt hole for the bottom panel to make sure the bolt doesnt hit the wires, and a little tape on the corner of the PS incase of rubbing. Unrelated to Canbus, but I also put heatsinks on any flat surface I could see on the board for better cooling performance. 

![image](https://github.com/user-attachments/assets/620b0ca6-5d0e-4a7e-89f3-8760cffb617b)
![image](https://github.com/user-attachments/assets/3b57a0c5-0030-4e96-8d55-c572ee389136)

A bit hard to see but parts fans are plugged into fan 1 and 2
Filament sensor into x-endstop
Can into Can - make sure colors are the ame as on UTC.
Thermistor into temp sensor
Extruder into E-motor
Heatbreak fan into fan 0

I use threaded aluminum standoffs to attach to back of extruder. 18-20mm do the trick with my Sextant extruder. May be different for stock

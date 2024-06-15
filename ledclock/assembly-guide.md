# Clock assembly
Assemble the start, end, digit and colon segments according to the following picture:
![Assembly clock front](ledclock/images/assembly_clock_front.png)
![Assembly clock back](ledclock/images/assembly_clock_back.png)

You can optionally secure the segments with the 3x8mm flat head screws and M3 nuts.

# LED strip wiring
Every 7-segment-digit requires three LEDs. Wire the LEDs in the following way. The arrows on the LED holders give additional guidance
![Assembly electronics_led](ledclock/images/assembly_electronics_led.png)

# Integrate Electronics
Wire the electronics either by the ordering the provided PCB or by the following schematics:
#TODO

# Final Assembly
Mount the LED holders to the digit and colon segments:
![Assembly led](ledclock/images/assembly_led.png)

Install the PCB and the micro USB board in the start segment and wire the pcb with the leds:
![Assembly led](ledclock/images/assembly_electronics_pcb.png)

Close the segments with the back covers and secure them with M3x8 countersunk head screws

# Install Software
Connect the ESP32 via USB and go to [Install](https://l0calgost.github.io/ledclock/) to install the software

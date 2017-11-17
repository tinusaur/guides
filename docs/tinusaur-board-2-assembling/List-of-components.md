# List of components
<!-- add-image: tbd - one with all, one for each -->
<!-- add-content: short description for each component-->

## Main Board Package

1. PCB - Tinusaur PCB
2. Socket, DIP-8 - DIP-8 socket for MCU
3. MCU, Attiny85 - Atmel AVR ATtiny85 microcontroller
4. H1, Header - Header 2×4, Female
5. H2, Header - Header 2×5, Female
6. R1, Resistor - Resistor 10K, Small, 1/8W
7. C2, Capacitor - Capacitor 100uF, Low profile 5×5 mm
8. C1, Capacitor - Capacitor 100nF, Small
9. Power, Header - Header 1×2, Female, for external power
10. Battery, Header - Header 1×2, Male, for internal battery on/off (put the cap on)
11. Battery, Jumper - Jumper, 2-pin, for battery power on/off
12. ISP, Header - Header 2×5, Male, Shrouded, for ISP / USBasp
13. Battery holder - Battery holder for CR2032 battery
14. RESET, Button - Tactile push button, for RESET
15. Battery 3V - Battery 3V, CR2032


## Usb Controller
<!-- terminology-edit: programmer vs. controller -->

Use the USB 2.0 Controller to connect the Tinusaur board to a PC or a Mac for testing and programming the main board.

<!-- structure-edit: move specific project packages to separate files -->
## Blinking LED Project Package

1. Shield, PCB - Shield LEDx2 PCB
1. H1, Header - Header 2×2, Male   (1)
1. H2, Header - Header 2×5, Male
1. LED1, LED - LED, 3mm, red
1. LED2, LED - LED, 3mm, green
1. Resistor (LED1) - Resistor 330 ohm, Small, 1/8W, for LED   (2)
1. Resistor (LED2) - Resistor 330 ohm, Small, 1/8W, for LED   (2)

## Led and Buzzer Project Package

1. Shield, PCB - Shield EDUx4IO PCB
1. H1, Header - Header 2×4, Male    (1)
1. H2, Header -	Header 2×5, Male
1. LED1, LED - LED, 3mm, red
1. PHR1, Photoresistor - Photoresistor
1. R (LED1)	- Resistor 330 ohm, Small, 1/8W, for LED1  (2)
1. R (PHR1)	- Resistor 10K, Small, 1/8W, for PHR1  (2)
1. BUZ, Buzzer - Buzzer, passive
1. BUT, Button - Button, pushbutton, tactile.



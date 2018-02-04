# List of Components


## Main Board Bag
The components are listed in the order, in which they are assembled.

### 1. Tinusaur printed circuit board (PCB)

A board made of non-conductive material on which you mount and solder the components to connect them together, so that they form a working circuit. The Tinusaur PCB is designed to do specific jobs. The design of the PCB is described in a schema that you can use to identify where to mount each component. Look for the schema card in your Tinusaur box.
<!--image-add: a photo of the board-->

### 2. Socket, DIP-8

A socket is a placeholder for the microcontroller (MCU) that connects the MCU to the board. Because the MCU is sensitive to heat and could get damaged during soldering, the socket makes it easy to plug the MCU in and out. DIP stands for "Dual Inline Package", which is an integrated circuit package with two rows of pins. 8 is the number of the pins.
<!--image-add: a photo of the socket-->

### 3. H1, Header, 2×4, female

A rectangular connector with 2 rows of 4 holes.
<!--image-add: a photo of the header-->

### 4. H2, Header, 2×5, female

A rectangular connector with 2 rows of 5 holes.
<!--image-add: a photo of the header-->

### 5. R1, Resistor

A resistor is an electrical component that limits or regulates the flow of electrical current in the internal circuit. This resistor is small and its value is 10k (10,000) ohms. See [Identifying the Value of a Resistor](https://github.com/tinusaur/guides/blob/master/docs/tinusaur-board-2-assembling/Identifying-value-resistors.md).
<!--what will be the rule for numbers - in the Resistor section the figures are 10 000 and 10000, I think 10,000 is best--> 

The power rate of the resistor is 1/8W (watts), meaning that it can handle this much electricity power before it overheats.
<!--image-add: a photo of the resistor-->

### 6. C2, Electrolytic capacitor

A capacitor gets charged with electricity from the circuit and can discharge that electricity in quick outbursts as required. This capacitor can store 100uF (nanofarads) of electricity. It is 5×5 mm in size, with low profile (not too thick).
<!--image-add: a photo of the capacitor-->

### 7. C1, Capacitor
A small capacitor that can store 100nF (nanofarads) of electricity.
<!--image-add: a photo of the capacitor-->

### 8. Power, Header, 1×2, female

A rectangular connector with 1 row of 2 holes, in which you can plug in an external power source for the Tinusaur PCB.
<!--image-add: a photo of the header-->

### 9. Battery, Header 1×2, male

A rectangular connector with 1 row of 2 pins, to which you connect the battery jumper, so that you can turn on/off the internal battery.
<!--image-add: a photo of the header-->

### 10. Battery, Jumper, 2-pin

A battery jumper turns on the internal battery, when you cover both pins of the battery header with the jumper. If you cover just one of the pins, the internal battery is turned off.
<!--image-add: a photo of the jumper-->

### 11. ISP, Header, 2×5, male, shrouded

A rectangular connector with 2 rows of 5 pins, to which you connect the ISP/USBasp cable. This header is shrouded (with a plastic box around the pins) and has a notch key (small opening on one of the sides) to prevent you from placing the header the wrong way around.
<!--image-add: a photo of the header-->

### 12. Battery holder

A holder, in which to insert a CR2032 battery.
<!--image-add: a photo of the holder-->

### 13. RESET button

A push button for resetting the PCB board.
<!--image-add: a photo of the button-->

### 14. Battery 3V

A CR2032 battery of 3V that is the internal power source for the Tinusaur PCB.
<!--image-add: a photo of the battery-->

### 15. MCU, ATtiny85

"Atmel AVR ATtiny85" is the "family name" of the microcontroller (MCU) that you connect to the Tinusaur PCB and program to do specific tasks. Think of it as the brain of the operation that can get a light-emitting diode (LED) to turn on and off.
<!--image-add: a photo of the microcontroller-->

## USB Programmer

Use the USB 2.0 programmer to connect the Tinusaur PCB to a PC or a Mac for testing and programming the main board.

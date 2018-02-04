# Writing Your First Tinusaur Program
1. In the Arduino IDE, create a new file.

2. On the first line of your file to declare a constant for the red LED on the Tinusaur board:
```
int LED_RED = 0;
```
This constant tells the program that the red LED is on pin 0. You will also use this constant to switch the LED on and off.

3. On a new line, declare a constant for the green LED, too:
```
int LED_GREEN = 1;
```
This constant tells the program that the green LED, on pin 1.

4. Leave an empty line after the constant declarations, and on the next line write:
```
 void setup(){}
``` 
When the prorgam starts, the setup function will run once. The function is now empty and does nothing.

5. To get the setup funtion to work for the red LED inside the curly brackets {} type: 
```
pinMode(LED_RED, OUTPUT);
```

6. To get the setup function to work for the green LED, inside the curly brackets, below the line where you just wrote, type:
```
pinMode(LED_GREEN, OUTPUT);
```
pinMode is the function that configures the LED pins on the Tinusaur board. We pass the following arguments to the pinMode function and the arguments tell the program:
- configure this LED (LED_COLOR)
- direct the electricity current through the led (OUTPUT)

```
int LED_RED = 0;
int LED_GREEN = 1;

void setup() {
	pinMode(LED_RED, OUTPUT);
	pinMode(LED_GREEN, OUTPUT);
}
```

7. Now that we have our LEDs configured, we can write a function to make them blink.
The loop function will get executed repeatedly. This means that the leds will blink until you break the circuit, or run out of battery.

```
int LED_RED = 0;
int LED_GREEN = 1;

void setup() {
	pinMode(LED_RED, OUTPUT);
	pinMode(LED_GREEN, OUTPUT);
}

void loop() {
	digitalWrite(LED_RED, HIGH);
	digitalWrite(LED_GREEN, LOW);
	delay(500);
	digitalWrite(LED_RED, LOW);
	digitalWrite(LED_GREEN, HIGH);
	delay(500);
}
```

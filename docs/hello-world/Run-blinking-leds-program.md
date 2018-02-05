# Run Blinking Leds Program
1. Plug the USB programmer into a USB port on your computer.
2. Connect the Tinusaur board to the USB programmer.
3. On the Tinusaur board, connect a LED to PB0 with a 330 ohm resistor in series.
4. Start the Arduino IDE.
5. Copy the following code into the Arduino IDE editor: 
```
>int led = PB0;
void setup() {
    pinMode(led, OUTPUT);    // Set the LED port as output
}
void loop() {
    digitalWrite(led, HIGH); // turn the LED on
    delay(200);              // wait for a while
    digitalWrite(led, LOW);  // turn the LED off
    delay(200);              // wait for a while
}
```
3. Click the **Upload** button to compile and run the code.

![](https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/Code-Sample02.JPG)

The program starts running immediately after the upload is finished, which causes the LED to start blinking rapidly.   
See also [Saving the Tinusaur Board Internal Battery](https://github.com/tinusaur/guides/blob/master/docs/hello-world/saving-internal-battery.md)

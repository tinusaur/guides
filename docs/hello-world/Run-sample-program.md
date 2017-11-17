# Run a Sample Program

## Run a Test Program 

Prerequisites: 
+ The USB programmer must be plugged in a USB port on your computer.
+ The board must be connected to the USB programmer.

1. Start the IDE.
2. Copy the follwing code to the IDE editor: 
```
>void setup() {
}
void loop() {
}
```
3. Click the **Upload** button to compile and run the code.
![](https://github.com/tinusaur/guides/blob/master/docs/images/Code-Sample01.JPG)

Note: This process should finish without any errors. The program does not do anything

## Run a Blinking LED Program

Prerequisites: 
+ The USB programmer must be plugged in a USB port on your computer.
+ The board must be connected to the USB programmer.
+ The board must have a LED connected to PB0 with a 330 ohm resistor in series.

1. Start the IDE.
2. Copy the follwing code to the IDE editor: 
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

The program starts running immediately after the upload is finished and the LED start rapidly blinking rapidly.


**Note:** If the battery is installed and the battery jumper is connected, the program will continue running even if you disconnect the cable from the USB programmer.

### To stop the program from running:
1. Disconnect the cable from the USB programmer;
2. Remove the battery jumper to disconnect the power from the battery;

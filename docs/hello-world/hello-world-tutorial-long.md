# Hello World from a Tinusaur Board
## Writing your first Tinuasur program
After you install the Arduino IDE and driver and add the tinusaur board to IDE, you can create your first project.
1. In the Arduino IDE, create a new file.
2. On the first line of your file enter:
int LED_RED = 0;
This will declare a new constant. This constant corresponds to the red LED on your Tinusaur bord, and tells the program that the red LED is on pin 0. You will further use this constant to switch the LED on and off.
3. Now you have to declare a constant for the green LED, too. After the ;, hit anter and write:
int LED_GREEN = 1;
This is your green LED, on pin 1.
4. Leave an empty line after the constant declarations, and on the next line write:
 void setup(){}
This will define your first function. The setup function will run once, when your program starts. So far, the function is there but is empty - and it does not do anything.
Let's get our setup function to work! Click between the curly brackets {}, hit enter, and write:
pinMode(LED_RED, OUTPUT);
5. Inside the curly brackets, below the line where you just wrote, enter the following:
pinMode(LED_GREEN, OUTPUT);
What we just did is insert two other functions inside our setup function. Each of the new functions is called pinMode, and we use them to configure the LED pins on the Tinusaur board. To make it work, we pass the following arguments to each of the functions:
LED_COLOR - this argument tells the program which LED pin to configure.
OUTPUT - this argument configures the pin as OUTPUT, which allows the program to send current to the pin that can light up the LED.
If you followed the steps correctly, you should see the following code in your file:

int LED_RED = 0;
int LED_GREEN = 1;

void setup() {
	pinMode(LED_RED, OUTPUT);
	pinMode(LED_GREEN, OUTPUT);
}

4. Now that we have our LEDs configured, we can write a function to make them blink.
7 write loop ()... this will add a loop function to your program
loop function execute repeatedly. this means the led willl blink until you break the circuit, or run out of battery ;


Full code:

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
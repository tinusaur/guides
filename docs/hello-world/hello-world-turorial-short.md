# Writing Your Code


After you have installed the USBasp driver and you have deployed the Arduino environment, you can start writing your first program.


1. Create a new file.
2. Write the line:
`int LED_RED = 0; `
It declares the variable *LED_RED* as an integer with a constant value of *0*.
2. Write the line:
`int LED_GREEN = 1; `
It declares the variable *LED_GREEN* as an integer with a constant value of *1*.
2. Write the line:
`void setup () {`
It sets up a function that will run once for the variables you will write in the next lines.
2. Write the line:
`pinMode (LED_RED, OUTPUT);`
It defines the variable *LED_RED* for the red led on your Tinosaur board as an output.

3. Then, write the line:
`pinMode (LED_GREEN, OUTPUT); }`
It defines the variable *LED_GREEN* for the green led on your Tinosaur board as an output.

4. The line:
`void loop () {`
Sets up a function that runs repeatedly until you interupt the circuit.
5. Write the line:
`digitalWrite (LED_RED, HIGH);`
This function turns the red led *LED_RED* on.

6. Write the line:
`digitalWrite (LED_GREEN, LOW);`
This function turns the green led *LED_GREEN* off.

7. Write the line:
`delay(500);`
This function creates a delay in time for a period of 500 milliseconds.

5. Write the line:
`digitalWrite (LED_RED, LOW);`
It turns the red led *LED_RED* off.

6. Write the line:
`digitalWrite (LED_GREEN, HIGH);`
It turns the green led *LED_GREEN* on.

7. The line:
`delay(500); }`
Creates a delay in time for a period of 500 milliseconds.

7. Save the file.
8. Click the first icon from the toolbar or upload the file. It will trigger a verificaion of your code. 



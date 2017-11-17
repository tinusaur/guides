# Writing Your Code


After you have installed the USBasp driver and you have deployed the Arduino environment, you can start writing your first program.


1. Create a new file.
2. Write the line:
`int LED_RED = 0; ` <br />
It declares the variable *LED_RED* as an integer with a constant value of *0*.

2. Underneath, write the line:
`int LED_GREEN = 1; ` <br />
It declares the variable *LED_GREEN* as an integer with a constant value of *1*.

2. The next line:
`void setup () {`<br />
Sets up a function that will run once for the variables you will write in the next lines.

2. Write the line:
`pinMode (LED_RED, OUTPUT);`<br />
It defines the variable *LED_RED* for the red led on your Tinosaur board as an output.

3. Then, write the line:
`pinMode (LED_GREEN, OUTPUT); }`<br />
It defines the variable *LED_GREEN* for the green led on your Tinosaur board as an output.

4. The line:
`void loop () {`<br />
Sets up a function that runs repeatedly until you interupt the circuit.

5. Write the line:
`digitalWrite (LED_RED, HIGH);`<br />
This function turns the red led *LED_RED* on.

6. Write the line:
`digitalWrite (LED_GREEN, LOW);`<br />
This function turns the green led *LED_GREEN* off.

7. Write the line:
`delay(500);`<br />
This function creates a delay in time for a period of 500 milliseconds.

5. Write the line:
`digitalWrite (LED_RED, LOW);`<br />
It turns the red led *LED_RED* off.

6. Write the line:
`digitalWrite (LED_GREEN, HIGH);`<br />
It turns the green led *LED_GREEN* on.

7. The line:
`delay(500); }`<br />
Creates a delay in time for a period of 500 milliseconds.

Your final code, with additional formatting, should look like this:

```
int LED_RED = 0;
int LED_GREEN = 1;

void setup () {
  pinMode (LED_RED, OUTPUT);
  pinMode (LED_GREEN, OUTPUT); 
}
void loop () {
  digitalWrite (LED_RED, HIGH);
  digitalWrite (LED_GREEN, LOW);
  delay(500);

  digitalWrite (LED_RED, LOW);
  digitalWrite (LED_GREEN, HIGH);
  delay(500);
}
```

7. Save the file.
8. Click the check icon from the toolbar or upload the file. It will trigger a verificaion of your code. 



# Installing Arduino IDE on Windows 

Arduino is an open-source electronics platform, based on easy-to-use hardware and software. It is intended for coding interactive projects.
[Learn More](https://www.arduino.cc/en/Guide/Introduction)

## Installing Arduino IDE

1. Log on Windows as Administrator. 
2. From the Arduino official website https://www.arduino.cc/en/Main/Software, download the Arduino IDE for your Windows version.
3. Start the Arduino IDE.
<!-- screenshot of Arduino IDE-->


## Adding Support for the Tinusaur Boards
Add the Tinusaur printed circuit board (PCB) to the Arduino environment as follows. 

1. In the Arduino IDE, select **File > Preferences**, and click **Additional Boards Manager URLs**.
2. Enter the following URL to add the Tinusaur board to the Arduino IDE:    
https://bitbucket.org/tinusaur/arduino-ide-boards/raw/default/package_tinusaur_attiny_index.json   
**Tip:** You can add multiple URLs by separating them on a new line.    

![](https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_05_c700x700_cropped.png)
    
3. Click **OK**.

4. In the Arduino IDE, select **Tools > Board:_board_name_here > Boards Manager**.

<!-- pic Arduino IDE Boards Manager -->
5. From the **Type** drop-down menu, select **Contributed**, and then **Tinusaur Boards**.    

![](https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_10_c700x644.png)
     
6. Click **Install**.

## Setting up Arduino for the Tinusaur Board
Select the components of the Tinusaur board to use in Arduino.
1. In the Arduino IDE, select **Tools > Board:...**, and then from the boards list select **Tinusaur**.
<!--Arduino IDE Tinusaur Board-->
2. From **Tools > Processor:...**, select the CPU type of the Tinusaur board.    
If you do not know the processor of your board, select **ATtiny85**.
<!--Arduino IDE Tinusaur Board CPU-->      

![](https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_18_c700x640.png)   
       
3. From **Tools > Clock:...**, select the CPU frequency.   
If you do not know the ferquency of the processor, select **1 MHz**.
<!--Arduino IDE Tinusaur Board Frequency-->
4. From **Tools > Programmer:...**, select the appropriate programmer.   
If you do not know the programmer, select **USBasp**.
<!--Arduino IDE Tinusaur Board USBasp-->

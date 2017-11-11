##Installing the Arduino IDE on a Windows OS 

Arduino is an open-source electronics platform based on easy-to-use hardware and software. It's intended for anyone making interactive projects.
(https://www.arduino.cc/en/Guide/Introduction "Learn More about Arduino")

######Software Requirements: 
* Windows 7 32-bit
* Windows 7 64-bit
* Windows 10 32-bit
* Windows 10 64-bit

######Prerequisites:
* Verify you can log in to the Windows OS as an Administrator. 

######Procedure:

1. From the Arduino official Web site https://www.arduino.cc/en/Main/Software, download the the Arduino IDE<!-- for your host operating system-->.

2. Start the Arduino IDE.
<!-- screenshot of Arduino IDE-->


###Adding Support for the Tinusaur Boards

1. In the Arduino IDE, select **File > Preferences**, and click the **Additional Boards Manager URLs** text box.
The Additional Boards Manager URLs dialog box opens.
3. Enter the following URL to add the Tinusaur board to the Arduino IDE, and click OK:
https://bitbucket.org/tinusaur/arduino-ide-boards/raw/default/package_tinusaur_attiny_index.json
**INFO:** You can add multiple URLs by separating them on a new line.
https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_05_c700x700_cropped.png
4. Click **OK** to close the Preferences wizard.
<!-- pic Arduino IDE adding board URL -->
5. In the Arduino IDE, select **Tools > Board:_board_name_here > Boards Manager**.
The Arduino IDE Boards Manager dialog box that contains information about the boards opens.
<!-- pic Arduino IDE Boards Manager -->
6. From the **Type** drop-down menu, select **Contributed**, and select **Tinusaur Boards**.
<!--Arduino IDE Contributed Boards-->
https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_10_c700x644.png
7. Click **Install**, and close the window when the installation completes. 
You completed installing the Arduino IDE on you Windows system.

###Setup the Arduino for the Tinusaur Board

1. In the Arduino IDE, select **Tools > Board:...**, select the **Tinusaur** board from the bottom of the boards list.
<!--Arduino IDE Tinusaur Board-->
2. Verify the correct components for the Tinusaur board are selected.
3. From **Tools > Processor:...**, select the CPU type of the Tinusaur board.
If you do not know the processor of your board, select **ATtiny85**.
<!--Arduino IDE Tinusaur Board CPU-->
https://github.com/tinusaur/guides/blob/master/docs/hello-world/images/201603311827_setupboards_18_c700x640.png
4. From **Tools > Clock:...**, select the CPU frequency.
If you do not know the ferquency of the processor, select **1 MHz**.
<!--Arduino IDE Tinusaur Board Frequency-->
4. From **Tools > Programmer:...**, select the appropriate programmer.
If you do not know the programmer, select **USBasp**.
<!--Arduino IDE Tinusaur Board USBasp-->
You completed the setup of the Arduino IDE for the Tinusaur Board.

Enjoy!

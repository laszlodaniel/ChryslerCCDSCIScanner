1. Download and install/unpack the following:
* latest Arduino IDE from https://www.arduino.cc/en/Main/Software
* latest GitHub update from https://github.com/laszlodaniel/ChryslerCCDSCIScanner/archive/master.zip

2. Go to the Arduino IDE installation directory and create a new directory called "Arduino". Copy the content of the "Arduino" folder inside the GitHub zip file to this location 

3. Start the Arduino IDE and go to File / Preferences

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_01.png)

4. Make sure that the Sketchbook location is the "Arduino" directory that you have just created

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_02.png)

5. Go to Tools and make changes to the Board / Processor / Port setting as shown

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_03.png)

6. In case of multiple COM-ports head to the Device Manager and look for a Port using CP210X as bridge and note the COM-number

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_04.png)

7. Make sure that the Board settings are reflected correctly on the bottom of the window and open the scanner sketch from File / Sketchbook / ChryslerCCDSCIScanner

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_05.png)

8. Click the "Verify" button on top of the window to check for code errors in case you make changes

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_06.png)

9. "Done compiling" means the code is okay and can be uploaded to the scanner

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_07.png)

10. Click the "Upload" button on top of the window to verify once more and upload the code to the scanner

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_08.png)

11. "Done uploading" means the code is successfully uploaded to the scanner

![alt tag](https://raw.githubusercontent.com/laszlodaniel/ChryslerCCDSCIScanner/master/Arduino/GettingStarted/arduino_setup_09.png)
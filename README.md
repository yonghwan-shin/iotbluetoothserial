iotbluetoothserial
IoT Core Generic Bluetooth Serial Universal Windows App

Updates:
- Version 1.2 One bug fix (was writing send twice), one code improvement (menu returns DeviceInformation so no need to relookup).


Project Description

This project is discussed indetail on embedded101.com:
http://embedded101.com/Blogs/David-Jones/entryid/707/Win-10-Iot-Core-Bluetooth-Universal-Windows-Serial-App-

 Universal Win App that runs on Windows 10, including IoT Core (eg Raspberry PI2) that connects to an embedded, eg Arduino, device over Bluetooth Serial.

 There are two projects: The Universal Windows App that requires Windows 10 and Visual Studio 2015 RTM. Requires a generic Bluetooth dongle. I use a very old CSR V1.1 version .. but it works!

The Arduino serial loopback Sketch. 

The Arduino device requires a Bluetooth adapter connected to pins 0 and 1 as the code uses the Serial class. I used a Sparkfun Bluetooth Mate Gold as in  Windows-10-IoT-Windows-Remote-Arduino-and-Universal-Windows-Platform (See http://embedded101.com/Blogs/David-Jones/entryid/636/Windows-10-IoT-Windows-Remote-Arduino-and-Universal-Windows-Platform-Apps)


Note: This IS NOT a Windows Remote Arduino activity.+  
 
 


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/djaus2/iotbluetoothserial/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


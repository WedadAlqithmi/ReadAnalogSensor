# ReadAnalogSensor

for this task all i need was: 
- arduino UNO
- BreadBoard
- 3 wires 
- analog sensor << i used light sensor you can use any analog sensor 


## Steps: 

connect the senor into the bread board 

connect the resistor along with the sensor 

Connect the red wire along to the first terminal of the sensor and connect it to the 5v port in the ardunio UNO 

Connect the black wire along to the second terminal of the sensor and connect it to the GND port in the ardunio UNO 

connect the yellow wire into the (A0) port in arduino and connect to the same line where the sensor and resistor are 

check the images to get a clear look


![WhatsApp Image 2022-08-03 at 8 01 32 PM (1)](https://user-images.githubusercontent.com/108210044/182673852-ebd86b44-505c-4fe5-9d7c-1eaa9eef7200.jpeg)
![WhatsApp Image 2022-08-03 at 8 01 32 PM](https://user-images.githubusercontent.com/108210044/182673865-7ced3b1d-70b0-4ec5-8bde-fcb1fe95766a.jpeg)


connect the UNO to your PC 
and upload the arduino code to read the signals, then print it to the serial monitor 

The command responsible for reading the signals is 

```
analogRead(A0);

```

make sure that the baud rate is the same value of 
``` 
serial.begin(00000);
``` 






https://user-images.githubusercontent.com/108210044/182671349-6a6a2989-ae50-4a30-a97c-88757b3a5360.mp4


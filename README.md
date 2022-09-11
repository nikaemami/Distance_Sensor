# Distance_Sensor
Implementation of a GP2Y0A700K0F distance measuring sensor in STM32.

I connected the sensor to a voltage source of 5 volts. The final design is as below:

![My Image](images/IMG_4949.jpg)

By connecting a voltmeter to the output of the sensor, I measured the output of the sensor in enough points in the range of its possible input values. The results are shown in the table below:

![My Image](images/IMG_4950.jpg)

By using the above dataset in MATLAB cftool, I found the regression line corresponding to the dataset:

![My Image](images/IMG_4951.jpg)

By using this equation I was able to write a program to measure the distance in centimeters and print the result on an lcd display connected to the STM32 microcontroller.



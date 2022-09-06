# Distance_Sensor
Implementation of a GP2Y0A700K0F distance measuring sensor in STM32.

I connected the sensor to a voltage source of 5 volts, then by connecting a voltmeter to the output of the sensor I filled out the table below.

The results are as follows:

By using the above dataset in MATLAB cftool, I found the regression line corresponding to the dataset. 

By using this equation I was able to write a program to measure the distance in centimeters and print the result on an lcd display connected to the STM32 microcontroller as below:

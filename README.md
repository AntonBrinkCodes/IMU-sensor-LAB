# IMU-sensor-LAB
IMU Sensor lab for the Course CM2000. Filter and gyroFilter functions written by me from lab instructions.
All other functions given as part of lab and written by course lecturer Jonas Willén.

The purpose of this lab is using an EWMA filter and other filtering techniques to get usable data from a PolarSense IMU. The code is written in Javascript. The functions to receive and display the IMU data were provided to us and only the code under gyroFilter() and filter() (as well as some global variables) are written by me, following the lab instructions. The whole code can be seen in the github repository linked in Appendix A. 

The IMU sensor has an accelerometer, gyroscope and magnetometer. In this lab I will only use the accelerometer and gyroscope.

The primary lab tasks were: 
To detect the cadence the IMU is being shaken in using accelerometer data, 
To display the roll using a combination of accelerometer and gyroscope data. 
Secondary lab tasks were:
Creating code to detect if the IMU has been continually shaking for >1 second.
Displaying pitch and yaw by also using magnetometer data.
Applying a Kalman filter to the roll calculations.

Of the secondary lab tasks we could choose one or several to complete. I chose to detect if the IMU has been continually shaking for >1 second.

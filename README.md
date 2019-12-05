# Drone
Drone with arduino 
First of all the requirements are; 
1)F450 quadcopter frame 
2)Arduino 
3)MPU-6050
4)Lipo battery 11.1V 3cell
5)30A esc for brushless engine * 4
6)Brushless engine *4
7)2.4Ghz Receiver and 2.4Ghz 6 channel controller  
Now open the general schematics this is the general circuit, you can find fritzing file in drone control schematics. When connection is done the drone will not work since arduino doesnt include the code.
MPU-6050 has to stay steady because it will give the most necessary data which is loocation of drone in x y z axis. Actually this is an accelerometer and gyroscope. Attaching it with double sided tape will make things easy also be sure that it is flat otherwise you should read the values when the drone is steady and you have to give offset. Such as then you put the drone in flat place and when you connect your arduino to your computer, read the values from mpu-6050, you can find the code in 'read values from mpu-6050'. Upload the code to the arduino and open the serial port screen in arduino code page. If you see the values as 0 in every axis its perfect otherwise you have to give offset but its easy you can find hoe to do in the code. 
After done this you have to upload the codes but in order. You can find the codes in 'codes' part. Fist open the 'ymfc-al-setup'  do the setup but fist you have to read the code to understand what are you doing and what are you going to do.

What's inside this version? There are now 7 modes!

Mode 0 - The magnetometer Moire Pattern. Shows Heading and Field Strength

Mode 1 - LUX. This displays the numeric value as well as a circular guage as lux increases. I've measured direct sublight but the max value is something like 400lux.

Mode 2 - Colorimeter (Lamda). On this version, the white LED only comes on when the proximity sensor detects an object about 1cm away.

Node 3 - dB meter. This has a cool "RADAR" look and dBs are shown as red dots.

Mode 4 - ENV (atm pressure, altitude, temp, humidity, heat index, CO2, and TOV). Default screen is blue and text is white. When the Handheld is connected via Bluetooth, the TOV and CO2 turn green. All sensors on this screen have a threashold, so that if any of them are within a *warning*, the screen turns yellow. When the threshold is too high *Danger*, the screen turns red.

Mode 5 - Ricci Scalar Flied (simulated).

Mode 6 - MLX90640 heat camera with Garmin LIDAR Lite v4 distance. Shows the heat map with a minimum and maximum temperature, as well as the distance to the object (up to 7m tested). 

Mode 7 - LINDAR distance. In theory, the Garmin LIDAR Lite v4 can measure up to 10m. But with my tests, both inside and out, I could only get a solid reading at around 7.5m. Your milage may vary, as my unit is over 4 years old. 



***NOTE***

There were many issues with getting this to work in the Tricorder sketch. the two main library files, LIDARLite_v4LED.cpp and LIDARLite_v3HP.cpp have been modified. I've included all the library files for the LIDAR just in case, but you should only have to upload the two mentioned.

I DID NOT include the library files for all the other includes, but those were never modified by me, so your ArduinoIDE should handle those with no issues.


Again, please feel free to fork this for your own use and let me know if you do, as I would love to try it out on my rig!

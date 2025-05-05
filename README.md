What's inside this version? There are now 7 modes!

Mode 0 - The magnetometer Moire Pattern

Mode 1 - LUX 

Mode 2 - Colorimeter

Node 3 - dB meter

Mode 4 - ENV (atm pressure, altitude, temp, humidity, heat index, CO2, and TOV)

Mode 5 - Ricci Scalar Flied (simulated)

Mode 6 - MLX90640 heat camera with Garmin LIDAR Lite v4 distance

Mode 7 - LINDAR distance



***NOTE***

There were many issues with getting this to work in the Tricorder sketch. the two main library files, LIDARLite_v4LED.cpp and LIDARLite_v3HP.cpp have been modified. I've included all the library files for the LIDAR just in case, but you should only have to upload the two mentioned.

I DID NOT include the library files for all the other includes, but those were never modified by me, so your ArduinoIDE should handle those with no issues.


Again, please feel free to fork this for your own use and let me know if you do, as I would love to try it out on my rig!

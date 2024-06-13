How to set zones in Home Assistant with the LD2410 Series of mmWave Sensors

I often have people ask me how to set the zones up for the LD2410 series of mmWave presence sensors. Here are the steps i came up with to do that.

Step 1: Measure the distance from the sensor to where you want zone 1 to end. Also do the same for zone 2 and zone 3.

Step 2: In Home Assistant go to the sensors configuration page and scroll down until you find the configurations you see below.

Step 3: In the Radar End Zone 1 box type in the measurement you made for zone 1. This is in centimeters so if you measured in inches convert the measurement first.

Step 4: Repeat step 3 for zone 2 and zone 3.

Step 5: Adjust the Radar max Move and Radar max Still distances to match the end of zone 3 or where ever you want the detection to end. Keep in mind that this measurement is in meters so again convert your measurements to meters. The max is 8 meters.

Step 6: Repeat steps 1 through 5 for your other sensors.

##Orenco Robotics 2016

###Color Sensor Guide

**Goal**: Provide guidance to team members wanting to efficiently use the color sensor

####Fun Facts
* Detects seven colors: black, blue, yellow, red, green, white, and brown. 
* Detects Light intensity, is measured from 0 to 100 (very dark to very light). The sample rate of the color sensor is 1 kHz/sec.

####Modes of Operation
Three modes of operation:
1. Color mode - Returns true (present) or false (not present for one or more of the seven colors.
2. Reflected Light Intensity mode - measures the amount of light reflected back from a red lamp on the senor
3. Ambient Light Intensity mode - measures the amount of light entering the sensor from the environment

####Calibration

####Programming Tips

####Tips and Tricks

####Known Gotchas
* The sensor must be held in close proximity (but not touching) and at a right angle to the surface being measured. Light from the environment can affect measurements and care should be taken to shield the sensor from these effects in Color mode or Reflected Light mode.

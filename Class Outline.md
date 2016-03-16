##Spring Robotics Class Outline

Spring Robotics is a multi day course taught over the period of 11 weeks to students between the ages of 8 and 12. The primary goal of the course is to strengthen the students' understanding of LEGO robotics and FLL concepts in anticipation for 2016/17 FLL season.

###Course Materials for SpringRobotics

*	[Riley Rover](http://www.damienkee.com/home/2013/8/2/rileyrover-ev3-classroom-robot-design.html) (built from the [LEGO Mindstorms Education Kit](https://shop.education.lego.com/legoed/en-US/search/navSearchResults.jsp?categoryId=EDU_PRD_LINE_107&ProductLine=MINDSTORMS+Education+EV3))
*	iPads, Low Power Laptop or Desktop Computers
*	EV3 Code Included in this Repository
*	Research Templates Included in this Repository
*	iDevice with the GooseChase software installed

###Course Outline

####Week One
**Goals**: Introduce the color and ultrasonic sensors and solve a challange using the two devices.

**Programs**

1.	
2.	
3. 	

**Session Guide**

1.	The week will have two GooseChase tracks; one each for the ultrasonic sensor and color sensor. Each GooseChase challenge will demonstrate sensor modality, sensitivity, modes of operation, and a list of gotchas.
	* Color Sensor
		* Modality - Light
		* Sensitivity - Detects light intensity and seven colors: black, blue, yellow, red, green, white, and brown. Light intensity is measured from 0 to 100 (very dark to very light). The sample rate of the color sensor is 1 kHz/sec.
		* Modes of Operation - Color mode will return true (present) or false (not present) for one or more of the seven colors. Reflected Light Intensity mode measures the amount of light reflected back from a red lamp on the sensor. Ambient Light Intensity Mode measure the amount of light entering the sensor from the environment.
		* Gotchas - The sensor must be held in close proximity (but not touching) and at a right angle to the surface being measured. Light from the environment can affect measurements and care should be taken to shield the sensor from these effects in Color mode or Reflected Light mode.
	* Ultrasonic Sensor
		* Modality - Sound
		* Sensitivity - Range 3cm to 250cm (1" and 99"). Reading of 255cm (100") means that the sensor is not able to detect any object in range.
		* Modes of Operation - Measure mode will measure the distance to an object. Presence mode will detect the signal from a second US Sensor.
		* Gotchas - The sensor is less effective in detecting surfaces with "soft" surfaces or hard surfaces that are sharply angled. Both conditions will reduce the amount of sound that returns to the microphone.


**Stretch**

1.	
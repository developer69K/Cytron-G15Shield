# exitWheelMode() #

## Description ##
This function is to exit wheel mode and reset the angle limit to the default value.

## Include ##
Cytron_G15Shield.h

## Prototype ##
		uint16_t exitWheelMode(servoID);

## Parameters ##
**servoID**: G15's servo ID

## Returns ##
Error status in 2 bytes. If return is non-zero, error occurred. Refer Return Status.

## Example ##
		g15.exitWheelMode(1); // Exit wheel mode for G15 with ID number 1
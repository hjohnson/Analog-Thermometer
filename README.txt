PHYS 320 Final Project: Thermometer. 
Harry Johnson
12/17/11
CC BY/SA 3.0

	These circuits are a paired temperature probe and analog panel meter to display said temperature.
 	
	On the probe side, a 2n3904 NPN transistor is used in saturation, where the Base-Emitter junction is essentially a diode. Silicon diodes in saturation have a fairly linear -2.2mV/ºC temperature coefficient. The forward voltage is also dependent on the collector current of the transistor, so the transistor is immersed in ice water to cool it to 0ºC and a potentiometer is used to calibrate the forward voltage to equal a reference voltage formed by R1 and R2. When this is done, the op amp will output 0 volts when the temperature is 0ºC. Next, a second potentiometer is used to calibrate the gain of the op amp circuit so an increase in 1ºC results in a voltage output increase of 100mV.

	On the panel meter side, a 0-100mA ammeter driven by a standard op amp current source is used to display 0-100ºC. 
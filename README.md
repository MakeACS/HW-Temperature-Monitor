# Temperature Monitor

This ACS hardware accessory allows monitoring of a thermistor, and can disable the deployment if the temperature gets too high or low. 

## Configuration

To configure the device, press and hold the center button for 3 seconds. The button will start to flash to indicate it is in settings mode. 

The following settings are available: 

* Units (Indicated U) - U-CE or U-FH for Celsius/Farenheit
* High Temperature (Indicated H) - H095 for 95 degrees
* Low Temperature (Incidated L) - L010 for 10 degrees
* Brightness (indicated b) - bOFF for 0 (screen off), b-01 to b-07 for 0-7. Should update in real-time to show.
	* When in the settings menu at brightness 0, brightness 1 is used instead.
* Beta (indicated by bEtA) - screen shows the word, then flashes to the value as all 4 chars.
	* To make setting easier, beta starts at 3950, and wraps between 1500 and 5000.
	* Tip: Press and hold the up or down button to quickly scrolls through values. 

Once you cycle through all settings, the system returns to normal operation.

*Warning: There is no option to revert or not save settings changes, they go into effect immediately!*

## License
This project is licensed under the CERN-OHL-S 2.0 License. See LIECENSE.txt for more information.

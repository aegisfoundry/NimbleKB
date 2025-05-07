## Symptom
Nothing Prints

## Troubleshooting
Ensure that that Nimble can see the printer. 
From the back office, go to the configuration, check printers.
﻿
![image](https://github.com/user-attachments/assets/f7926f9c-c0b2-4dac-852c-f533b77ce941)

If the screen does not display any printers and/or says something like "No printers found" when using Windows Print Services:
	• Ensure that the services are running. 
	• Ensure the UWP Loopback exception is enabled


Ensure the printers being used do not show as Offline, out of paper, etc. The "None" or "OK" state means the printers are reporting OK.

If a printer shows as offline or shows an error status
* Restart the printer. The power switch is normally on the side or front of the device.
* Restart the register
* Check the printer cabling (network or USB)- unplug and replug the power and network/USB connection.
	
If the printer shows as other error state (out of paper, door open, etc)
* Fix the indicated issue

If the printer shows as None
* Check the print rules- ensure that the print rule in question is valid- the computer name is selected, the printer name is selected, the receipt type and print style are correct, etc.
* Ensure the paper is loaded correctly. Some printers require the roll to be oriented differently. The inside cover of the print door usually has the correct orientation for paper.
* Note- If the computer's name has changed, any associated print rules for the device will need to be reset.
* Check the audit log for the store / station. If needed, enable printer debug mode.
* Attempt to print test page from the printer. For most printers, this involves turning off the printer and power it back on while holding down the feed button.
   * If the printer does not print, then the paper may not be loaded properly. If reseating the paper roll does not help, the printer may be broken.

### Note on Pax Thermal Printers (T3810, etc)
If you have a Pax thermal printer that will not print, press the power button 4 times in rapid succession. The printer lights should blink and the system will beep after a few seconds as it restarts. 
This will reset the internal connection between the printer and the device using it.

**Symptom** 
Nothing Prints

**Troubleshooting**
Ensure that that Nimble can see the printer. 
From the back office, go to the configuration, check printers.
﻿
![image](https://github.com/user-attachments/assets/f7926f9c-c0b2-4dac-852c-f533b77ce941)

If the screen does not display any printers and/or says something like "No printers found" when using Windows Print Services:
	• Ensure that the services are running. 
	• Ensure the UWP Loopback exception is enabled


Ensure the printers being used do not show as Offline, out of paper, etc. The "None" or "OK" state means the printers are reporting OK.

If a printer shows as offline
	• Restart the printer. The power switch is normally on the side.
	• Restart the register
	• Check the printer cabling (network or USB)- unplug and replug 
	
If the printer shows as other error state (out of paper, door open, etc)
	• Fix the indicated issue

If the printer shows as None
	• Check the print rules- ensure that the print rule in question is valid- the computer name is selected, the printer name is selected, the receipt type and print style are correct, etc.
	• Note- If the computer's name has changed, any associated print rules for the device will need to be reset.
 	• Check the audit log for the store / station. If needed, enable printer debug mode.

## Pax T3180 Thermal Printer

Supported Connection Options:
Ethernet, WiFi

Note that USB and Bluetooth are not currently supported

### Status Light
If the unit is on WiFi, the status light will blink green if WiFi is connected.

### Print Configuration
This will print the current system configuration.

- Turn the power to the printer off.
- Hold the power button and paper feed button
- After about half a second, release the power button but continue to hold the paper feed button
- If the unit prints out a long page, and then a short page, release the paper feed after the second page prints.
- If the unit only prints out a long page, you can release the paper feed after it prints.

*Depending on the firmware, the unit will either print 1 slip of paper or 3.*

If the unit prints 3 pages, the third page will have the ethernet/wifi information on it.
If the unit prints 1 page, the network configuration will be on the first page.


### Print WiFi Parameters (WiFi Only)
This will print the systems WiFi parameters.

- With the printer on, press the power button 3 times, approxiamtely .5 seconds each time with a .5 second delay between each.
The unit should print the current WiFi configuration.
If the system is in AP mode, it will show the SSID and password to connect.
If the system is in endpoint mode, it will show the currently configured WiFi network.


### Reset WiFi (WiFi Only)
This will revert the unit to AP mode.

- With the unit on, press the power button 5 times, approxiamtely .5 seconds each time with a .5 second delay between each.
- The unit should beep and restart


### Toggle Between Ethernet/ WiFi
The T3180 can either be WiFi or Ethernet, but not at the same time.

- With the printer on, open the paper door.
- Press and hold both the power and paper feed buttons on top of the printer and hold them for at least three seconds.
- The unit should beep and reboot.


### Resetting a T3180
To reset a T3180 to factory settings, perform the following procedure:

- Open a web browser to the printer's IP address using HTTP only. E.g., http://192.168.1.237
- Note: You may have to use Firefox because every other browser seems to not let you do this any more. Thanks, literally everyone else.
- Under the Configuration -> Network -> Reset, select "Factory Reset"

![image](https://github.com/user-attachments/assets/e95bf3b9-3820-49dd-9ca4-8b5402695bf7)

After you confirm you want to reset, the system should beep and reboot the printer.


*Notes*
A factory reset will NOT reset a locked connection. If the problem you are trying to solve is that you cannot print from the unit, try the "release connection" process instead.


### Release Connection on a T3180
The T3180 can get locked to only allow printing from certain sources. To unlock / release the lock, perform the following procedure:

- With the printer on, press the power button 4 times, holding about .5 seconds each time with a .5 second pause between each press.
- After the fourth button press, the unit should beep and restart. If it does not beep, try again.

Once the unit restarts, it should be released to connect and allow printing from other sources.

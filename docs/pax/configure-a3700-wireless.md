## Configuring the Pax A3700 for Wireless

The A3700 tablet payment processor is often paired with the Pax L1400 POS station.
However, if you are trying to connect the A3700 to a wireless network, you will need to first configure the USB settings on the A3700. Otherwise, the WiFi will shut down any time the station is docked.

*Note - You will need to perform this procedure with the station docked to the L1400*

First, have the payment processor uninstall the "Petunia" app from the A3700. It is a service, and cannot be uninstalled from the device, only the Pax Store.

To configure the terminal's USB settings, you will need to exit the payment application if it is up. Generally, this is done by tapping on the four corners of the screen, starting with the top left, and then entering in the password to exit.

Tap on settings

![image](https://github.com/user-attachments/assets/52f6f637-b6e5-452b-816a-a239c465e4c8)

You will be prompted for the device's configuration password. If you have not set or changed the password, it may be the default password. Please see the article on default passwords for Pax devices.

Tap on "Connected Devices", and then "USB"

![image](https://github.com/user-attachments/assets/84631dbf-224f-4986-9db5-15340838332f)

*Note that if you do not see a "USB" section, your station may not be docked to the L1400. Please verify the station has locked onto the base terminal.*

Scroll down until you see the USB settings. By default, the A3700 is configured for "ECM". Change that setting to "No Data Transfer"

![image](https://github.com/user-attachments/assets/88e25534-206b-4089-b0fc-980eba53ed58)

Next, on the left-side menu, select "Network and Internet"
Enable WiFi, and select your preferred network.

![image](https://github.com/user-attachments/assets/c0cce86d-972f-4745-a1fc-352482b48d36)

Once you have set up WiFi, scroll down on the page until you see "Wi-Fi Preferences".
![image](https://github.com/user-attachments/assets/e35266b6-a6a0-46d9-9ce2-75dc2ba97f4b)


Tap on that, and ensure "Turn on Wi-Fi automatically" is enabled.
![image](https://github.com/user-attachments/assets/9277d8ab-1750-4b68-858e-a5001d9b492d)


### Notes 
To ensure that the device is always reachable from the stations, configure your wireless settings with a static IP address, or configure the customer's wireless network to reserve an IP address for that specific device.

You can also configure the WiFi from the Pax store, but the configuration must be done prior reconfiguring the USB settings. If you need to change the wireless configuration after disabling the USB, you will need to either do so manually *and* in the Pax store device configuration, OR you will need to re-enable ECM on the USB configuration, and then the updated settings from the Pax store will flow to the device.

![image](https://github.com/user-attachments/assets/d2b129c2-06f2-4d50-b47c-811a350df385)




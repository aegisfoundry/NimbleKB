## Configure the L1400 / Elys Solution

Note: This assumes you have wired up the station already. See the KB on the Pax L1400 for details.

1.	Wire up the station.
2.	Power on the L1400 and add it to the customer's network (WiFi or Ethernet)
3.	Ensure the firmware is on the latest version. If not, have the processor or whomever is responsible for managing the device perform a push install of the latest L1400 formware.
4.	Have the processor or whomever is responsible set the system to restart (if possible) at 4:30 AM CST.
5.	Ensure that the timezone on the system is correct; That is something that can be set by whomever controls the device via the Pax store admin system.
6.	Ensure the Honeybee application and Petunia service are not installed.

•	*If the honeybee app is installed and you cannot remove it, you are not on the latest firmware.*

•	*The petunia service, if installed, can only be removed via the pax store.*

7.	Configure any bluetooth devices, such as barcode readers, etc
8.	If the customer is using a Pax printer, they will need to change the printer mode to Ethernet, or configure WiFi on the device. In both cases, the device should have a static IP address assigned to it from the customer’s internal network. 
9.	If the customer is using a connected Pax A3700 card reader, ensure the device is set up properly. See the KB on the Pax A3700.
10.	If the customer has a cash drawer, ensure that the drawer is connected to the printer and configure the printer kick code. 
11.	Install Nimble, either via push install or via the app store.
12.	Log into Nimble with the support users email and password and go to registers.
13.	Tap on “This Device”
14.	Give the device a nickname and save that. 
15.	Tap on “This Device” again and and authorize the register in Nimble and restart the NimblePOS client. 
16.	Log back in to Nimble as the support user number and go to the back office.
17.	Configure the printer as a “known printer” with a type of Epson, port number of TCP:<device’s IP address>, port settings of 9100, character width of 45. Name the device something appropriate (e.g., Receipt1, etc)
18.	Ensure there is a Pax Ethernet payment type set up in the Payment section. You only need one for the store, not one per register, so if there is already a “Credit” payment type, you do not need to create a new one.
19.	Go to registers and tap on the name of the device and then edit.
20.	Set the default printer name to the name of the known printer configured in step 17.
21.	If the station has a cash drawer, enter the IP address of the printer, port 9100, and cash drawer kick command.
22.	Save the register settings.
23.	Edit the register again
24.	Go to providers and select the name of the credit provider you have set up for the store in step 18.
25.	Enter in the card reader’s IP address. The port number is typically 10009 unless it has been changed by the processor / gateway (not typical). You must give the provider a receipt name (e.g., “Credit”) for the payment to be active. All other settings will depend on the specific scenario involved (e.g., tip on device, etc).
26.	Note that “Use Post Auth Tip” is only required for Heartland processing.


## Configuring Nimble for a Pax Reader

### Add the Pax Ethernet Payment Provider
Note: You only have to configure ONE pax ethernet payment provider per store.

Under the POS Settings (Gear icon on the left menu in the back office), tap "Payments".

If you do not already have a Pax Ethernet payment type, you will need to add one. Tap ADD to add a new payment provider.

<img width="537" height="536" alt="image" src="https://github.com/user-attachments/assets/9a05daca-a628-443b-9a8e-07ac274e6230" />

Give the payment type a name that will show up on the customer receipt (Typically, "Credit")

Set the payment type to Credit

Select "PAX Ethernet" as the provider. If you do not see providers listed, ensure you have already set the payment type.

You can set a minimum permission to use the payment type (Not typical). Most customers, this field can be left blank. 

Tap Save.

### Pax Device Settings
Set the device up on the customer's network, either ethernet or WiFi. 

Make a note of the reader's IP address.

It is strongly recommended that you utilize a static IP address for the payment device, either via setting the static IP address on the device itself or by utilizing a static IP reservation on the customer's network specifically for that device.

It is stringly recommended that the device firmware be updated to the latest firmware prior to deployment.

Key Settings:
* Ensure auto batch is ENABLED.
* Ensure the ECR Terminal Integration Mode is EXTERNAL POS
* Ensure the Communications port is 10009

All other settings, such as tip configuration, tip-on-device amounts, surcharges, fees, etc are merchant specific or utilize default settings.


### Register Settings
Once the pax payment provider has been configured in the POS system, you will need to configure each register that will need to connect to a payment terminal.

Under register configuration, go to each active register and edit the settings and go to "Provider"

To to the "Credit" provider (or whatever you called the payment provider in the system from above).

Set the port to 10009
Set the receipt name to "CREDIT" or whatever name you want on the customer receipt.
Enter the Card Reader's IP address (from above)

If the customer is going to utilize a tip-on-device (e.g., the customer is prompted to add a tip from the payment device), enable the "Tip on Device" option. You will also need to ensure the tip-on-device settings are configured in the Pax Store settings for that device.

_If you are configuring a Heartland payment reader and will be taking tips, enable the "Use Post Auth Tip" option. This is a Heartland-specific feature and should not be enabled if you are not using a Heartland processor._






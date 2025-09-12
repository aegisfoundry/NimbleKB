## Configuring Nimble for a Valor Reader

### Add the Valor Payment Provider
Note: You only have to configure ONE valor payment provider per store.

Under the POS Settings (Gear icon on the left menu in the back office), tap "Payments".

If you do not already have a Valor payment type, you will need to add one. Tap ADD to add a new payment provider.

<img width="540" height="536" alt="image" src="https://github.com/user-attachments/assets/fac53610-8901-47dd-99c8-f5f67ecb8ae5" />

Give the payment type a name that will show up on the customer receipt (Typically, "Credit")

Set the payment type to Credit

Select "Valor" as the provider. If you do not see providers listed, ensure you have already set the payment type.

You can set a minimum permission to use the payment type (Not typical). Most customers, this field can be left blank. 

Tap Save.


<img width="540" height="536" alt="image" src="https://github.com/user-attachments/assets/5030f1ff-cddf-4a9f-926c-8e61d34bfa26" />


### Register Settings
Once the Valor provider has been configured in the POS system, you will need to configure each register that will need to connect to a payment terminal.

Under register configuration, go to each active register and edit the settings and go to "Provider"

To to the "Credit" provider (or whatever you called the payment provider in the system from above).

Set the port to 5000
Set the receipt name to "CREDIT" or whatever name you want on the customer receipt.
Enter the Card Reader's IP address (from above)

If the customer is going to utilize a tip-on-device (e.g., the customer is prompted to add a tip from the payment device), enable the "Tip on Device" option. You will also need to ensure the tip-on-device settings are configured in the Valor merchant portal settings for that device.

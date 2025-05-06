Register Management allows for the configuration and authorization of registers for a given store.
 
## Authorize Register
When you first log in to the point of sale, you will have to use a username and password from a manager with Non-Register access set. 
 
If the device is going to be a register - allowing the register to process orders and perform related operations - it will need to be authorized by pressing the "Authorize Register" button in the "Registers" page under the "Configuration" gear icon.
 
Please note that authorized registers are billed on a monthly basis. If you authorize a terminal, your store will be billed for that register on the next monthly bill.
 
Devices that are not authorized as a register will still have access to the entire configuration and back-office part of the system for no charge.
 
## Deauthorize Register
Managers can remove registers from their account by clicking / taping on the name of a register and pressing the "Deauthorize" button. If no register is selected, the deauthorization will act on the current device.
 
This will remove the selected register from your next billing cycle. 
 
Please note that terminals are billed for the previous month. For example, if you deauthorize a terminal on September 15th, you will still be billed for that terminal on your October bill for service through the end of September, but it will not be on your November bill for your October service. Likewise, if you authorize a terminal on September 15th, you will be billed for it starting on your October bill for your September service.
 
Registers are billed for whole months. If you authorize a register on the 29th day of the month, you will still be billed for the entire month.

![image](https://github.com/user-attachments/assets/e7cf3b2c-ac36-4895-82a6-e896feeacf25)

## Editing a Register
If you tap on a register and "Edit", you will be able to configure register information.
 
The register persona is the persona the register will use. Examples include the default persona, table management persona, and bar persona.
 
Note that changing the persona will require a restart of the register.
 
You can adjust the logged in (Order Management) screen timeout- this is the time in seconds before a register will log out of the system and return to the PIN pad log in if there has not been any activity from the employee.

You can also adjust the time out from the order screen. This will return an employee to the order management screen from an order screen after the specified number of seconds of inactivity. Any open order will be stored prior to returning the employee to the order management screen.
 
You can enter the name of the register's default printer (See Print Rules), and if the register has a cash drawer, you can enter in the IP address and IP port or the Com port for the drawer, as well as the drawer kick command.
 
If you enable "Fast Order Style", the register will stay in the order screen after closing an order. This optimizes the workflow for ordering styles that flow from order to payment in a single transaction, such as fast food and fast casual.
 
Note- If you use "Fast Order Style" ordering, it is strongly recommended that you set a default service type or the system will prompt you for a service type at the completion of every order as a new order is automatically started.
 
Note- Fast Order Style is often used with "Auto-Close Items" in the store configuration. See Store Configuration for details.

![image](https://github.com/user-attachments/assets/76b74fd6-5c05-4d69-b0dd-8b5462d47385)

"Set Providers" will allow you to configure parameters for each payment provider in the system.

![image](https://github.com/user-attachments/assets/c2197dc1-8488-4be7-b278-3607cffccfdf)

Same payment providers will only require a receipt name. 

**If a name is not provided for a given register, the payment type will not be available on the register.**

![image](https://github.com/user-attachments/assets/385f27bc-f040-439e-9385-62e2e8a4e37e)

For payment processors, more information may be required, such as the IP parameters of the reader, port number, and tip settings. Please check with your payment provider for these settings.

![image](https://github.com/user-attachments/assets/f3b07987-79ba-45a6-9840-6a234a05efa4)

Same payment processors allow the payment device to operate as a customer-facing display.

If your device supports this configuration, you will have options in the payment provider configuration to enable and use that feature. The example below is for Pax devices, which have two related options: Enabling the device for use as a second screen, and the screen width in characters for padding between the item name and price to allow for use with wider or narrower displays.

20 to 25 is usually fine for narrow devices, such as an A35, A80, and A920 device. Wider devices, such as an A3700, require larger values to maximize the screen real-estate being used.

![image](https://github.com/user-attachments/assets/463cf823-ea58-4196-a143-40bec87772e9)

Using your payment device as a second screen may also include an idle screen when not in an order that may show your store’s name and phone number, depending on the capabilities of your device. These values are pulled from your store configuration page, so no additional set-up is needed to enable that.

## Register Configuration - Second Screen

You can set a device up as a dedicated second screen. This can be useful for customer-facing screens, or when developing a drive-through solution.
To configure a device as a second screen requires you to set the register persona of the taret device to ‘Second Screen – Child’. 
On the source station – the one that would be creating or editing the order- you will need to go to the register configuration for that device, tap on the ‘Second Screen’ button, and select the register or registers that you have set with the second screen persona. 

![image](https://github.com/user-attachments/assets/7b96ba11-292d-433f-9f87-9830a7918bd6)

This will establish a link between the parent and child device or devices. A parent station can use multiple devices as a second screen, so you can have a customer facing display and mirror the information to a drive through screen, for example. 

If you want to customize the idle / splash images on the second screen, you will need to use the ‘Styles’ configuration page. You must have a support level user to access styles, this cannot be done by a store manager.

## The total size of all custom images used in the second screen carousel must be less than one megabyte. ##











 


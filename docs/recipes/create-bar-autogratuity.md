## How do I create an auto-gratutity for a bar when the customer did not close out their tab before leaving?

Typically seen at bars or table-service restaurants with bars that use pre-auth. The customer does not have to leave their credit card with the bartender, but if they do not close out their tab before leaving, an automatic gratuity would need to be added to the tab before closing it.

To configure, ensure that the customer has the "Close Tab" feature enabled.

Create a service charge of the type "Auto Gratuity - End of Day" set to the desired parameters. E.g., 20% fee with 100% payable to the employee.

The close tab feature will automatically use a configured service charge of this type, and add the fee to the order before automatically closing out the tab with the credit card processor.

### If the customer is not using the Close Tab Feature

It is STRONGLY recommended that the customer use the Close Tab feature for this.

To do this without the close tab, there are a few options:
- Create a new service type for orders that need to be closed out with an autogratuity.
  - Create a service-type service fee in the system with a name like "Bar - Autogratuity"
  - At close-of-day, the bartender will need to change any open orders to this service type.
  - Once the order is moved to the new service type, it will have the auto gratutity added to it.
  - The bartender can then manually close out the order.
- Create a new service charge for a guest count of 99 or more.
  - Name the service charge something like "Bar Autogratuity", but use the "Guest Count" type charge, and set it to a very high number (like 99).
  - At close-of-day, the bartender will open each order and change the guest count to 99, which will add the charge to it.
  - The charge on the receipt will read whatever the service charge name is, so the fact that the charge is techincally a guest count will not matter on the receipt.
- Create a misc item in the system with a misc name and add it to each order, calculating the price for the item when you add it.

Again, it is STRONGLY recommended that the customer use the Close Tab Feature for this, because a single button press will close all eligiable orders with no extra input or work.

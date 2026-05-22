# Retail Interface

# Front Of House / Cashier Operations

*Item Loading*

Retail stores often contain far more items than restaurants and will take longer to start because all of the items have to be loaded. The client is capable of loading items in the background after startup, but until all items are loaded, the system will show the following message at the login page.

<img width="350" height="134" alt="image" src="https://github.com/user-attachments/assets/273fa226-51ca-4552-a58f-1094fe591d58" />

The system can still be used for basic functions while the items are loading in the background, although order management and processing will be disabled until all store items are loaded. Once the store items are loaded, the message will automatically clear out.

It can take several minutes for very large stores to load, depending on the internet speeds and/or the use of a local server. A 50,000 item store without a local server can take up to a minute to load with fast internet, for example.

*Navigation*

Retail does not navigate between single order and open order management like the restaurant personas. Instead, all retail front-of-house operations are performed from the same screen.

## Operation

When a user with access to create new orders logs in(e.g., cashier, etc) the system will be ready to take orders. If a non-manager logs in and the “Enforce Timeclock” option is enabled, the user will be required to clock in before they can start taking orders.

<img width="468" height="354" alt="image" src="https://github.com/user-attachments/assets/4932e739-2a5a-4d3f-a347-2519ba09e443" />

The retail persona is barcode / item focused. If you do not have a barcode scanner, you will only be able to add items via the “Lookup / Search” field or the “PLU Lookup” button.

If you have a barcode scanner, simple scan an item’s barcode to add it to an order.

<img width="468" height="354" alt="image" src="https://github.com/user-attachments/assets/9852715e-29b6-49dc-8c22-91a24587abff" />

Subsequent scans of identical items will increase the quantity of matching items on the ticket instead of adding duplicate line items.

<img width="468" height="85" alt="image" src="https://github.com/user-attachments/assets/a600b129-9433-40dd-b0d7-f36f1fe0ead3" />

### Using Lookup / Search

Tap on the “Lookup / Search” box on the right side of the screen to bring up the search window.

<img width="290" height="316" alt="image" src="https://github.com/user-attachments/assets/cccfa887-2be0-4230-978b-8a65ab2df0a0" />

You can search via department, name, barcode, or PLU, including partial searches. For example, to search for “Gatorade”, you can type that into the name field and tap search.

<img width="290" height="187" alt="image" src="https://github.com/user-attachments/assets/4950b2cb-69a1-4cb2-8390-fb26a3ff5c8e" />

*Note: The search can take a moment if there are a lot of matching items and the store has a large number of items.*

Search results will be displayed, showing all matching items.

<img width="289" height="287" alt="image" src="https://github.com/user-attachments/assets/6ac1e13e-fb61-4a56-a8bd-2b0e7306f331" />

From here, you can go back to the search page through results, or tap an item and add it to the order.

<img width="468" height="102" alt="image" src="https://github.com/user-attachments/assets/243ce423-833f-482c-bfe5-0b21d4dd7147" />

### PLU Lookup

If you tap the PLU Lookup from the main screen, you can enter in a PLU.

<img width="289" height="289" alt="image" src="https://github.com/user-attachments/assets/28397adc-e180-4db4-befe-c655273cb8e7" />

If a matching PLU is found, it will be added to the order.

### Adjusting Quantity

If you want to manually adjust the quantity of an item- for example, a double scan or in the event the customer is purchasing a lot of identical items, you can tap the line item on the receipt view and tap adjust quantity.

<img width="468" height="354" alt="image" src="https://github.com/user-attachments/assets/3baf7951-e03b-4aaa-a30c-d6ff5ebaf2fb" />

*Note- You cannot adjust a quantity to 0; You will need to void the item (See Void)*

## Voiding Items

To void an item, tap on an item and then “Void Item”

<img width="468" height="354" alt="image" src="https://github.com/user-attachments/assets/3ec53d5f-4fcb-46f9-ab96-baf2808a0e1f" />

You can enter a reason for the void. If you have void action reasons configured, you will see buttons already set up for fast explanation.

<img width="290" height="289" alt="image" src="https://github.com/user-attachments/assets/bcac67c0-6b2c-463a-a4cf-e9570faf3b38" />

## Associating Order with a Customer

For cases where an order needs to be connected to a specific customer or attaching a customer name to an order is needed, tap the “Customer” field at the top of the screen.

<img width="290" height="198" alt="image" src="https://github.com/user-attachments/assets/59991d19-5e9a-44cd-9e6e-ca0f1e278a3f" />

### Guest

Selecting “Guest” will allow you to attach a non-durable customer name to the order. While the name is saved with the order, a new customer record is not created.

<img width="290" height="145" alt="image" src="https://github.com/user-attachments/assets/fd8ec7d5-df48-456e-af33-1c55f195e95e" />

### Lookup

Lookup allows you to search your customer database for matching customers. You can use a combination of fields, including first and last name, phone number, or email.

<img width="290" height="289" alt="image" src="https://github.com/user-attachments/assets/e81e158a-416e-4a97-a16b-bd8aca1318fe" />

### New Customer

New customer allows you to create a new customer in your customer database that can be used in subsequent lookups.

The only required fields for a customer are first and last name.

<img width="290" height="289" alt="image" src="https://github.com/user-attachments/assets/e4dbd08f-45c3-41e1-a0aa-fd6d9257ba0b" />

## Ticket and Item Notes

You can add notes to items and for tickets.

To add a note for an item, tap on the item and select “Item Note” from the right side of the screen.

To add a ticket note, go to “Options” and select “Ticket Note”

# Payment

## Quickpay

For cases where the customer is applying a single payment to an order that does not require manual discounts or loyalty, cashiers can tap “Quickpay” from the main screen and choose a payment type to more quickly cash out a customer.

## Cashout

Cash out offers more options than quickpay, including discount management, loyalty, and other options.

To cash out an order, tap the “Cashout” button on the POS screen.

<img width="290" height="277" alt="image" src="https://github.com/user-attachments/assets/683e2736-7bae-4fec-8ecb-da3b8a5e55c5" />

From the cashout screen, you can add manual discounts, add or void payments, store the ticket for later use, or close the ticket.

### Adding a Payment

To add a payment, tap the Add Payment button and select the payment method.

<img width="468" height="153" alt="image" src="https://github.com/user-attachments/assets/defb89b8-5ea4-4e7b-b429-15dac8fc95cb" />

You will need to enter an amount to pay. By default for non-cash payments, the amount will be the full amount of the order, but you can override the amount to do a partial payment.

<img width="290" height="292" alt="image" src="https://github.com/user-attachments/assets/e5ac1d97-9e36-4b0f-8753-5f98f8b14505" />

You can tap add payment to add additional payments. 

If the order has sufficient payments to close the ticket, the “Close Ticket” option will be available.

### Adding a Discount

To add a discount, tap the “Add Discount” button from the cashout screen. You will need to select a discount group, and then choose a discount.

<img width="219" height="218" alt="image" src="https://github.com/user-attachments/assets/d4fbbc41-de06-4554-8a4b-4544b6100e2f" />

If the discount you select is an item-level discount, you will need to choose the item to apply the discount to.

<img width="219" height="218" alt="image" src="https://github.com/user-attachments/assets/6b9d8e42-6f1c-46c4-bf9e-f20efef300f0" />

Non-eligible discounts are not displayed or will be disabled.

### Voiding a Payment

To void a payment, tap the “Void Payment” button. You will need to select the payment to void.

*Note that cash payments with change will create two payment entries- a payment, and a change entry. You will need to void both.*

Credit payments can only be voided on the same batch, which is usually closed at the end of the day. For previous days, you will need to refund instead of voiding a payment.

### Void Discount

If your order has discounts, you can void them from the cashout screen by selecting “Void Discount” and selecting the appropriate discount.

### Modify Tip

If your store uses tips and does not use tip-on-device, you can add or modify a tip on a payment. This is not a typical configuration.

### Print

Print will print an itemized receipt for the customer. This can be done prior to payment or after payment.

*Note that if you have “Quickly Close Orders” enabled, you will be prompted when an order is closed if you want to print the ticket.*

### Store Order

Storing an order allows you to save the current order without closing it or paying for it. A typical case might be a customer forgot their wallet or is calling in an order they are going to pick up later that day.

Tapping “Store Order” will move the order into the “Stored” tab at the top of the screen.Using Giftcards

### Checking a giftcard balance

You can check a giftcard balance from the cashout screen by tapping “Giftcard Balance”, or from the main screen under “Options”

### Loading a Giftcard

To load a gift card, under “Options”, select “Load Giftcard”

<img width="217" height="217" alt="image" src="https://github.com/user-attachments/assets/534366f0-12a2-4c41-8542-acc03ffde22d" />

### Redeeming a Giftcard

Giftcards are redeemed like any other payment method. You can use quickpay or the cashout screen to charge an order to a gift card.

### Using Loyalty

Loyalty can be accessed by using the “Options” panel and selecting “Loyalty”, or tapping the “Loyalty” button at the top of the screen.

<img width="219" height="162" alt="image" src="https://github.com/user-attachments/assets/f981b1c0-545e-4aea-b9f4-3d0e6e7391a3" />

To look up an existing loyalty member, you will use the customer’s phone number

<img width="218" height="217" alt="image" src="https://github.com/user-attachments/assets/bdcc6c65-a50d-4847-a58b-c8f90a1163f1" />

Tap in the member’s phone number and select lookup. If there is a match, the information will be displayed.

<img width="218" height="217" alt="image" src="https://github.com/user-attachments/assets/71acddeb-4729-4081-bd46-fa00a9915a3c" />

If this is correct, select “Done” to apply the loyalty information to the current order.

If this is not correct, tap “Change” to search for a different member. 

You can also choose to edit the member’s information directly from this panel.

<img width="217" height="216" alt="image" src="https://github.com/user-attachments/assets/6c18e5ca-5b67-49ee-8d50-c5ce5a60d1dd" />

### Enable / Disable Fees and Taxes

To enable or disable order fees or taxes, tap on “Options”

<img width="218" height="217" alt="image" src="https://github.com/user-attachments/assets/1c02b332-2661-47db-8052-4207a672070c" />

From here, you can toggle fees or taxes on for a given order.

Note that disabling fees requires permissions that a cashier may not have, and they will be prompted for a user ID with permission to make the change.

When fees or taxes are disabled, the button reflects the current state.

<img width="217" height="216" alt="image" src="https://github.com/user-attachments/assets/cffc9158-ee09-4df4-b070-79f23cb3e31f" />

## Viewing Stored Orders

If an open order has been stored, you can tap on “Stored” on the top right screen to view stored orders.

You can tap on a ticket to view the items, and can edit, void, or reprint the ticket by tapping on the appropriate buttons on the right side of the screen.

<img width="468" height="332" alt="image" src="https://github.com/user-attachments/assets/d349b124-0857-4129-abb2-e2bbc779d2db" />

## Viewing Historic Orders

To view closed orders, from today or from previous dates, select the “Historic” button at the top of the screen.

<img width="185" height="173" alt="image" src="https://github.com/user-attachments/assets/0bf4fdb3-57da-494a-89d1-66535d12a107" />

You can search by ticket number and date

<img width="289" height="205" alt="image" src="https://github.com/user-attachments/assets/579007e7-9b00-473e-918b-3852342403d2" />

Or see all tickets for a given business day

<img width="290" height="144" alt="image" src="https://github.com/user-attachments/assets/91a0612e-7ba2-42ab-8be8-1ae2807400b3" />

## Refunds

You can only issue refunds on historic tickets. Open tickets, even if stored, can only have payments voided. If you need to issue a partial refund on an open ticket with active payments, you will need to close the ticket first.

<img width="468" height="320" alt="image" src="https://github.com/user-attachments/assets/1aa89bdb-46f5-47ff-ae40-92136b6f8e84" />

Tap on a ticket, then select “Refund”

If the user does not have rights to do a payment refund, they will be prompted for an employee that does.

<img width="289" height="290" alt="image" src="https://github.com/user-attachments/assets/dedbe8b7-74ed-4d96-a9eb-ff038811fbd6" />

You will be prompted for a payment refund method. You can refund an amount to any configured payment method. For example you can refund a sale to a store gift card, for example.

<img width="468" height="175" alt="image" src="https://github.com/user-attachments/assets/2e280c0d-93a9-43e6-bf51-aa52465e9cba" />
 
Enter in the amount of the refund.

*Note that you cannot enter in an amount more than the amount of the order after any other refunds are taken out.* 

For example, if the order was $50 that already has $30 of refunds against the same order, you cannot refund an additional $40; The maximum refund amount in that scenario would be $20. If you enter in too high of an amount, the “Next” button will be disabled.

<img width="290" height="290" alt="image" src="https://github.com/user-attachments/assets/737f9d63-ba2c-4f9b-aec0-25bc037179b5" />

*Note that refunds are linked to orders so that a store can track that information.*

# Back of House Operations

## Item Management

Item management is conducted with the item management page in the back office. Select the shopping cart icon on the left-hand menu.

<img width="290" height="188" alt="image" src="https://github.com/user-attachments/assets/9f02f012-af93-411d-8488-c248c98e4071" />

To find an item, you can search by department, tag, item name, the barcode, PLU, or a combination.

<img width="468" height="142" alt="image" src="https://github.com/user-attachments/assets/fa0ce11f-8e22-4407-b50a-8be95ee4976d" />

If your search results are too broad, you will get a warning that only the first 100 results are shown.

<img width="290" height="117" alt="image" src="https://github.com/user-attachments/assets/d710d9dd-912a-4c12-be6c-9dde61d61296" />

To edit an item, tap on the edit button, or you can tap “Add” to create a new item.

<img width="747" height="626" alt="image" src="https://github.com/user-attachments/assets/b840c7df-7f02-43ee-a6e4-d09872c87410" />

You can optionally set a department for an item. Note that this is a change from the restaurant personas that require a department for an item to be purchasable; in retail mode the department is optional.

The sort order is not critical for retail operations either and can be left at default unless there are specific use cases that warrant adjusting the value.

If you wish to track an items inventory, you will need to set the inventory item switch to “on”.

The "Sold By" drop down controls how the item is sold in the system:

### Normal

This is the default mode for all items.

### Weight

Items sold by weight will prompt front-of-house users for a scale (if configured) or to manually enter in a quantity. 

### Price in Barcode

Items sold with SKU pricing / Price in Barcode will read the price embedded in the barcode. This is typically used in delis, fish markets, butchers, and other stores that have external scales that print SKU priced barcodes.

Using this option will enable the "Sold By" panel

<img width="747" height="626" alt="image" src="https://github.com/user-attachments/assets/d0d11061-e215-4cce-958a-b953605e2b3f" />

SKU pricing uses a short barcode for the item, followed by a mixture of pricing digits and padding digits.

The Point-of-Sale system is able to handle 3, 4, 5, or 6 digit SKU prices by adjusting the options for the item. 

A 4 pricing digit scale will have a maximum scale amount of $99.99

A 5 pricing digit scale will have a maximum scale amount of $999.99

Those are not limitations in the POS, those are set from the scale.

*Note that 3 and 6 digit scales are very uncommon*

A 4 pricing digit SKU price barcode may typically be something like:

0203016621430

The item's root barcode (set in the barcode field of the item's main screen) would read 0203016 

*Note: Some barcode readers truncate leading zeros. If you are using a barcode reader that truncates leading zeros, do not enter a leading zero into the item's barcode*

The rest of the barcode consists of a left pad digit (6), the item's price in pennies (2143) and a right pad digit (0).

The padding digits are technically checksums, but the POS just ignores then in this instance.

By telling the POS that the SKU price has 4 pricing digits and 1 padding digit to the right, the system is able to deduce the digits in the barcode that represent the price.

Additionally, the POS is intelligent enough to convert the price into a quantity sold in the POS for inventory and sales records.

In the example above, if the item sells for $10.00 a pound and the SKU price was $21.43, the system will record that as a sale with a quantity of 2.14.

### Service

Service items are items that require specific employee positions to fulfill. This is only required if you are using scheduling for service availability. If you are not using scheduled availability, you do not need to configure items as service items.

<img width="277" height="202" alt="image" src="https://github.com/user-attachments/assets/2d9c75b2-a9ec-4b83-9379-ba0054c4b40b" />

Service items require that you enter in a service duration in minutes, and select a position that is required to fulfil the service.


### Rental

Rental items are items that are rented and not sold. This is only required if your store is using scheduling for rental availability. If you are not using scheduled availability, you do not need to configure items as rental items.

<img width="258" height="176" alt="image" src="https://github.com/user-attachments/assets/6a09be50-9dd5-4e7c-96ee-66a78df00122" />

Rental items require a duration of the rental in minutes to be entered.

In addition, rental items require inventory set up (see inventory) and at least one on-hand for availability.

### Tags

Tags are used in the system in various ways; Print routing, discounts, loyalty, and reporting can all use tags.

Because of the typical larger scope of items for retail stores, tag management becomes more important for item rules; it is impractical to try and apply discounts for specific items, for example/

You can start typing in a tag name to list matching tags, and if a matching tag does not exist, a new one will be created.


### Inventory
If you configure an item as an inventory item, the system will add a simple inventory page to the item detail.

*Note that full inventory adds additional options around items; See Inventory Management.*

<img width="747" height="626" alt="image" src="https://github.com/user-attachments/assets/62fd8e6a-15bc-453a-a7cf-587c7ca789c6" />

Inventory items in the POS are structured with inner and outer packaging, giving the store a tremendous amount of flexibility on how to track inventory.

Typically, an outer package is how the item is purchased, and inner packaging is how the item is sold. 

*Note that packing units are able to be set by the store to whatever name makes sense in context.*
For example, the store may track bottles, boxes, tablespoons, ounces, pounds, liters, gallons, pours, etc. 

Packaging Examples:
- A store may buy cans of cola by the case but sell them by the bottle. The outer package unit will be flat, the inner package will be bottle. The system will report inventory by fractions of a flat.
- A store may buy bottles of bourbon by the case and sell them by the bottle, but wants to track inventory by the bottle. To do that, use bottles for both inner and outer packaging, and the system will tracka nd report inventory by the bottle.
- A store may buy hamburger in 50 pound lots, but sell it in 1 pound packages. In that case, the inner and outer packages are both pounds, and inventory reporting will be by the pound.

Safety Stock is a reporting feature that allows you to set a reporting value for inventory reorder reports. If this value is set, any items at or below safety stock will appear on a reorder report. 

*Note that if you want the reorder report automatically, you will need to configure the report to be emailed out daily from the reporting portal*

*Note that safety stock is tied to outer packaging*

You can also optionally set the quantity on hand directly in the item management page instead of using the full inventory page.

## Pricing

As with all other personas, retail items can have multiple pricing rules, and different taxes can be applied to different items.
Items can also be set to be variably priced by toggling the switch.

Tap “Save” to save the item.

<img width="290" height="289" alt="image" src="https://github.com/user-attachments/assets/d33418c7-d09f-4a35-bab6-d657bffde00f" />

# Inventory Management (Full)

The inventory management in the item management page is simplified. The system has a full management section located under the "Inventory" option on the top under the shopping cart left icon

Due to the larger number of items typical in retail stores, inventory functions keys off of searching. 

<img width="468" height="305" alt="image" src="https://github.com/user-attachments/assets/3b4a720c-b5ed-4198-9f71-1576bb74acc6" />

Inventory management is structured around matching items to vendors, manufacturers, and packaging.

## Vendors

The vendor is the company or companies you buy products from. To add or edit vendors, tap the “Vendors” tab in inventory management.

You can optionally add in an accounting name to match up vendors with your accounting system.

<img width="290" height="184" alt="image" src="https://github.com/user-attachments/assets/e3ecf213-c6e8-4b8d-b43a-856d21adcbaf" />

## Manufacturers

The manufacturer is the brand of the item you are purchasing. As with vendors, you can optionally match up the accounting system identifier or account for a manufacturer.

<img width="290" height="184" alt="image" src="https://github.com/user-attachments/assets/3df9a012-48f2-4d48-87ef-802d4fba36f2" />

## Packaging

Packaging is where you combine the item with the vendor and manufacturer. You can enter in search times to see existing packaging, or create new packaging. To add or edit packaging for an item, tap on the add or edit button under the packaging tab.

<img width="468" height="214" alt="image" src="https://github.com/user-attachments/assets/4531f71f-9370-445b-984a-8c0adec010de" />

Tap the “Menu Inventory Item” field to start an item search.

<img width="290" height="290" alt="image" src="https://github.com/user-attachments/assets/58576b59-7270-4e94-b460-8dc0bfb01eaf" />

The item you are looking for can be found by searching by name, tag, department, barcode/SKU, PLU, or a combination of those fields.

<img width="290" height="317" alt="image" src="https://github.com/user-attachments/assets/e9aabc48-3635-483c-92ed-ddf5f0dad417" />

You can type in your search parameters and tap search to see your list of matching items

<img width="290" height="290" alt="image" src="https://github.com/user-attachments/assets/f66acd67-a428-4836-af42-649a3c7b28e0" />

Once you have selected your item, tap “Next” to go to the next tab to set the vendor, vendor item number, manufacturer, and manufacturer item numbers.

<img width="290" height="290" alt="image" src="https://github.com/user-attachments/assets/9216c4d5-36b7-4e6d-968b-615c6d7e3e6a" />

Tap next to set the packaging. This is the same functionality from inside of the item management page. See above for details.

<img width="539" height="540" alt="image" src="https://github.com/user-attachments/assets/9f55023b-ca00-40e4-b3f0-38ec3b7c4b76" />

## On Hand

The On-Hand tab allows you to track and adjust inventory quantities for items directly.

<img width="468" height="214" alt="image" src="https://github.com/user-attachments/assets/421fc6ed-ffc9-4e86-a962-19e2ea381f35" />

You can search for an item, and from here add, remove, or set inventory for a selected item.

Add and Remove will adjust the quantity of a selected item up or down based on the value that you set, while Set inventory simply changes the on-hand quantity to the value specified – for example, during a cycle count.

If you have configured inventory action reasons, you can select a pre-made inventory adjustment reason. For example, purchase, damage, etc.

<img width="290" height="287" alt="image" src="https://github.com/user-attachments/assets/3407d8b1-0b9b-42c5-81d9-456f71a040a3" />













































## What are my options for "cash discounting" / "credit service fee" / "dual pricing" in Nimble?
## How do I choose which type to use?

Although the terms "cash discount", "credit service fee", and "dual pricing" are sometimes used interchangably, they represent three different concepts. Nimble can handle each case.

### Cash Discounting

Cash Discounting is a literal discount that is applied only when the customer pays in cash. All of the pricing in the system in this scenario would need to reflect the *credit* price for the items.

To configure cash discounting, create a discount with the following parameters:
- Discount type is set to automatic order discount with a fixed percentage
- Payment type is set to cash.
- Minimum permission is set to your cashier / server job roles.
- Maximum one per order.

All other parameters - receipt name, discount amount, etc, can be configured to whatever are required for the specific case.

When a cash payment is added to an order, the discount will be applied at time of payment.

Note for table-service restaurants:
When the server prints out a pre-payment receipt, if a cash discount option has been configured properly, the receipt will list both a cash price and a credit price. Once the order is paid for, it will only show the price based on the payment type.

Note on mixing payment types on an order / receipt:
If you add a cash payment for less than the entire amount of the ticket, when you add a non-cash payment, the system has to remove the cash discount on the other payment. If you need to split a ticket in a way so that someone can pay cash and non-cash, you would need to break up the ticket using split instead of trying to apply multiple payments to the same ticket.

### Credit Service Fees

This refers to a fee that is added to an order when the customer is paying with a credit card. All of the pricing in the system in this scenario would need to reflect the *cash* price for the items.

You can configure the system to either add the service fee into the order, or you can configure the system to allow the credit card processor to add the fee.

#### *Using the POS to add the fee*

Create a service charge in the system, set to the "Dual Pricing" type, and select the applicable payment type (e.g., the configured credit card processor). 

You can set a flat fee, percentage fee, and max fee amounts as required for the use case.

The system will then add the service charge to all applicable orders.

If you need to process an order without the fees, you can use the "Disable Fees" button in the order options panel.

#### *Using the credit card processor to add the fee*

Configure your processor to add the applicable fee to transactions.

Create a service charge in the system of the "Payment Provider" type and select the applicable payment provider.

### Dual Pricing

In most cases where people talk about "Dual Pricing", they generally either mean a cash discount or a processor fee (See above).

Nimble can do true dual pricing, but that creates lot of management overhead for the customer, and the customer needs to be aware of the ramifications of that.
*It is not recommended for most clients to actually implement a true dual price solution.*

To use dual pricing, set up price rules in the system for both cash and credit pricing. You can either tie these to the payment type, or to a service type if that makes more logical sense for your workflow. See below for details.

You will need to set the price for both price rules. This does allow for maximum control of the pricing versus other methods. For example, an item that has a cash price of $10.00 and your credit pricing is 3% higher, using methods like a service charge would result in a final price of $10.30. Using dual pricing, you could make the item $10.50 or $10.25.

Also, if you have multiple other pricing rules that have to follow a dual pricing model, you will double up on each pricing rule. 

For example, if you have the following pricing rules:
- Lunch
- Happy Hour
- Friday Special
- Weekend
- Standard

You would need to make a pricing rule for each version:
- Lunch Cash
- Lunch Credit
- Happy Hour Cash
- Happy Hour Credit
- Friday Special Cash
- Friday Special Credit
- Weekend Cash
- Weekend Credit
- Standard Cash
- Standard Credit

#### *Using Service Types instead of Payment Type*
Consider using a cash vs credit service type for fast casual and retail scenarios.
Selecting a service type can be forced up-front when the order is created. This allows the system to be aware of the pricing before the time of payment. Otherwise, the system will select the pricing type based on pricing rule order until a payment type is selected.

In order words, if your cash price is a higher priority than your credit price, an order may ring up as $20. When the customer goes to pay with their credit card, the order will suddenly jump to $21.50 (for example), because now the system is aware of the payment type.

However, to use this method of dual pricing, you would need to configure both the additional price rules, but also additional service types to use them.


To configure discounts, go to the "Discounts" section under the "Configuration" gear icon.
![image](https://github.com/user-attachments/assets/d696924f-9fdf-46e7-839c-be178ac8def3)


Discounts are broken into categories / groups for access in the register. The different groups configured will show on the left side of the discounts page, with all discounts in that group listed in the main portion of the screen.
 
To add a discount, tap or click "Add"

![image](https://github.com/user-attachments/assets/8ab2bd8b-d417-404e-a524-9b4eb72f11f2)

 
Discounts must have a name. This will show up in the register, but you can also choose to set a Receipt Name to display a specific name to a customer that may or may not be different from the discount's name.

Discounts must have a name. This will show up in the register, but you can also choose to set a Receipt Name to display a specific name to a customer that may or may not be different from the discount's name.
 
For example, you could name a discount in the system "$10 for $50" but on the receipt label the discount "Coupon Promo". The first helps your employees choose the correct discount, the later is for your customers.
 
Discounts can be configured with a minimum permission - typically server or cashier, but you can also set discounts that require higher permissions, such as shift lead, assistant manager, or manager level.
 
The Discount Group is the logical group the discount belongs to- the list on the left in the discount screen.
 
Discounts can be of any of the following type:
* Item Level, Fixed Dollar Amount
* Item Level, Variable Dollar Amount
* Item Level, Fixed Percentage Amount
* Item Level, Variable Percentage Amount
* Order Level, Fixed Dollar Amount
* Order Level, Variable Dollar Amount
* Order Level, Fixed Percentage Amount
* Order Level, Variable Percentage Amount
* Auto Order Discount, Fixed Amount
* Auto Order Discount, Fixed Percentage
 
Variable discounts - dollar or percentage - will prompt for an amount to be entered when they are added to an order.
 
Item level discounts will require the user to select a qualifying item on the order to be discounted.
 
Automatic discounts will be applied as soon as the conditions for the discount are met.
 
Discounts can be stacked on an order, and will process in the way most beneficial to the store. For example, a $10 order with a 10% discount and a $1.00 discount would process the $1.00 off before the 10% Discount, resulting in a final pre-tax price of $8.10. The order the discounts are added will not impact this.
 
A max discount amount can be set. For example, a discount can be created for 25% up to $10. 
 
A minimum order amount allows the discount to require the order be over a specified dollar threshold (pre-tax) before it can be applied.
 
The Max Per Order setting allows you to control how many of the same discount can be applied to an order. For example, the default value of 1 will only allow a single instance of the discount to be applied to an order.

The Barcodes button allows you to enter in a list of barcodes that are associated with the discount, typically used for coupons.

![image](https://github.com/user-attachments/assets/ca773435-9703-46cf-af09-3ac9b7ec6277)

A discount can be set to override item pricing rules. Item price rules can be set to not allow discounting- for example, for items that are on special or are non-discountable due to regulatory requirements. A discount can be set to override these rules. For example, a manager may need to discount an item even though it's being sold at a special, non-discountable price. See "Pricing Rules"
 
By default, discount rules do not override the order-pricing "do not discount" flag unless specifically set to do so. Items on an order that are set to not be discountable are not eligible for item level discounts and may be excluded from order level discounts unless the discount behavior is changed.
 
Discounts can be set to require an Action Reason. Action reasons are notes that an employee may be required to use to explain why a discount was used. Action reasons can be typed in manually, and pre-defined action reasons can be set up under the "Action Reasons" configuration option.
 
The next page of a discount definition allows for additional limitations or definitions of the discount to be configured, including:
 
* Date range the discount is available, typically used for limited time offers
* Days-of-the-Week a discount is available, typically used with special offers such as only being valid on a Tuesday or a weekend.
* Time-of-day Availability, typically used to limit a discount to certain times of the day, such as a lunch discount.
* Service Types, allowing discounts to be limited to dine-in only.
* Payment Types, which allow discounts to be configured for specific payment types, such as a cash discount.
* Menu Items, allowing a discount to only be applicable to specific items
* Tags, allowing a discount to be limited to only items with matching tags applied to it
* Departments, allowing a discount to only apply to one or more configured departments. 
 
 
These options can all be combined to create discounts that are only valid under very specific circumstances and scenarios, helping to limit opportunities for your employees to mis-apply discounts.

![image](https://github.com/user-attachments/assets/f645c577-ddbc-4d42-8331-08a366152730)

## Note on Cash Discounts
To create an automatic cash discount that will show as a option on a pre-payment receipt, you will need to create a discount using one of the automatic order discounts, and set the required payment type to a cash payment type.
 
If you have set up a cash discount, the cash payment total will show up on the receipt, along with a credit total.
 



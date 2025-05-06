## Menu Items
 
Menu Items are the list of items that your store is selling. 

Note that “Menu Items” refers to the terminology used for restaurant and food-focused personas. For details on item management for retail focused personas, see the “Retail Persona” Section
 
To add or edit menu items, select "Menu Items" from the "Menu" configuration option.
 
Menu departments are listed on the left side of the screen. Tap on a department to see the list of items in that department.
 
If an item is not in a department, it will be listed in the "Uncategorized" option at the bottom of the department list.
 
You can add or edit a menu item, or bulk add a list of items all at once.

![image](https://github.com/user-attachments/assets/22022d9b-e198-4249-9c14-1c21e025a459)

All items must have a unique name in the system. E.g., you can't have an item "chicken tenders" and another item named "chicken tenders" that is a separate item only used for adding chicken tenders to another entree. 
You can have "chicken tenders" and "+ tenders" or "add chicken tenders"
 
Short names are optional. Kitchen print receipts will print use short names on items where they are provided, and use item names if a short name isn't set.
 
Barcode is the barcode string value to use for the item when using barcodes. 
 
PLU is an item number that is searchable with the item search function.
 
To add an item into a department or move an item to a new department, type in the department name into the "Department" field. 
 
If the department doesn't exist, it will be created.
 
You can toggle an item between "in stock" and "out of stock" by changing the "Stock Status" switch. An out-of-stock item will still show in the register, but will be greyed out and cannot be added to an order.
 
You can set the item's Sort Order to determine the order the item will be listed in the menu. Items are sorted by sort order from lowest to highest, and inside of a given sort order in alphabetical order. You can assign every item in a department in a specific order in the system, or assign the top items specifically and allow the remaining items to be in alphabetical order.
 
 
Marking an item as an "Inventory item" will set it to be an inventory trackable item. For restaurants, this would typically be used for ingredient level items.
 
If you enable the “Top Item” option, the item will also appear in the “Top Item” department in the Front of the House. If no items have “Top Item” enabled, the “Top Item” department will not show up in the FoH.

<img width="540" alt="image" src="https://github.com/user-attachments/assets/d7ae4b22-640f-4021-a3c8-e80961c0d173" />


### Selling by Weight
If you set an item to be sold by weight, when the item is added to an order, you will be prompted to enter in a quantity being sold. If you have an attached scale (see scale configuration), it will prompt you to read the scale.

Items priced by weight take the quantity from the scale or manual entry and multiply it by the item's configured price. For example, if an item is $10 and you sell a quantiy of 1.5, the item will be 1.5x $10 = $15.

### SKU pricing

To sell an item with the price embedded in the SKU (typical at a deli, fish market, etc) that use external scales, you can mark the item as sold by “Price in Barcode”

You will be prompted to configure the SKU price for the item.
Most scales will have 1 or 2 digits at the right-most part of the barcode that are not used for pricing. Those are the “right pad digits”.

You will also need to configure a number of pricing digits. Most scales will output 4 or 5 digits, with a maximum scale amount of $99.99 or $999.99 respectively. Many scales will also have one or two digits to the left of the price. You do not need to enter the number of left padding digits.

![image](https://github.com/user-attachments/assets/07b44f0e-d04d-427e-9a6b-1b78c57dcdfc)

Note that the item’s configured barcode will be the barcode without a price or padding digits. For example, a barcode may be 203016 with 4 pricing digits and 1 right pad. 
For an item priced at $21.43, the actual barcode from the scale may be 203016621430, which includes one left-pad digit (the second ‘6’) that is ignored by the system.

## Tags

Tags are labels that are applied to items that can use used for different things, including:
 
* Print Routing
* Loyalty
* Grouping Items together for option group and substitution selection
* Grouping items together for discount eligibility
 
Items can have multiple tags applied to them, so an item can be a member of a "Salad Dressing" and "Salad Print" tag group, for example.
 
To add a tag, type in the tag name in the entry box. The field is a type-ahead box, so you can enter in a partial name to show a list of matches. Tap on a match to add it to your list of applied tags.
 
If the name of the tag you enter does not exist, adding it to the item will create the tag.

![image](https://github.com/user-attachments/assets/88025dc9-7ac1-4349-92a4-5d23612b37d9)

  
## Build Items / Ingredients
 
Build Items are the inventory items that make up an item your store is selling.
 
An item does not need to be configured with build items at all. However, adding ingredients allows for cost of goods sold tracking and for menu modifications.
 
 
To add an ingredient or build item to an item, type in the name of the item in the search box. Any items that match your search will appear in the list and you can select the matching item. If the item name you typed in does not exist, it will create a new ingredient / inventory item for you in-line that can be used or referenced by other items in the menu.
 
You can remove an item by using the red X to the right of the item.

![image](https://github.com/user-attachments/assets/8ce2ec54-e34f-48ca-b15b-1ece041f3af1)

The gear icon allows you to adjust the allowed quantity modifiers (See Quantity Modifiers) and set the inventory usage for the item.
 
If you wish to add a price adjustment to a quantity modifier, you would add it here.
 
The bottom row - the "Quantity" tells the system how many of your build item you are using in menu item. This is only needed if you are concerned with tracking your cost of goods sold at a granular level. See "Packaging" under "Inventory Management"

![image](https://github.com/user-attachments/assets/3a5cd9d0-54c9-4b6e-8cb8-086066cccb02)


**Note- Do not add an ingredient of the same name as the parent item to the build items as this will create an infinite recursion in the system.**
For example, if you create a menu item named "Bacon" and add an ingredient "Bacon" to the item- it will not create a new ingredient item "Bacon", it will attach the menu item to itself.
 
If you do this, the register will note this when you add the item to an order. As you can see below, the order as an ingredient of "bacon", and under "bacon" it is showing the ingredients - in this case, also bacon. The yellow triangles tell you that you have added an item as its own ingredient. This doesn't hurt anything in the point of sale, but it may cause your employees to ask about the yellow warning triangles.

![image](https://github.com/user-attachments/assets/819ce9b8-4034-4bc2-bc3f-3e4876a3e0d4)

Note - When using workflow steps, you can attach workflow steps to ingredient items. For example, if you have a workflow option group "Meat Temp", you can attach it to a "Steak" build item and force the item to process that flow in order with option group workflow items.

## Option Groups
Option Groups allows you to attach option groups to an item.
 
An option group could be a selection of side items, a meat temperature modifier selection, salad dressing choices, or virtually any other selectable modification. See "Option Groups" for more details on option groups.
 
To add an option group to an item, start typing the name of the option group into the field. The field will search ahead for matches, and when you see a match you can tap on it to add the option group to your menu item. If the option group does not exist, a new one would be created with that name and you can configure the option group later under the "Option Groups" page.
 
Note - You can add multiple of the same option group to an item. For example, if a menu item has two side options, you can add the option group "Sides" to the item twice.
 
The red X will remove an option group from a menu item.
 
If you are using workflow style modifier groups, you can specify the workflow order that the option groups will be presented in. Workflow steps are processed in order, from the lowest number to the highest number.
 
Note - If you have multiple workflow items with the same workflow step, they may not be processed in a consistent order. If is strongly recommended that stores using forced workflow steps give unique step numbers to each option group they want processed for an item.

![image](https://github.com/user-attachments/assets/8fc070c7-4988-4f55-9988-0476773f82a6)

## Pricing Rules
 
The last stage of creating a new menu item is to set the item's price.
 
The point-of-sale system allows for an item to have different prices based on the context. This is different from many systems where an item would need to have multiple buttons in the system to have a different price. For example, an item "Cosmo" might require a button for the regular price, and another button for a "Happy Hour" price.
 
This can be very confusing when an item may have different prices for lunch, dinner, happy hour, the weekend, and Sunday brunch. Having multiple buttons can also lead to the server using the wrong button to add - and thus, the wrong price - an item to an order.
 
For every pricing rule configured in the system (See "Pricing Rules"), the item will have an option to set a specific price for that item and pricing rule.
 
Pricing rules are checked one at a time in order (from top to bottom) to see 1) If a pricing rule matches and 2) if there is a set price for that rule.
 
If a price rule is valid but no price is set, the system will check the next rule in order.
 
If no price rule matches, the item will show in the menu but will be disabled as if it were out of stock.
 
To set pricing for an item, enter in the price for the item for the given pricing rules. If you only have a single pricing rule, there will only be one row to fill out. 
 
Note - You do not need to set a price for every rule unless the rule will change the price. For example, if an item is $10.75 for dinner, you do not need to set a price of $10.75 for lunch as well.
 
You can mark any price as non-discountable. Note that discount rules can be configured to override that setting - typically manager-only discounts.

![image](https://github.com/user-attachments/assets/f185d9be-2266-4985-979b-355823da385f)

You can also set which configured taxes in the system apply to the item. If no taxes are set, the item will not be taxed when it is purchased.
 
For new items, all taxes marked as "default" will be automatically enabled on the item. You can tap on the switch next to the tax to enable or disable that specific tax on the item.

![image](https://github.com/user-attachments/assets/77458189-d1c9-41ef-9ada-fa6ade43f98d)


### Notes
* An item with a variable price would still need a price of $0 to be available on the menu. If there are no matching price rules with a value in them, the item will not be available on the menu for purchase.
* You can set the price of a variably priced item as higher than $0; If an employee does not set the item's price, it will treat the price you set as a default price. 
 * For example, you could create a "Market Price Fish" with a price of $32, but set the item to be variably priced. If the employee doesn't set the price, it will still ring up at $32. 
* You can have as many variable priced items as you want.
 



Print Rules determine when an item will be printed, how it will be printed, which device it will print to, and which receipt type it will use to print.
 
When printing, ALL applicable print rules are executed, so if there is a rule for a receipt print and a kitchen print that both match, the system will print both.
 
To configure print rules, select "Print Rules' under the "Configuration" gear icon.

![image](https://github.com/user-attachments/assets/15d1a38c-6941-4ff4-bc4d-a0a6d1adaa2d)

Print rules are broken into Print Rule Groups, allowing a manager to create different groups of rules for different scenarios. For example, a restaurant may have a "Regular" printing rule set and a "Slow Day" printing rule set that will route kitchen printing and bar printing differently because there are fewer staff.
 
The Heart icon next to a print rule group name on the left indicates the print group is the active print group. Tap on the "Edit Print Groups" to change the active print group. Only one group may be active at a time.

![image](https://github.com/user-attachments/assets/4cb8b0c1-0f24-4c51-94b9-40730dfa52c9)

To create a new print rule, tap or click the "Add" button.
 
Print rules must have a name and a print rule group. 
 
The print receipt dropdown will allow you to select the receipt type you want the print rule to trigger.

![image](https://github.com/user-attachments/assets/c76da5ba-2cc2-41d9-b9bb-b5f85b83eaf0)

Print style allows for setting if you want the configured receipt to print all items or only the new or changed items. This is typically used in a kitchen printing situation.
 
Print scale allows you to adjust the scale the printer is using. For example, if you find a particular print is a little small, you can adjust the scale to 1.2 to increase the sizes 20%.
 
Print quantity will set how many copies of a receipt are printed.

If you are using a Network Print Server, you can set the print rule to send the print job to the network server instead of printing locally. This is most commonly used with mobile devices, such as iOS or Android tablets. 

Tap Next to go to the Print Triggers page.
 
A print rule will need one or more print triggers- events or buttons in the register that are used to trigger processing the rule.
 
The prompt for Email and Prompt for Text allow for receipts to be emailed or sent SMS to a customer. 
 
Note that email and text receipts may be billable.

![image](https://github.com/user-attachments/assets/c9917a89-c762-4d02-a171-fbd6579e68ff)

The Registers and Service Types allow you to determine which registers will trigger the rule and which service types are applicable. 
 
For example, you could set a rule up just for a carry-out service type to use a special carry-out receipt.
 
A rule can be applied to multiple registers. 

![image](https://github.com/user-attachments/assets/441c2de3-d04d-4c71-895a-1f8de0de1963)

The print rule printers set the printer or printers that a print rule will utilize. 
 
Printers are selected by the name of the printer on the device. If you tap on the "search or add" field, it will list available printers on the device, but you can enter in a name that doesn't match if you plan to install a printer with that name later.
 
This allows you to create a rule that applies to 5 registers to all use a printer named "receipt", but each register has a different physical printer the "receipt" printer is pointing to. 
Alternatively, you can just leave the printer field blank and the system will use the default printer for the register (See Register Configuration). Using a default printer is the preferred method for receipt printing.

![image](https://github.com/user-attachments/assets/a1226523-85df-4f63-8a07-4468b95c8117)

You can limit a print rule to only print items with specific tags. For example, you could set a print rule up that only prints items with a "Grill Print" tag to print to a printer by the grill, while a rule with a "Salad Print" tag is used to print items to a cold station printer.
 
If you do not specify any tags to print, all items will be printed.
 
![image](https://github.com/user-attachments/assets/40e0faf0-a9b5-44c9-9863-21b22b13117a)
 
Likewise, you can specify one or more tags that can be used to exclude items from the print rule. 
 
Exclusion tags can be used independently of inclusion tags.
 
For example, if you do not specify inclusion tags it will print every item. If you add an exclusion tag for "Drinks", the rule will print everything but items marked "Drinks"
 
If you specific inclusion tags and exclusion tags, it will only print items that are in the included tags but not in the excluded tag list. Excluded items take priority over included tags.
 
![image](https://github.com/user-attachments/assets/23198a8b-961b-45b7-8519-f18bceffbeab)









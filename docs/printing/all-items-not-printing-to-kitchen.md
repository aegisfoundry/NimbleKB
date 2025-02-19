Check the print rules to see what print tags, if any, are set.

For example, if you have a rule to print items tagged "grill print" to a printer "grill", then all items that should print to that printer must be tagged "grill print". 

Check the print rule's exclude tags. For example, a salad could be tagged "expo" and "salad print", but if the expo printer is set to exclude "salad print", then the salad won't print to that printer. Exclusions win out over inclusions, unless a lower down inclusion exists. E.g., the grill printer is not set to print "salad", but if a salad has an optional "add steak" that's tagged to go to the grill it will print anyway.

Or put another way, if a root item prints, child items will print IF they are not set to exclude, or IF they are set to exclude BUT a lower level item in their structure is set to include.![image](https://github.com/user-attachments/assets/da1cee92-8dc5-44f2-9fee-f231ecc37824)

﻿<img width="652" alt="image" src="https://github.com/user-attachments/assets/07258564-fc71-469b-ae02-a6488d30bb3a" />

Check the order's audit log. The audit log will show which items were printed and which items were excluded. You may also want to run a tag audit for the store to ensure items are tagged correctly for your include / exclude logic.![image](https://github.com/user-attachments/assets/e70ca110-8aea-4cb6-ab9c-7a8d7809470e)

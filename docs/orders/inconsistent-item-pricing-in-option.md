## I have an option that rings up at differnt prices, even in the same item.

## Troubleshooting

Check the option group for the parent item. For example, if the parent item is "Grilled Chicken Plate" and it has an option group of "Side Selection", you would check the "Side Selection" option group.

If the option is set to "use menu item pricing", ensure that the item's price rules are configured correctly. For example, if an option item has a "regular" and "happy hour" price, then the item will have different prices based on price rule logic.

Also ensure that the option is not defined twice in the option group.

For example, the "side salad" option below is set as an item rule and set to use menu item pricing, which is set to $3.99

﻿![image](https://github.com/user-attachments/assets/74752d73-80d2-4f79-8242-d6250908cd1d)

However, the "side salad" is also configured with the tag "Sides", which in this example is included in the option group definition for $1.99

![image](https://github.com/user-attachments/assets/e922ef33-da84-43bc-8594-de8fa51b3a65)

If that is the case, you will need to exclude the "side salad" from the tag rule.

﻿![image](https://github.com/user-attachments/assets/84c6a1a3-11f8-43a9-9dab-fa6c09099cb5)

If an option item has both an item rule and tag rule with different pricing, the system may return price adjustment inconsistently.



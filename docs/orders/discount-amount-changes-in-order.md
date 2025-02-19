**Symptom**
A discount amount in an order changes when adding / removing items.

This can happen because of the order of operations on how discounts are applied. For consistency, discounts are calculated in the following order:

	1. Item level discounts, fixed dollar amount
	2. Item level discounts, variable amount
	3. Order level discounts, fixed dollar amount
	4. Order level discounts, variable dollar amount

This order of applying discounts will minimize the impact of the discounts to the store. For example, if you have the following:

	• An order for $10
	• A $1.00 off item discount
	• A 10% off order discount

The system will first apply the $1 discount, taking the order down to $9.00 before applying the 10% order discount, which will ring in at $0.90 (10% of $9.00) for a total due of $8.10

If you added the order level discount first (10%) on the $10 order, it would first show up as a $1.00 discount, but when you add the $1.00 item discount, it will recalculate to $0.90.

# Symptom
A store is trying to use a cash discount - a discount automatically applied when a customer pays in cash. A receipt that is printed prior to payment should show the cash and the non-cash price. but the receipt only shows the non-cash price.

# Troubleshooting
In order for cash discount to print on the receipt, all of the following must be true:

There is a discount rule for the cash discount:
- The discount is of type auto order. Manual order discounts and item discounts (manual or auto) will not work.
- The discount is a set percentage. Cash discount cannot be a variable fee and cannot be a dollar discount.
- The discount has a receipt name.
- The discount is set to override item rules.
- The discount is set to only apply to cash payment types.
- The receipt XML has cash discount lines in it.

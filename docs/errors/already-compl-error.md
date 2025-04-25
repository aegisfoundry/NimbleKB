## When running a payment, the system returns an "ALREADY COMPL." error

﻿![image](https://github.com/user-attachments/assets/a3dee229-e256-4575-b65a-3db461d2bf4b)

## Troubleshooting

The transaction was already completed. Basically the POS and the payment provider are no longer in sync.

Typical example causses:
* Converting a preauth to a sale, then closing the POS in the middle of the transaction but after the card reader has engaged.
* Engaging a payment in the POS, then canceling the transaction from the POS after the customer has swiped their card but the system has not returned an approval yet.

If you attempt to re-run the transaction, you will see this error.

To fix, you will need to close out the order using a POP payment, house account, or manager discount. The payment has been made with the payment provider and the store has not lost money, but the POS is unaware of the transaction having been completed due to user errors.

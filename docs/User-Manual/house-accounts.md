## Configuring House Accounts
The point-of-sale system offers an integrated house account system. 

House accounts allow stores to pay for orders/invoices with an account number that can be reconciled at a later date.

While similar to POP accounts, house accounts offer better tracking and differentiation of charges. However, unlike POP, house accounts require internet connectivity to operate. 

After configuration, house accounts operate like other payment processors and can be set with required permissions to use (e.g., you can require a manager to charge an order to a house account). Note that permission requirements are global to house accounts and are not account-specific. You cannot allow servers to use some house accounts but require a manager for others, for example. 

![image](https://github.com/user-attachments/assets/2f7c0c82-727c-4a20-8924-2116545f90d5)

You will also need to ensure that the payment provider has been configured for any register that you want to be able to use house accounts.

![image](https://github.com/user-attachments/assets/db89f5cb-dc7c-4642-b307-2a61f607cb72)


A house account starts at a zero balance, and any charges will be deducted from the balance.

To configure individual house accounts, click or tap on the “House Accounts” item in the apps configuration.

![image](https://github.com/user-attachments/assets/f519450a-533a-4fe4-b947-54bfe18e1759)

To add a house account, tap “Add”, or “Edit” to edit an existing account.

![image](https://github.com/user-attachments/assets/c64a6857-f650-4e97-9304-822b6e6d90d0)

A house account will require an account number and name. The account number must be a number, you cannot use alpha or special characters in that field. 

If the house account is tax-exempt, you can set the flag here. If you set the account to be tax-exempt, you will be prompted for a tax ID.

You can optionally set contact information for the house account, including phone numbers, email addresses, and address information. These fields are optional.

![image](https://github.com/user-attachments/assets/bc1e5d38-5e84-44ca-81b0-bf8b215cbffa)

## Viewing House Account Transactions
To view recent transactions for a house account, tap on the account and then the “Transactions” button. This will show the last 10 transactions on the account.

## Applying an Account Adjustment

House account adjustments can be used to either apply a payment to a house account, or create an external payment record. 

To apply an adjustment, tap on the account and tap or click on the “Adjustment” button.

![image](https://github.com/user-attachments/assets/f384042f-96a9-44df-b8c2-981aa1ec9ed6)

You will need to choose a transaction type- a credit (adding a payment to a house account to offset charges), or a debit (adding an external transaction made outside of the point-of-sale system).

For example, if you are using a house account for catering and a customer has sent a $5,000 payment via a check, you can add the payment by creating a credit record for $5,000.

### Initiating a Payment for a House Account from the Back Office
You can apply a payment to a house account by first selecting the account by tapping or click on git, and then tapping or clicking the “Payment” button from any authorized register with at least one configured payment provider.

**You can only pay a house account from an authorized register. If you are just on computer with back-office access, you would need to do an adjustment instead.**

![image](https://github.com/user-attachments/assets/29147604-c96f-464e-908a-b49d412bb20b)

The payment button will show a list of configured payment options for the register. Typically, you would use your credit card reader to run a customer’s card, but you can also record taking a check, taking cash, or even pay off one house account with another.

![image](https://github.com/user-attachments/assets/59f7422f-f579-4c11-acba-3f8dcd95fdb5)

You will be prompted to enter in a payment amount. By default, the payment amount set will be the balance on the account, but you can clear that and apply a partial payment if needed.

![image](https://github.com/user-attachments/assets/6008b152-8c63-4105-b385-993e1dfe500f)

If your payment method is a credit card, your credit card reader will activate and it will run the charge. 

Once the payment process has completed, the system will apply the payment to the house account as a credit, reducing the balance by the amount paid.
If the balance is already at zero, or the amount paid is greater than the balance owed, the account will have a positive balance.

### Note:
* Cash discounts do not apply when paying a house account.
* Dual Price surcharge fees do not apply when paying a house account. 
* Provider service charges- e.g., charges added by the processor – will apply, and will result in an overpay on the account. You will need to do a manual adjustment to correct that.

## Using a House Account to Pay for an Order
You will need to ensure you have created at least one house account in the back office and configured a house account payment provider option.  Please see the section on configuring house accounts for more information.

When you select the house account payment provider in the point-of-sale, you will be prompted for the account number. Enter in the number you configured in the back-of-house.

### Note:
* Internet access is required for house account functionality.
* A house account will always approve; There is no method to limit the balance of a house account.
* You can place a permission on the use of house accounts in general so that only a manager may use them, but you cannot limit access to specific accounts.

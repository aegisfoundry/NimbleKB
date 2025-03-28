# Symptom:
I am getting a change prompt on a credit transaction. For example, I run a $10 charge and the system will respond with a prompt for $0.30 in change.

# Troubleshooting
The most likely cause is that your credit card processor is configured to add a credit surcharge but the system is not configured with a payment provider surcharge in the system.

To verify if that is the cause, check your receipt. You in the example above, despite the order being $10.00, the reader would have approved $10.30.

Go into the back office, go to configuration, and then service charged. Ensure that you have a payment provider surcharge configured for that payment type.

# Troubleshooting the Customer Facing Display Application

## Symptom

The customer facing display never shows on the device.

- Verify that the "use as second screen" option is configured in the payment processor (Pax)
- Verify the correct app is installed. It will be the CFD app from Nimble Technologies. The icon is a payment processor with a flame behind it.
- Start the app manually; the app must be run manually one time before it can auto start correctly.

## Symptom

The customer facing display is stuck on "waiting for pos commands"

- Verify that the IP address in the register configuration for the payment provider (pax) matches the device.


## Symptom

The customer display app is jumping back and forth between orders and/or the orders are corrupted

- The most likely cause is two POS registers sharing the same credit card reader AND both are configured to use second screen. The CFD app is not able to safely handle multiple devices trying to talk to it at once.

## Symptom

The CFD is jumping between different color schemes

- The CFD gets the theme information from the POS register. If you have different users with different color themes applied at the user-level (supported but not a typical configuration), the CFD may change color themes as different employees log in.

## Trying to make a payment on a PAX device returns an "UNSUPPORT EDC" or "UNSUPPORTED EDC" error

## Troubleshooting

There are multiple EDC error types. 

### Troubleshooting 100004 Errors

The transaction type is not supported. For example, the POS was configured to allow a debit transaction but the device was not configured to allow a debit card transaction. Check your configuration on the POS and the register device to ensure all transaction types are correctly configured.

### Troubleshooting 100005 Errors
The device configuration is invalid or corrupt. Try pushing the configuration to the device again.

If the error persists, check your device configuration or device configuration template for possible problems.

### Troubleshooting 100008 / 100009 / 10010 Errors

These generally indicate a device communication problem. 

The device may be offline - check the customer has internet and the device is connected to the network properly. 

Restart the payment device.

It may be possible for these errors to occur if the payment network or gateway are down. If that is the case, you may receive a large number of similar complaints at the same time.


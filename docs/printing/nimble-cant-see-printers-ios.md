# Symptom
My ipad / iOS device cannot see any printers or is not printing.

# Troubleshooting
iOS can utilize two print methods.
1. iOS Native Printing
2. Nimble Print Server Printing

For iOS Native printing
- The printer MUST support Airprint. If the printer does not support airprint, it will not see the printer with OS direct printing.
- Ensure the printer is on and connected to the same network as the ipad. 

For Nimble Print Server Printing
- Ensure the print server is running.
- If the print server is utilzing Windows printing, ensure the nimble listener and print server sevices are running.

Both
- Check the store's error log in support tools
- If you have an order number, check the audit log for the order.

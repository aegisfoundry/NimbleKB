# Print Triggers
Print triggers determine when a given print rule is fired. Below is a comprehensive list of when each trigger is called.


## Order Related Triggers

### On Close
- **Close Order** button is pressed.
- **Print & Close** or **Close Order** is pressed (Fast Close Order mode).

### On Reprint
- **Print and Close** is pressed (Fast Close Order Mode).
- **Reprint Receipt** in More Options modal is pressed.
- **Reprint Ticket** in Order Management window is pressed.

### On Fire
- **Fire to Kitchen** button is pressed. (Restaurant Modes)

### On Refire
- **Refire Receipt** button is pressed from More Options Modal. (Restaurant Modes)

### On Payment
- When **Add Payment Modal** is closed after successful transaction (not in Retail currently).

### On Reprint Payment
- **Reprint Payment button** is pressed from More Options Modal.

### Prompt for Email

### Prompt for Text

------------------------

## Process Related Triggers

### Register Report
- **Print Summary** is pressed from Order Management Screen.

### Closing Report
- **Print Closing Report** is pressed from Manager Panel (Order Management Screen).

### Pay In
- Paid In is added successfully from Manager Panel (Order Management Screen).

### Pay Out
- Paid Out is added successfully from Manager Panel (Order Management Screen).

### On Error
- Immediately after either an **On Fire** or **On Refire** print job fails.

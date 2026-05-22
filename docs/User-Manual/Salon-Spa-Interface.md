# Salon Spa Interface

Converted from `Salon_Spa_Howto.v1.0.docx`.

## Contents

- [Terms](#terms)
- [Schedule View](#schedule-view)
  - [Today View](#today-view)
  - [Creating Walk-in(s)](#creating-walk-ins)
  - [Creating Scheduled Appointment(s)](#creating-scheduled-appointments)
- [Employee Assignment(s)](#employee-assignments)
  - [Choose Order Owner](#choose-order-owner)
  - [Assign Employee](#assign-employee)
  - [Unassigned Queue](#unassigned-queue)
  - [Assign Unassigned Order(s)](#assign-unassigned-orders)
  - [Assign Order](#assign-order)
  - [Auto Assign](#auto-assign)
- [Customer Lookup and Creation](#customer-lookup-and-creation)
  - [Customer](#customer)
  - [Guest](#guest)
  - [Phone Lookup](#phone-lookup)
  - [Add Family Member](#add-family-member)
  - [New Customer](#new-customer)
  - [Family Members](#family-members)
- [Tipping](#tipping)
  - [Close Order](#close-order)
  - [Cash Tipout](#cash-tipout)
  - [Print](#print)
  - [Splitting Tip](#splitting-tip)
- [Back Office](#back-office)
  - [Creating New Rental/Service Item(s)](#creating-new-rentalservice-items)
  - [Employee Commission(s)](#employee-commissions)
- [Customer Facing Waitlist Configuration (Optional)](#customer-facing-waitlist-configuration-optional)
- [Operator Cheat Sheet](#operator-cheat-sheet)

## Terms

- **Assign Employee**: The window where you choose which staff member will perform a service. It appears when a service needs a provider before the order can move forward.
- **Unassigned Queue**: A holding area for service orders that do not yet have a staff member assigned. Once someone is selected, the order leaves the queue and becomes an active assigned order.
- **Schedule view**: Shows appointment timing and staff availability in a timeline format. Use it to book, move, and manage appointments throughout the day.
- **Customer Lookup**: Helps staff quickly find the correct customer record, typically by phone number. This ensures services, preferences, and history are attached to the right person.
- **Service Types**: Categories (order format and rules) used to organize services. They help control setup, reporting, and which employees can be assigned. Example: whether pre-auth, guest info, or other order requirements apply.
- **Service Item(s)**: The actual service being performed for the customer. It usually needs a staff member assignment and is tracked for scheduling, time, and commission. Example: haircut, color, facial.
- **Rental Item(s)**: The resource being rented or used for the time, not a hands-on service. It is tracked as a rental usage item rather than a hands-on performed service. Example: chair, room, equipment rental.
- **Commission Setup**: Configured in Back Office, not during checkout. It defines how staff earnings are calculated for services they perform on a commissions report.
- **Auto-Assign (Orders)**: When an unassigned order is claimed by an employee, the system automatically assigns any eligible unassigned service items to that employee for you.
- **Close Order Window**: The final check screen before you finish the sale.
- **Tip Split Prompt**: A screen that asks, "Do you want to share this tip with another employee?"
- **Tip Cash Out**: A step to record that tip money is being paid out in cash.
- **Print Option Prompt**: A screen that asks if you want to print a receipt and how.
- **Auto-Assign Tip Split (one employee available)**: If only one valid employee can receive tips, the system fills in automatically so you do not have to.
- **Order Screen**

## Schedule View

### Today View

#### Creating Appointment(s)

##### Walk-In(s)

###### Creating Walk-in(s)

- From the Today View, click **New Walk-In** from the Schedule View.
- The system prompts the user to choose an order owner.

![image](https://github.com/user-attachments/assets/f0d18572-3953-4722-8aab-4f4edc6c70b7)

- Select an employee, or select **Unassigned** to add it to the Unassigned Queue.
- The system refreshes and takes the user to the Customer window.
- Select a customer.
- The Customer window closes and the user is taken to the Order Screen.
- Select a Service Item, Rental Item, Product, and so on to add the order.
- If **Service Item**:
  - The user is prompted to **Assign Employee**.
- If **Non-Service Item**:
  - The user is returned to the Order Screen.
- Click **Store Order** to return to the Schedule View.
- The order appears in the assignment queue, unassigned or assigned, for the selected time slot.

#### Scheduling Appointment(s)

##### Creating Scheduled Appointment(s)

- Select **Schedule** at the top of the Schedule View.

![image](https://github.com/user-attachments/assets/5ebc0091-65d4-49e4-8fd8-f7ee55b313b9)

- Select **Date** and the calendar window appears.

![image](https://github.com/user-attachments/assets/91267db6-c074-425a-90ec-6fefa4146358)

- Select the date for the appointment.
- The system refreshes showing all appointments for the selected date.
- Click **Schedule Order**.
- The Schedule Order window opens.

![image](https://github.com/user-attachments/assets/3b986923-af55-429c-8d63-32a92907ad33)

- Select the applicable date and time.
- Click **Done**.
- The **Choose Order Owner** window opens.
- Select an employee, or select **Unassigned** to add it to the Unassigned Queue.
- After a selection is made, the Customer window opens.
- Select a customer.
- The Customer window closes and returns the user to the Order Screen.
- Select a Service Item, Rental Item, Product, and so on to add the order.
- If **Service Item**:
  - The user is prompted to **Assign Employee**.
- If **Non-Service Item**:
  - The user is returned to the Order Screen.
- Click **Store Order** to return to the Schedule View.
- The order appears in the assignment queue, unassigned or assigned, for the selected time slot.

## Employee Assignment(s)

### Choose Order Owner

- This window lists the employees that have logged into the system today.
- The user can assign the order either to an active employee or select **Unassigned**.
- Selecting **Unassigned** adds the order to the Unassigned Queue.

![image](https://github.com/user-attachments/assets/53134853-0a33-4f19-8773-0092bb04c8b2)

- Selecting an active employee adds the order to the employee's queue.

![image](https://github.com/user-attachments/assets/e027bd3e-e058-4112-a9d7-fa1d9fd74339)

### Assign Employee

When you add a service to a salon or spa order, you need to pick which employee will perform that service. The Assign Employee window is where you make that choice.

- **What it does**: Shows a list of available employees who are trained or certified for that type of service.
- **Why it matters**: The salon needs to know who did the work for scheduling, commission, and reporting.
- **How it works**: Tap the employee's name to assign them to that service, or select **Skip** to leave it unassigned so it can be picked up from the Unassigned Queue.
- **Multiple services**: If a customer books multiple services, you can assign an employee to each one separately. One person might do a haircut and another might do the manicure.
- **Skip**: Allows the Service Item to remain unassigned if the Service Order is being added to the Unassigned Queue. See [Auto Assign](#auto-assign).

![image](https://github.com/user-attachments/assets/b76e258e-a309-40df-a85d-ba038c8ec515)

### Unassigned Queue

The Unassigned Queue is a temporary holding area for service orders that are not yet tied to a specific employee.

- When a service is created without a staff member, it goes to this queue.
- Team members can open the queue and claim or assign the order to the correct employee.
- Once assigned, the order moves out of the queue and becomes a normal active order.
- This helps prevent missed services and keeps commission and reporting accurate.

![image](https://github.com/user-attachments/assets/848d8747-ce50-46c9-a881-b2cdc55a115e)

### Assign Unassigned Order(s)

- Select an order in the Unassigned Queue and click **Assign Order** on the Schedule View.

![image](https://github.com/user-attachments/assets/e319c83b-0364-4bed-b79c-da760c6e99c2)

- The **Assign Order** window opens. See [Choose Order Owner](#choose-order-owner).
- Note that **Unassigned** is not an option on this screen.
- Select the applicable employee for the Service Order.
- This assigns the Service Order.
- This auto-assigns the Service Item, if not previously assigned. See [Assign Employee](#assign-employee).

### Assign Order

The Assign Order button appears on the Schedule View. It is used to select the employee that is responsible for the order. When a selection is made on an unassigned order, it can auto-assign a service to match an employee's position.

### Auto Assign

Auto-Assign is when the system picks the employee for you automatically instead of making you choose them by hand. This happens when an order from the Unassigned Queue is assigned to an employee.

In Salon or Spa, this usually happens when an order is being assigned, or claimed, and the employee meets the required position rules. If the employee's position does not meet the required rules, the service will remain unassigned in the order.

Auto-Assign saves time by matching the order to the right employee automatically.

## Customer Lookup and Creation

Customer Lookup helps staff quickly find the correct customer record, typically by phone number. This ensures services, preferences, and history are attached to the right person.

### Customer

The Customer window appears at the beginning of the appointment. A customer must be assigned to continue. The options to add a customer are **Guest**, **Phone Lookup**, and **New Customer**.

![image](https://github.com/user-attachments/assets/f8f24fb6-3a49-4f04-824a-2486683e1647)

### Guest

The Guest option allows a one-time-use name to be entered without creating or looking up a customer.

![image](https://github.com/user-attachments/assets/43fd96c0-6309-44af-8d8d-0c1be2773fcf)

### Phone Lookup

The Phone Lookup allows a customer to be located using a phone number.

![image](https://github.com/user-attachments/assets/2339a8de-5d65-447e-a9c1-7c8c9e06a646)

- Enter a phone number and click **Search**.
- The **Select Customer** window opens detailing customers and family members connected to the given phone number.
- Select the customer, or click **+ Add Family Member**, and click **Select**.

![image](https://github.com/user-attachments/assets/995364eb-8fc0-4a2f-8bc4-40a6b1eaf967)

- The name is added to the order.

### Add Family Member

- Click **+ Add Family Member** from the **Select Customer** screen.
- The user is taken to the **New Customer** screen.
- Enter new information for the added family member.
- Click **Save**. The user is returned to the Family Member window detailing the members related to the phone number.

### New Customer

- Clicking **New Customer** opens the **New Customer** window.

![image](https://github.com/user-attachments/assets/8b003439-04c3-4942-a876-7c91a8ed07f6)

- Fill in the required information with a phone number so that it may be looked up later by phone number, then click **Save**.
- The **Family Members** window opens.

### Family Members

- The Family Members window allows the user to make changes to the customer selected for the order and to edit the family members related to the phone number.

![image](https://github.com/user-attachments/assets/7dfd3155-e7bb-451d-a12f-40d4957bd402)

- Options to change family members are **Set Active**, **Add**, **Edit**, and **Remove**.
- **Set Active** allows users to change which family member the order is set to.
- To change the active customer for the Service Order, select a different member of the family, which activates the **Set Active** button, and click **Set Active**.
- **Add** allows users to add a person to the family.
- Clicking **Add** takes users to the **New Customer** window, allowing users to add information for the newest family member.
- **Edit** allows users to update a person from the family.
- Clicking **Edit** takes users to the **New Customer** window with the currently selected customer's information pre-filled.

![image](https://github.com/user-attachments/assets/ce792fda-4099-4e5d-ad3d-30f1d5513fb3)

- Clicking **Save** returns users to the **Family Members** window.
- **Remove** allows users to remove a person from the family.
- Selecting a family member's name and clicking **Remove** removes the customer from the customer family.
- **Change** allows users to go back to the Customer window to make a different selection.

## Tipping

### Close Order

After entering a payment, the user is taken to the Close Order window. This window gives the options to **Cash Tipout**, **Print**, and **Split Tip**.

![image](https://github.com/user-attachments/assets/2729610e-04fd-43c3-be3b-d5257e752e37)

### Cash Tipout

This option cashes the tip out from the drawer or register to the employee. When **Cash Tipout** is selected, the user is taken to the **Cash Tipout** window. Enter the desired amount from the tip to be cashed out to the employee.

![image](https://github.com/user-attachments/assets/4e88798e-535f-47ee-a495-fc3b928feca4)

Note: For multiple tips, the tip that can be cashed out with this feature is the Service Order owner's tip.

Once the Cash Tipout has been completed, no further modifications can be made on the tip from the Close Order window.

![image](https://github.com/user-attachments/assets/cdb83a4e-b360-4b8b-9d54-54361d5c36d6)

### Print

Re-prints the work order related to the order being closed.

### Splitting Tip

- The tip can be split from the Close Order window by clicking **Split Tip**.

![image](https://github.com/user-attachments/assets/aa01081e-29e3-4f1d-b8d2-1ad6d11ab49e)

- After clicking **Split Tip**, the window refreshes to the **Split Tip** window.

![image](https://github.com/user-attachments/assets/12122b0d-5080-427c-b461-5bbf13313d29)

- The Split Tip window contains an editable employee list.

![image](https://github.com/user-attachments/assets/6f68a048-e8e7-4b9e-a6a5-230ef59c0b36)

- The employee list indicates that no funds, `$0.00`, have been applied by default.
- The cogwheel to the right of the allocated amount is used to change the amount to be allocated to the employee.
- The red **X** removes the employee from the list.
- **Split Evenly** allows the tip to be split evenly over the employees in the employee list.
- **Clear** removes all amounts applied to all listed employees.
- **Change Employees** takes the user to the **Change Employees** window.

![image](https://github.com/user-attachments/assets/ee1d0045-b6ab-46d5-80e4-8829b43b0ee0)

- On this window, the user can select and de-select employees manually or use the **Select None** or **Select All** buttons.
- **Select None** is helpful when there are many employees on the list and you only wish to select a few.
- Selecting **None** will not prevent you from returning to the Split Tip window, but if no employees are selected you cannot continue the split process.

![image](https://github.com/user-attachments/assets/f826c0ca-d57c-4e76-93b4-c36f4316dc06)

- When finished, click **Apply** to be returned to the Split Tip window.
- Split the funds of the tip over the employees as desired.
- **Split Evenly** will split the tip evenly among selected employees.
- Using the cogwheel allows the user to specify the amount to each employee.
- Once an amount has been applied to an employee using the cogwheel, the balance to be allocated is shown at the top of the Split Tip window.

![image](https://github.com/user-attachments/assets/0d805631-bc66-4319-8fab-8a0613b833ef)

- Use the **Clear** button at the bottom to clear any numbers entered for the tips.
- Clicking **Submit** returns the user to the Close Order window.
- The Close Order window is updated to detail how the tip was split up.

![image](https://github.com/user-attachments/assets/a93c8211-0053-4ad5-816b-3798aef6714c)

- Note: Clicking **Cash Tipout** will only allow the tip of the person assigned to the order to be cashed out. Example: only `$10` from that assigned order would be available to cash out.

## Back Office

### Creating New Rental/Service Item(s)

- Navigate to the Back Office.
- Select **Items** using the scissors icon.

![image](https://github.com/user-attachments/assets/8554495d-4c05-4223-9653-6ec07a9bb2a1)

- The menu displays **Items**, **Groups**, **Departments**, **Option Groups**, **Pricing Rules**, and **Inventory**.

![image](https://github.com/user-attachments/assets/b8bc50d9-86d0-4490-a767-d44755f286a2)

- Select **Items**.
- Created items are displayed.
- Click **Add** at the bottom of the Items screen.

![image](https://github.com/user-attachments/assets/3e29700e-6e0b-4971-98ef-badb334a66af)

- The **Item Settings** window opens.
- Enter general information for the Rental or Service Item being added.
- On the **General Information** tab, select the drop-down menu under **Sold By**.

![image](https://github.com/user-attachments/assets/c4fca6ee-8109-44bf-8ed9-fea2f70cc6c5)

- Selections include **Normal**, **Weight**, **Price in Barcode**, **Rental**, and **Service**.
- Select **Service** or **Rental**.
- A **Service/Rental** section appears in the left-hand navigation menu.
- For **Rental** only:
  - Rental items require an inventory item.
  - Click the toggle to turn on **Inventory Item**.
  - **Inventory** will be added to the navigation menu.
- Click **Next** to continue to the Service or Rental window.
- If **Service** was selected:

![image](https://github.com/user-attachments/assets/5d3706f1-b965-44b8-9e78-efb878e118a4)

  - The window updates to **Service** with fields for **Duration** and **Position**.
  - This is where the duration, in minutes, is entered for the service.
  - Example: `30` is entered for the duration of a lip wax session.
  - **Required Position** is where you select the employee position that corresponds to the Service Item being created.
  - Example: **Esthetician** is selected for the position that does the wax service.
- If **Rental** was selected:

![image](https://github.com/user-attachments/assets/81e875ba-b860-455a-96b2-272bdb31b13f)

![image](https://github.com/user-attachments/assets/db6dcfcb-1992-479f-a2f9-9cad040d2ea4)

![image](https://github.com/user-attachments/assets/ff1bd0b0-fb09-4d83-81aa-40c084c0a763)

![image](https://github.com/user-attachments/assets/375434a1-f761-4581-8157-c061223d9e0d)

![image](https://github.com/user-attachments/assets/bbe5bc66-f941-45ff-82c8-cc658a6a917d)

  - The window updates to **Rental** with a field for **Duration**.
  - This is where the duration, in minutes, is entered for the rental.
  - Example: `60` is entered for a one-hour rental on Tanning Bed 1.
- Click **Next** to continue.
- See other sections for how to use **Tags**, **Build Items**, and **Option Groups**.
- For **Rental** only:
  - Complete **Inventory Setup**.

![image](https://github.com/user-attachments/assets/71a6c467-38c9-4c23-a5e0-a5606dee21ba)

  - Enter the required inventory information.
  - Important: set at least `1` for **Quantity On Hand**. This tells the system that the item being rented is available. If this is not set, the system will not allow the rental.
- Click **Next** to continue.
- See other sections for how to complete **Pricing** and **Taxes**.
- Click **Save** to finish.
- The Items list will be updated to show the added Service or Rental Item.

### Employee Commission(s)

Commission Setup is configured in Back Office, not during checkout. It defines how staff earnings are calculated for services they perform.

- Navigate to the Back Office.
- Select the **Manager** tab, which looks like a silhouette of two heads together.

![image](https://github.com/user-attachments/assets/a3e3ddd0-fc9e-4a41-9e16-e6874b2735ba)

- The menu updates showing **Customers**, **Employees**, **Messages**, **Pay In / Pay Out**, **Commissions**, **Positions**, and **Scheduling**.
- Select **Commissions**.
- The user is taken to **Commission Rules**.

![image](https://github.com/user-attachments/assets/2f9d46c8-c39b-411d-9816-d37d2c232a2d)

- Click **Add** to create a new Commission Rule.
- The **Commission Rule** window opens prompting for **Position**, **Menu Tab**, **Flat Amount ($)**, and **Percentage (%)**.
- Select the applicable **Position** from the drop-down menu.

![image](https://github.com/user-attachments/assets/d8bc90f5-045f-40d8-a996-5e61af58d3d3)

- Example: **Nail Tech**.
- Select the applicable **Menu Tag**.
- Example: **Product**.
- Enter either a **Flat Amount ($)** or **Percentage (%)**.

![image](https://github.com/user-attachments/assets/0a05b6ad-0000-4f8c-9f13-e420eb25ecff)

- Click **Save**.
- The Commission Rule menu closes and the table shows the updated Commission Rules.

## Customer Facing Waitlist Configuration (Optional)

If you are using a customer-facing waitlist device, configure it from the point of sale in the Back Office. Under the puzzle-piece **Apps** section on the left side, select **Waitlist**.

Note that a customer-facing waitlist display requires a separate hardware screen capable of running the POS Customer Facing Display application. Consult your provider for options.

![image](https://github.com/user-attachments/assets/a951e216-9f9b-4589-8b6b-5dc5c325fd74)

- You can enable or disable functionality of the waitlist by toggling the **Runtime Enabled** switch.
- The waitlist requires information from a configured and authorized register or POS terminal. Use the selection drop-down to choose which register will be used to send waitlist information to the display.
- The display device will have an IP address on the network. Enter the IP address in standard notation, `x.x.x.x`.
- For time estimation, enter a value in minutes for the average service time.

## Operator Cheat Sheet

- **Assign Employee** = who performs the service
- **Unassigned Queue** = waiting room for unclaimed service orders
- **Schedule** = time plus staff calendar
- **Customer Lookup** = attach service to the right customer
- **Service Types** = service categories for organization and control
- **Commission Setup** = earnings rules configured in Back Office

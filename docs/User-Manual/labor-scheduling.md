# Labor Scheduling

## Overview
Labor scheduling allows stores to create and optionally enforce labor scheduling for their store. The system is flexible enough to handle stores operating with a single fixed schedule, stores with a rotation schedule, and stores that create new schedules every week.
Labor scheduling can be used to ensure your store is properly staffed, and optionally to prevent employees from clocking in outside of their assigned hours without manager approval.

## Concepts / Terminology
### Terms

**Schedule**

A schedule is a group of shifts and position assignments for a given day of the week. For the labor scheduling system, the schedule always begins on the day of the week your store is set to start payroll (typically Monday, configured in the store General Configuration page in the back office).
Schedules cover an entire week. If you need to change schedules mid-week (e.g., from a regular schedule to a holiday schedule) you can do this by changing which schedule is active prior to the start of the business day. For example, after close of business on Wednesday, you could set the current week to another time period and set a holiday schedule to start the current week to make it active. Changing schedules mid-week should not be a typical occurrence.

**Shift**

A shift is a group of positions during a given day of the week. A store may have multiple shifts throughout a given day- for example, a morning shift, an evening shift, and a crossover shift that overlaps the end of the morning shift and start of the evening shift during peak hours. Alternatively, stores may only have one shift on a given day.
Note that while shifts may overlap, employees cannot be assigned to overlapping shifts.

For example:
*	A morning shift from 8am to 2pm
*	An evening shift from 2pm to 8pm
*	A midday shift from 11am to 5pm

An employ may be assigned to the morning and evening shift (working a double), but they cannot be assigned to the morning and midday or evening shift and midday shifts because those overlap.

**Position**

A position in a shift refers to a store position that needs to be filled by an employee. For example, a midday shift may require one server, two cooks, and a dishwasher.

**Position Assignment**
A position assignment is what ties a specific given employee to a given position during a shift for a day of the week.

### Managing a Fixed Schedule

A fixed schedule is a schedule where the same employees work the same shifts every week. Some exception schedules may need to be handled from time to time, such as holiday schedules, before things return to the normal fixed schedule.
Stores operating in this mode would typically create a “Regular” schedule, and a “Holiday” schedule. 
Sunday night after close of business, or first thing Monday morning before non-managers come in to the store, the manager will edit the schedule to point to the new week. All shifts, positions, and position assignments will carry forward with no additional work. 
When shifting to a holiday schedule, once the schedule is set, when it needs to be the active schedule for the week, the manager will simply edit the holiday schedule to be the active week by setting it to the start of the holiday period prior to the start of that week.

### Managing a Multi-Week Rotation Schedule

A multi-week rotating schedule will typically have 2-5 weekly schedules, plus optional holiday schedules as well.
If your store schedules one week in advance, you would configure two schedules- one for the current week (for example, Schedule A), one for the next week (Schedule B). 
When the week defined by Schedule A is completed, a manager would change Schedule A to be the week after next, and Schedule B would become the active schedule.
Upon changing over to Schedule B, the manager would then start updating the position assignments on Schedule A to reflect the next week’s work assignments. 
This method can be extended to cover a month’s rotation (4-5 weeks), plus any holiday special schedules.

### Managing a New Schedule Every Week

This would typically be used at stores where the schedule either changes completely week over week with different shifts and positions, or if a store wanted to track schedule adherence over time.
In this model, a new schedule is created for upcoming weeks, and old schedules can be deleted after they are completed. Deleted schedules are not removed, just hidden from the interface and made inactive, so they can still be used for reporting schedule adherence. 

### Interaction with Timeclock / Payroll

Payroll reports are based off the timeclock, not the schedule. The reflect the hours worked, not the hours scheduled.

# Back-of-House Operations
If enabled for your store, Labor Scheduling is in the back office under the “People” icon on the left side menu.

## General Configuration Options

<img width="324" height="169" alt="image" src="https://github.com/user-attachments/assets/ebf4e175-cac1-4f1b-92c5-d81bf4ee6b44" />

 
**Enforcing Scheduling**

If this is enabled, all non-manager / assistant managers will not be allowed to clock in to the system without the approval of a manager or assistant manager.
Employees are not forced out at the end of their shift times.

**Max Preferred Hours**

This is the weekly maximum number of hours an employee can be scheduled for without an alert. An employee scheduled for more than the Max Preferred Hours value but under the Maximum Stretch Hours will trigger a warning in the schedule.

**Max Stretch Hours**

This is the maximum number of hours an employee can be scheduled for before the scheduling system will throw an alert. Often times, this is going to be the overtime threshold.

**Clock-in Grace Minutes**

If “Enforce Timeclock” is enabled, this is the number of minutes an employee can still clock in (early or late) without a manager’s approval. If “Enforce Timeclock” is disabled, this setting is ignored.

## Schedules

### Creating a Schedule

To create a new schedule, click or tap “new”

<img width="325" height="156" alt="image" src="https://github.com/user-attachments/assets/38caebfd-d2ea-4e6f-8174-7b21aaae5b48" />
 
When creating a schedule, you will have an option to create a schedule from scratch or by copying an existing schedule.

<img width="92" height="85" alt="image" src="https://github.com/user-attachments/assets/798be2d4-6f7a-4063-a415-bd47737e3de8" />

You can only copy a schedule if you have a valid, active schedule already in the system.

**Creating from scratch**

When you create a schedule from scatch, you will be asked to name the schedule (e.g., “Week 1”, “Holiday”, “March Wk 1”, etc.
You will also need to select a week the schedule will be active by clicking on a day in the calendar control. 

If you select the wrong week, you can tap or click “Clear” to reset the date so you can choose again. You must select a date for the schedule before you can save.

<img width="142" height="142" alt="image" src="https://github.com/user-attachments/assets/6c4c27ed-158b-457f-8fff-d501ef06ec38" />

Once you have created a schedule, you can click on it to start creating shifts and position assignments. See the section on creating and editing shifts for information on shift management.

<img width="189" height="69" alt="image" src="https://github.com/user-attachments/assets/b4f16363-0f17-42b7-9fa2-7169adea1b91" />

**Copying Existing Schedule**

To copy an existing schedule, tap or click on “New” under the schedules list on the left, and select “Copy Existing” Select the schedule you want to copy from and click or tap next.

<img width="217" height="216" alt="image" src="https://github.com/user-attachments/assets/870e38ef-3d12-4245-ace8-9be9e0a79cbf" />

You will need to name the new schedule, select a week it will be active, and choose if you want to copy positions and assignments over. Click or tap save when done, or cancel to exit with saving your changes.

<img width="217" height="246" alt="image" src="https://github.com/user-attachments/assets/ee66549f-e0c3-4c19-aa1d-92b44825a01c" />

### Editing A Schedule
To edit an existing schedule, you can click or tap on the schedule to select it.

Please see the section on Shifts for information on how to manage / edit shifts and position assignments.

If you want to change when a week is active- for example, to flip “Schedule A” to a future week and “Schedule B” to be the current week, tap or click on the “Edit Schedule” button at the bottom of the screen.

This will allow you to rename the schedule and / or change the week the schedule is active for.

*Note that you can only have one schedule active during a given week.*

### Deleting a Schedule
To delete a schedule, click or tap on the schedule and use the “Delete Schedule” option at the bottom of POS. You will be asked to confirm by typing in “Delete Schedule”

*Note that deleting a schedule is permanent and cannot be undone or recovered.*

<img width="325" height="217" alt="image" src="https://github.com/user-attachments/assets/c3c9223d-3ebc-4b18-b885-c27b33ba9c91" />

## Shifts

A shift is a period of time during a day where one or more people will be working. 

Shifts define when specific employees can work (if schedule enforcement is enabled) or should work (if it is not). 

For example, a morning shift may run from 8am to 2pm, while an evening shift runs from 1pm through 7pm. A shift will have positions assigned to it (e.g., cooks, runners, cashiers, etc), and those positions can be assigned to available employees.

Shifts can overlap, but employees cannot be assigned to overlapping shifts.

If you have one position that doesn’t fit into an existing shift – for example, cooks and kitchen staff may start work at 10am, but servers and other front-of-house staff start at 11am, you can create a shift for the kitchen staff and a separate shift for the servers.

### Creating a Shift

To create a shift, click or tap on the “New Shift” button under your schedule.

You will be asked to name the shift (e.g., “Morning Shift”, etc), select an applicable Day of the Week, and start and end times for the shift.

<img width="217" height="217" alt="image" src="https://github.com/user-attachments/assets/496c0720-fdd7-45d1-9d20-1e181549f310" />
 
After defining that information, click or tap “Positions” to create available positions during that shift that will need to be filled.

You can add, edit, or delete shift positions from this page.

*Note that the Positions come from the positions you have created for your store. For example, if you have not created a “Bartender” position, you cannot add a “Bartender” position to the schedule until you have gone into the employee positions section and created the new Bartender Role.*

<img width="217" height="217" alt="image" src="https://github.com/user-attachments/assets/329d2c8e-33f8-4282-a6e1-dbc55ac5a903" />

### Adding a Position
Tap or click “Add” to add a new position.

<img width="217" height="137" alt="image" src="https://github.com/user-attachments/assets/d28a17cb-aff0-43d9-92a3-c03cf1114556" />

Tap or click on the “Position” field to select an available position.

Once a position is selected, you can optionally choose to assign an employee to that shift position. You don’t have to do the assignment at this time, that is just an option.

*Note that you can only assign employees to a position if they have that position. E.g., if an employee is only configured as a Cook and a Runner, you cannot select them for a Bartender position until you have added that position to the employee. See Employee Management for details.*

If you are creating multiple of the same position (e.g., you need 3 cashiers), you can increase the number of positions.

### Editing a Position
To edit a position or position assignment, click or tap on the shift position and select “Edit”

<img width="217" height="218" alt="image" src="https://github.com/user-attachments/assets/588f0b53-d2a4-4ab6-a733-62e8091412da" />

This will allow you to assign an employee to that shift position, or remove an already assigned employee from that position.

<img width="217" height="138" alt="image" src="https://github.com/user-attachments/assets/fbf5069c-9825-4c71-81b5-bfdfa3f9b5cc" />

When finished, click or tap “Done” to save your changes, or “Cancel” to undo any changes you have made.

### Deleting a Position
To delete a position, click or tap on the position and select the “Delete” option. You will be asked to confirm the deletion.

<img width="217" height="74" alt="image" src="https://github.com/user-attachments/assets/b00f24f1-16d9-4568-88a0-fe16018a05cb" />

### Editing an Existing Shift
To edit a shift, tap or click on the shift, and tap or click on edit shift. You will be able to add or remove shifts, change position assignments, etc.

### Copying an Existing Shift
To copy a shift, tap on an existing shift and then the “Copy Shift” button at the bottom of the page.

<img width="324" height="186" alt="image" src="https://github.com/user-attachments/assets/e349fda2-e686-428d-a791-f415b285903b" />

When you copy a shift, you can choose which day or days to copy the shift to, allowing you to copy a common shift to multiple days at once. 

You can also choose to copy the positions from the existing shift across, and if you copy the positions, you can optionally also copy existing position assignments.

<img width="217" height="218" alt="image" src="https://github.com/user-attachments/assets/a674bc8b-0bda-44a5-8b8f-7a7574e8630c" />

*Note that if copy a shift with positions and assignments, it one or more employees are over the configured preferred or stretch hours, every shift that employee is in can turn yellow or red.*

<img width="324" height="170" alt="image" src="https://github.com/user-attachments/assets/f620e8de-c3cd-4296-a9c8-d89ebf92691c" />

When this happens, you can click or tap on a yellow or red shift and then the error status employee to see the problem.
 
<img width="217" height="162" alt="image" src="https://github.com/user-attachments/assets/f3275635-820d-4fd4-98b4-0f5be6dfc14f" />

### Deleting a Shift

To delete a shift, click or tap on the shift and then the “Delete Shift” button on the bottom of the screen. You will need to confirm your intent to delete because deleting a shift cannot be undone.

### Shift Colors

A shift’s colors on the schedule indicate the status of the shift:

**Green:**

All positions are filled with no warnings or errors

**White:**

A shift has been created but there are no position assignments.

**Grey:**

The shift is for a past day. This is typical for the current week as the week progresses.

**Yellow:**

There are one or more warning conditions during the shift that may need to be corrected, such as employees that are above the preferred hours for the week, or some positions have not been filled on a future schedule. Unfilled positions on a current schedule will be red.

**Red:**

There are one or more error conditions during the shift, such as an employee over the stretch hours for the week or one or more employees are assigned to overlapping shifts.

# Front-of-House Operations

There are no scheduling front-of-house operations. If an employee clocks in during their scheduled hours within the configured grace minutes, there are no changes to the operator’s experience. 

If an employee attempts to clock in before or after their grace minutes, or does not have an assigned shift, the system will prompt for a manager confirmation. This is intended to allow a manager to bypass the schedule to handle exceptions – e.g., an employee calls in sick and another employee comes in to cover their shift – without reconfiguring the schedule.
 
Note that enforcing the labor schedule does not force an employee to clock out.


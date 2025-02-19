**Listing Printers from CLI**
wmic printer list brief
﻿![image](https://github.com/user-attachments/assets/3491ff29-de4c-4f2e-af44-bd3514a515d3)


**Printer States and Statuses**
code number	result
0	OK
1	Unknown state
2	Other (Not defined)
3	Idle, ready to print
4	Ready to Print
5	Warming up
6	Stopped Printing / paused
7	Offline
8	Paper Jam
9	Paper Out
10	Manual Feed (waiting on paper)
11	General Paper Problem

**Show all print Jobs**
wmic printjob list brief

**Delete Print Jobs from CLI**
wmic printjob delete


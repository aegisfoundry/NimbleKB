The Point-of-sale system supports multiple methods of printing, including operating system-dependent printing and vendor-specific integrated printing.

Under the configuration gear icon, you can click or tap on the printers tab to access the list of known and configured printers.

![image](https://github.com/user-attachments/assets/ac43bf57-bad5-4ee8-9785-1c7c30092210)

The system will show the list of discovered or configured printers, and their status. A status of “None” indicates that the printer is online and ready to work. If you are experiencing printing issues, verify that the printer is online for the station.

Android and iOS Printers are discovered at print time, so they will not show up in the list.

To utilize Windows printing, you will need to install the Printing Companion by using the “Download Companion” button. The companion application will interface the point-of-sale system to the Windows operating system.

Nimble also supports direct vendor integrated printing, currently only with Star Micronics printers. These allow for the system to directly connect with the printer without using the device’s operating system. This can reduce printing errors in some circumstances. 

To add or edit a known printer, click or tap on the “Manage Known printers” button. You can create a new printer, or edit an existing printer drom there.

![image](https://github.com/user-attachments/assets/aec25390-7057-4a5e-83d1-f892e66dbd7f)

 Currently, known printers are all of vendor “star” or "epson", and use a TCP:<ip address> Port. 
 Port settings are not required for Star Micronics printers.
 Epson printers require a port setting, typically 9100.


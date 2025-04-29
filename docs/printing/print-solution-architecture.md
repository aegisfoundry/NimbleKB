# Understanding Nimble Printing

Nimble has several different ways to print, each with advantages and disadvantages:
* Operating System (OS) Printing leverages the device's native print architecture, allowing Nimble to print to any printer the operating system can access.
* Integrated / Direct Printing are vendor-specific integrations for printers, allowing the system to print more quickly and without any limitations from the operating system.
* Print Server Printing leverages a print server utility to centralize printing from multiple devices.

Currently, Nimble has direct print integrations with Star and Epson compatible printers.

Of note, you can mix-and-match between Epson, Star, and OS printing at the same store. For example, you could use an OS printing for a receipt, but have Star and Epson kitchen printers.

The general recommendation for most point-of-sale implementations is to use Epson or Star Direct Printing, with other options available as needed for specific use cases.

## Star Direct Printing
* Star Direct Printing only works with Windows. iOS and Android are not currently supported with Star Direct.
* Star Direct Printing does not support logo printing from the POS; You will need to configure logo printing on the printer itself.
* Star Direct Printing only works with Ethernet. At the moment, USB and Serial are not supported.
* Star Printers known to work:
  * Star TSP 650 series thermal printers
  * Star 700 / 740 series impact printers
  * Star Mc Print3 series thermal printers
* Star Printers known NOT to work:
  * Star TSP-100/140 series thermal printers

Star Direct Printing Advantages:
* Star Direct Printing is very fast compared to Windows printing
* Star Direct Printing is easy to set up - No drivers are required

Star Direct Printing Disadvantages:
* Star Direct Printing only works on Windows. If you have non-Windows registers, you would need to use other printers for those devices, or configure a Nimble Print Server
* Star Direct Printing does not support USB/Serial printing.

## Epson Direct Printing
* Epson Direct Printing supports Windows, iOS, and Android.
* Epson Direct Printing only works with Ethernet / WiFi printers. Serial and USB are not currently supported.

Epson Direct Printer Advantages:
* Works with any Epson or Epson-compatible thermal or impact printer. Any printer that supports the ESC/POS standard should work.
* Epson Direct Printing is easy to set up - No drivers are required.
* Epson Direct Printing is very fast compared to Windows printing.

Epson Direct Printer Disadvantages:
* Epson Direct Printing does not support USB/Serial printing.

## OS Printing
* Windows can print to any printer with a windows print driver.
* Android can print to any printer the android device can see and access.
* iOS requires a printer to have AirPrint capability.

Advantages of OS Printing:
* You can print to any printer the operating system can see.
* You can print to USB, serial, or ethernet/WiFi devices; As long as the Windows print server can see the printer, you can print to it.

Disadvantages of OS Printing:
* Android and iOS devices require a pop-up for the user to select the printer they wish to use each time a print is made. This may be acceptable for low-volume retail and service stores, but would not be a good experience for kitchen printing- each kitchen print would require a separate confirmation and manual routing to the correct printer from the user.
* Windows requires the use of the Nimble Companion Services to access the Windows printers without the print dialogue.

When to use OS Printing:
* When you need to print to a non-traditional receipt printer, such as an 8.5x11" laser or inkjet printer.
* When you need to print to printers that are not Star or Epson compatible.


## Print Server Printing

The Nimble Print Server is an optional utility you can install on a Windows device on your network that stations can route their printing to. The windows device can use a mixture of Windows OS printing and direct integrations.

Advantages of Print Server Printing:
* Any device can print without a print dialogue or worrying about compatibility with the device. E.g., iPads can print to non-AirPlay printers.

Disadvantages of Print Server Printing:
* The print server is a single point-of-failure. If the print server is offline, your store cannot print.
* The process is slightly slower than regular printing. For kitchen printing, the few extra seconds are not likely to cause an issue, but a potential 4 to 5 second delay in getting a receipt may not be a good customer experience.

When to use Print Server Printing:
* When you have legacy printers that the customer will not upgrade or replace that do not work with some or all of the new registers. E.g., you install Android terminals and the customer has Bixilon printers that do not work natively with Android.
* When you have legacy printers that do not support multiple concurrent connections to them over ethernet, and will only allow one device to talk to them (Common with older kitchen/impact printers).

## Why Nimble Focuses on Network (Ethernet) Printing for Direct Integrations

Direct print integrations focus first on Ethernet / WiFi instead of Serial or USB. Serial and USB printers are tied to the unit that they are installed on, and print jobs cannot be routed to that device without additional complexity (e.g., such as a print server) and delay.

USB / Serial printing is not suitable for kitchen printing, where there may not be a computer attached to the printer. Because serial and USB are more limited, Nimble focuses first on Ethernet because it is suitable for all cases.


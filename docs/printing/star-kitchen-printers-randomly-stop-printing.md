## Symptom: My star kitchen printers will work, but will randomly stop printing at all, often during busy times.

## Solution
Try restarting the printer. Check paper levels, power, and network connectivity.

If the problem is a reoccuring issue, ensure that TCP Multi-session is enabled on the device. This is a Star-specific setting that allows a printer to talk to multiple devices, and is DISBALED by default on many older printer models, including the common 740 series impact printers and 650 series thermal printers. With this setting disabled, the printer will only accept a single connection from a single station at a time, and will "lock" itself to only talking to that device for a period of time. During that "lock", no other stations can send jobs to that printer.

### To enable multi-session on a Star network printer
* Open a web browser to the IP address using http only (e.g., http://192.168.1.50)
* Select "login". The password is usually the star default user/password: root/public
* Under "System configuration", ensure "Multi-session" is enabled
* If you made a change, you will need to go to the bottom of the form and select "Submit", and then on the left side menu, select "save". Choose "restart device" and execute


*Note that this process is specific to Star Micronics printers and is not applicable to Epson, Bixilon, etc.*


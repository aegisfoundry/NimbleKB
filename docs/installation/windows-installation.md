## How do I install Nimble on a Windows device?

## Solution
You will need access to the Microsoft App Store. *

Use either of the following links to install NimblePOS to the client.

HTTP Link: https://www.microsoft.com/store/apps/9PNH6M1VK9R7 

App Store Link: ms-windows-store://pdp/?produedctid=9PNH6M1VK9R7

You do not need a microsoft account to download the Nimble app from the Microsoft store.

Once the app is installed, it is recommended that you enable "Pin to Start" and "Pin to Taskbar" for the app. 

### Setting the POS to Tablet Mode

For a dedicated POS Register, set the system to always be in tablet mode to ensure the on-screen-keyboard works as intended.
* Under the start button, select "Settings"
* Navigate to "System", and then "Tablet Mode"
* Set the drop down on "When I sign In" to "Use Tablet Mode" 

You can toggle a Windows 10 machine in and out of tablet mode temporarily by tapping on the action center (bottom right Icon on the task bar) and tapping the "Tablet Mode" button.

### Setting up the POS client to automatically start on system launch

Toggle the machine out of tablet mode if it is not already
Open a file explorer window and set the destination to "shell:startup"

﻿![image](https://github.com/user-attachments/assets/2fcad077-0387-4c16-96e9-2ee255d46df1)

Open another file explorer window and set the destination to "shell:appsfolder"

﻿![image](https://github.com/user-attachments/assets/ba7608d5-d27e-4234-8332-4fc676b1bce0)

Find "NimblePOS" in the applications folder, and drag it to the "startup" folder to create a shortcut that will automatically start Nimble on login.
﻿![image](https://github.com/user-attachments/assets/98ef9cfb-7659-4a98-aa82-2184371f6187)



### * Note 
Many purpose-build point-of-sale registers don't natively have access to the Microsoft app store. 

Download the ZIP file from the following link: https://github.com/lixuy/LTSC-Add-MicrosoftStore/archive/2019.zip

﻿![image](https://github.com/user-attachments/assets/6ea9692e-a603-4f8b-836c-365203589c55)


Uncompress the .ZIP file, and run the "Add-Store.cmd" installation file as an administrator (right-click, run as administrator) to install access to the Microsoft App store.
There may be errors during the installation, this is normal when preqreuisites are already installed on the system.

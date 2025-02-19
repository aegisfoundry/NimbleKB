Checking the Services (Windows print only)
Verify that the Nimble Listener Service and Nimble Print Service are running. If one or both of the services aren't running, try starting the service and verify if it works. Also verify the services are set to auto start.


If the services are running, verify all of the executables are running for printing and listener services. There should be FOUR executables running:

NimblePrintService
NimblePrintServer
NimbleListener
NimbleListenerService
﻿![image](https://github.com/user-attachments/assets/a0c3d522-fe30-4aac-8393-cfbd45f41145)



A common failure is NimbleListener isn't running, as in the example below.
﻿![image](https://github.com/user-attachments/assets/fc55a9a8-b6c3-46ca-b58e-3f561805a2bf)


Open a command prompt and type the following
cd "c:\Program Files (x86)\Nimble\Listener"

then 
NimbleListener.exe

it should start up like this:

﻿![Uploading image.png…]()


You can control-C out of this.


If not, it may throw out an error like the following
﻿![image](https://github.com/user-attachments/assets/aacdeeec-c137-41f4-970b-ade14f76e735)


If it's a missing requirement, all of those should be in c:\program files (x86)\Nimble\Requirements

Reinstall all of the files.
If they say they are installed, that's fine, just keep going until you've run all of them.

Verify that the NimbleListener.exe will start manually from the command line.
If so, restart the system and ensure the services started up as expected.


Check the loopback state:
open a powershell prompt and run the following command:

checknetisolation loopbackexempt -s

It should look like this:
﻿![image](https://github.com/user-attachments/assets/bee6dec1-b100-4cb7-9bcd-0eb4ba0130cb)



Examples of failures

Note the "AppContainer NOT FOUND" bit
﻿![image](https://github.com/user-attachments/assets/e4d18d4e-1f46-4083-b011-15eb88bcd16e)


This is also a failure- nothing is listed
﻿![image](https://github.com/user-attachments/assets/d4df8145-ef8a-42fa-b571-5d762ae0c36b)


If this is the case, run this command:
checknetisolation loopbackexempt -a -n=E56E383F-00B4-4B28-8CD1-5060C0B59CED_vvea4jwpxhtfp

Note
The name seems to have changed, at least as far as nimble getting in the app store.
aegisfoundry.nimblepos_kmy2cmrr0xsqm
aegisfoundry.nimblepos_bfn31nh2abqaa
may be valid names now, because why the F not.


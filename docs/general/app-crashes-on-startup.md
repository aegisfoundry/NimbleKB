## Symptom
The Nimble application crashes at startup, before allowing someone to log in either number pad or email address

## Troubleshooting Steps
1. Restart the device
2. Uninstall and reinstall the application. Many issues can be fixed this way.
3. Ensure the local device is up-to-date and there are no pending operating system patches.
4. (Windows Only) Go to the Nimble application in the start menu.
- Right click on the application and go to the App Settings. Reset the application.
- This may also be done in right before another re-installation in case there is some persistent corrupted local data or setting.
5. (Windows Only) Open a command prompt as administrator.
- Run a checkdsk /r /f and restart the machine.
- This will check the system for bad sectors on the drive, but this will take some time, especially if there are a lot of bad sectors to process.
- If bad sectors are found, the hard drive on the system is failing.
- If any bad sectors are found, you can try to remove and re-install the Nimble application, but if this works, it is only temporary because the hard drive is failing.
6. (Windows Only) Reset the PC in case something on the operating system is corrupted.
> This will erase all data on the system and can take several hours. Resetting a PC is a last resort, and should NEVER be done on a back-office computer or any other non-Register device!!!


## MacOS Troubleshoot Steps
MacOS does not delete application data when an app is removed. If the app crashes at startup on MacOS:
1. Uninstall the application
2. Delete ~/Library/Containers/NimblePOS
3. Re-Install the application

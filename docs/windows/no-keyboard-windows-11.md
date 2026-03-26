## Problem
On Windows 11, the on-screen keyboard does not automatically appear when tapping on text fields. 

## Resolution
With Windows 11, the on-screen keyboard is configured by default to only appear if the user taps into a text box and there is no physical keyboard attached. However, the process that detects if a physical keyboard is attached is broken in windows 11.

To get around this, go to settings and search for the "TYPING SETTINGS" (Under "Time and Language")

Set the "Show the touch keyboard" setting to "Always"

<img width="543" height="309" alt="image" src="https://github.com/user-attachments/assets/b9e0f19c-6f06-4be8-811e-d9ab022c2af4" />

## Notes
Nimble 2.1.x or higher is required for this functionality to work.

The on-screen keyboard will still not appear when using a remote session to interact with the system.

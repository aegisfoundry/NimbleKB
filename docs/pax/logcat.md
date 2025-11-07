## How do I get a logcat or detail log from a pax device?

A logcat is a log bundle from the pax device. The detail log is just the larger log, while the log cat is often just a summary. In most cases, when someone askes for a LogCat, they really need the detail log. The log usually only contains a few days worth of data, so if there is an error you need to diagnose, the sooner the logcat can be uploaded, the more helpful it will be.

This is separate from any payment processor logs, such as Tsys or BroadPOS.

Logcats will tell you at a hardware level what the device is doing, and can help diagnose issues such as units restarting at strange times, going to sleep at strange times, autobatch issues, and hardware problems.

## Procedure

Close any applications on the device.

Find the PaxStore and open it.

You will need open up the options menu in the pax store, often a green "hamburger" in the upper left corner.

Go to "More", and then select "Upload Terminal Logcat"

Select the appropriate option - usually the detail log - and tap upload.

It may take a few moments to upload, especially over slow connections. A detail log can easily be 100 megabytes.

## Now What?

The logs are uploaded to the Pax store. 

* If you have access to the device in the pax portal, under the device, settings, on the right side go to the green Terminal Logcat button and select the log you want to download. As a note- these can be very large.
* If someone else manages the device, they will need to go and pull the logs.
* If more expertise is needed to parse the logs, contact Pax support. Tehy can pull the logs from the device.

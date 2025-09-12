## How to configure wifi settings on a Pax A-series device
### Applies to the A35, A80, and A920

_Note: The Pax A3700 has a slightly different configuration. See the article on configuring the Pax A3700 for details._

### Exit the payment application
If you have not already exited the payment application, the following procedures can be used to exit the application.

#### Portico-based payment applications
Typically on an A80, press the red X on the keypad and agree to closing the payment application.

If you are prompted for a password, you will need to check with your processor, or try the default Pax passwords (See the article on default pax passwords)

#### BroadPOS-based payment applications
Tap on each corner of the screen, starting in the top-left and proceeding clockwise.

<img width="448" height="853" alt="image" src="https://github.com/user-attachments/assets/8390c02f-478b-4273-9b08-ba8b776aa27c" />

_You will typically see a flash or other visual indication as you tap each corner._

You will often be prompted for a password. If so, use the password provided by the payment processor, or try the default Pax passwords (See the article on default pax passwords)

<img width="349" height="728" alt="image" src="https://github.com/user-attachments/assets/594b26b5-765d-4088-88d8-ea39a5ca02f2" />

Tap "Exit"

You may be prompted for the password again.

<img width="349" height="728" alt="image" src="https://github.com/user-attachments/assets/8265e569-07ad-4d9d-852d-c79208296401" />

Go to "Settings"

_You may be prompted for another password. That may or may not be the same password from the earlier step exiting the BroadPOS application._

<img width="393" height="793" alt="image" src="https://github.com/user-attachments/assets/86e387b4-102a-408b-bbc7-f3f7e8dab089" />

Tap on "Network and Internet"

<img width="414" height="377" alt="image" src="https://github.com/user-attachments/assets/657e4b10-d47a-4a44-95bc-86e2255f74da" />

Tap on the wifi network name you want to join.

<img width="383" height="441" alt="image" src="https://github.com/user-attachments/assets/997b7a51-6c75-4a4a-aac4-1f1f1b0a704e" />

You will enter in the wifi password here.

Note that if you need to set a static IP address on the device, use the "Advanced Options" drop-down.

Set the IP settings from DHCP (dynamic address) to Static

<img width="297" height="317" alt="image" src="https://github.com/user-attachments/assets/51faaccf-6a62-41f7-92bb-3c6d0c7e6f77" />

You will need to set the IP address, gateway, network prefix, and DNS server.

<img width="337" height="363" alt="image" src="https://github.com/user-attachments/assets/8fe16eab-7c5e-4971-95a8-1d79b916dcc5" />

The IP address, gateway, and network prefix length are specific to the customer's network. 

For many customer networks, the IP address will be in the 192.168.1.2-253 range, typically 192.168.1.200 or higher for static devices.

_Note each payment terminal will need to have a different IP address._

If the customer network is in the 192.168.1.x range, the gateway will typically be 192.168.1.1, although check the network configuration to be sure. Some networks may use 192.168.1.254, for example, although it is less common. Additionally, if a network is something like 192.168.4.x, then the gateway would be 192.168.4.1.

Typical small home / small office networks will have a network prefix of 24. That network length may be listed in the router as 255.255.255.0

DNS can be set to 8.8.8.8 

8.8.8.8 is a public DNS server and is safe to use.

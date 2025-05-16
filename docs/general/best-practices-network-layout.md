## Recommended Best Practices for Network Layout
Most devices should be set to use a static IP address inside of a store to reduce complexity in troubleshooting issues. If you have access to the firewall / router, you can configure these as static reservations, but if you replace the firewall/router then the devices will stop working and you will need to reconfigure.

Instead, by using static IP addresses, the point-of-sale network will remain able to communicate with the various parts, even if the underlying IP scheme used by the router changes.

For example, if the old network is 192.168.1.x, and a new firewall/router installed that changes it to 192.168.4.x, then while the point-of-sale devices won't be able to reach the internet, they will be able to talk to each other. Fixing the IP problem would be to simply update each devices IP address and change the mapping inside of the point-of-sale where appropriate. E.g., known printer addresses, cash drawers, and payment terminals.

Most SOHO grade network equipment will set the top of the DHCP range to end at x.199. For example, 192.168.1.2 -> 192.168.1.199. In those situations, any IP address over x.199 is not going to be handed out by the DHCP server.

For simplicity, you can often use that range of IP addresses over x.199 for static IP addresses without the DHCP server allocating those addresses to random devices without having to reprogram the customer's firewall.

Note that a store's network scheme can be configured using different network ranges; 192.168.x.x is the most common for small networks, but 172.16.x.x and 10.x.x.x are also things you may run into.


### Station IP Addresses
Use x.200 -> x.209 for registers / stations

### Credit Card Reader IP Addresses
Use x.210 -> x.219 for credit card readers

### Receipt Printer IP Addresses
Use x.220 -> 2.229 for receipt printers

### Kitchen Printer IP Addresses
Use x.230 -> x.239 for kitchen printers

### Bump Station IP Addresses
Use x.240 -> x.249 for expo / bump
The expo should be .240, and stations anything above that.


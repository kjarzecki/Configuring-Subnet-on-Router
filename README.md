## How to Configure a Separate Subnet on a Router

This webpage will outline how to configure a separate subnet on your router.
The end goal will be to create a separate subnet to connect the computer to, separate from the other devices on the main network address.
This is illustrated in the diagram below.

![Router Set-Up Goal](Router_set-up_goal.PNG)

### SMC Router - Background Information

The SMC Barricade 7004vbr has one WAN (Wide Area Network) port and four LAN (Local Area Network) ports.

The idea will be to allow the router to assign its own network address automatically based on the incoming internet (using DHCP), but then define a separate subnet under this main network address.




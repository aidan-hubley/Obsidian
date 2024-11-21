#DataCommNetworking
# Network Rack Overview
A network rack/server rack, is a metal frame designed to hold several networking components, such as servers, switches, patch panels, UPSs, and more. Those racks make it convenient to store and work with these types of devices.

Components:
A = Ethernet router
B = Ethernet switch
C = Ethernet patch panel
D = Fiber patch panel
E, F, G = Servers
H = UPS
I = Wireless controller
Front View:
![[Pasted image 20220828234953.jpg]]

Back View:
![[Pasted image 20220828235043.jpg]]

# Network Devices
## Router (A)
A router is a device that connects two or more network segments or subnets. In this example, you see that (among other things) this router has the ability to support a wide area network (WAN) and four local area networks (LANs). Notice that the WAN port is a small form-factor pluggable (SFP) connector. From the back view, you see where the router is turned on and how to attach this device to a power source.
![[Pasted image 20220828235327.png]]

## Cisco Switch (B)
A switch lets you connect multiple devices to the same network segment. Each port is given a number. The number next to an arrow that points up corresponds to the port on the top row. A number and down arrow correspond to the port on the bottom row. Most of the ports on this switch are used to connect devices using Ethernet or RJ45 cables (ports 1-24).
![[Pasted image 20220828235440.jpg]]
Specialized ports for Gigabit Ethernet and SFP are also available.
![[Pasted image 20220828235517.jpg]]

## Patch Panels (C & D)
A patch panel provides an easy way to connect devices and accommodate different types of cabling, such as Ethernet (twisted-pair) and fiber optic cables.

An Ethernet patch panel (C) typically terminates wires that run from the different Ethernet office wall plates. Patch cables (Ethernet cables with RJ-45 connectors) are then used to connect these ports to the switch. This allows an office computer to connect to the switch by simply connecting to a nearby wall plate.![[Pasted image 20220828235553.jpg]]
Some labs also work with fiber optic cables. The fiber optic patch panel (D) performs the same basic function as the Ethernet patch panel but uses fiber optic cabling. In some labs, these ports are used to connect to the SFP port found on the Cisco switch.
![[Pasted image 20220828235644.jpg]]

## Servers (E, F, G)
Servers can provide several functions, such as storing files, managing Active Directory, providing IP addresses (DHCP), and more. Depending on the lab, you may see one or more servers. When looking at the servers, you'll notice that they contain several disks. In this example, there are three servers: CorpServer, CorpiSCSI, and CorpData. As you select each server, you can see its outline, and its name is shown in the Selected Component pane.
![[Pasted image 20220828235813.png]]
Since there isn't much that can be done from the front view of the servers, you will often be working with them using the back view. From the back view, you can see various things, such as where the servers are getting their power source and any additional networking cards, such as an Ethernet PCIe Riser card or a fiber optic PCIe Riser card.
![[Pasted image 20220828235830.jpg]]

## Uninterruptible Power Supply
An uninterruptible power supply (UPS) is a device that is constantly providing battery power to a computer while the batteries are continually being recharged by the wall outlet. A UPS typically provides several locations to plug in devices. In some cases, these female AC power connectors may be divided into a critical and a non-critical panel. The critical portion will provide power to its connected devices when power from the wall outlet is disconnected. The non-critical panel will only provide power when the UPS is connected to a live wall outlet.
![[Pasted image 20220828235934.jpg]]

## Wireless Controller (H)
The last device in our example is a wireless controller, which is used to monitor and manages wireless access points in a wireless network architecture.
![[Pasted image 20220828235951.jpg]]

# Working with Network Cables
As you begin to work with the individual devices found on the network rack, it's helpful to understand how the cabling works with these devices. For example, to provide the most realistic experience possible, TestOut labs often let you add or move cables between devices. To accomplish this in this type of environment, only the cable ends and a small portion of the cable are used. Since the entire cable is not shown, both ends of the cable are highlighted when you select it, allowing you to see where (or if) the other end is connected. In this example, you see that the Ethernet cable connected to the router's LAN 1 port is also connected to port 15 on the Cisco switch.
![[Pasted image 20220829000133.jpg]]
Be careful not to confuse the cut end of the cable as being plugged into a port it is overlapping. For example, at first glance, it may appear as if the cable connected to the LAN port in the router is plugged into port 2 on the switch. Selecting the cable makes it clear this is not the case. An easy rule of thumb is that the end of the cable plugged into a port will have some type of connector, not just a cut off cable.

In addition, remember that the Selected Component panel located at the bottom of the hardware view also shows you the selected cable (or other device) and indicates which device it is connected to. The image here shows that the highlighted end on the right is connected to the SFP Transceiver on the router, while the other end of the cable shown on the left is connected to port 16 on the switch.

![[Pasted image 20220829000159.jpg]]
In some cases, the other end of a cable can only be seen by looking at the back view of the devices, such as when looking at the Ethernet cable connected to a server. If you don't see the other end of your selected cable in your current view, remember to look in the Selected Component panel or explore the Workspace, remembering to view both the front and back views.
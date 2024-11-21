# Questions 7.1
1. Match each switch management method on the left with its corresponding characteristics on the right. Each method may be used once, more than once, or not at all. 
	1. Competes with normal network traffic for bandwidth.
		1. In-band management
	2. Uses a dedicated communication channel.
		1. Out-of-band management
	3. Must be encrypted to protect communications from sniffing.
		1. In-band management
	4. Does not compete with normal network traffic for bandwidth.
		1. Out-of-band management
	5. Affected by network outages.
		1. In-band management
2. Which level of the OSI model does a Layer 2 switch operate at?
	1. Data Link Layer
3. Which of the following is a device that can send and receive data simultaneously?
	1. Full-duplex
4. On your network, you have a VLAN for the sales staff and a VLAN for the production staff. Both need to be able to communicate over the network. Which of the following devices would work BEST for communication between VLANs?
	1. Layer 3 switch
5. As a network administrator, you have 10 VLANs on your network that need to communicate with each other. Which of the following network devices is the BEST choice for allowing communication between 10 VLANs?
	1. Layer 3 switch
6. Match each type of switch on the left with its corresponding characteristics on the right. Each switch type may be used once, more than once, or not at all.
	1. Commonly sold at retail stores.
		1. Unmanaged switch
	2. Provides port security features.
		1. Managed switch
	3. Supports VLANs.
		1. Managed switch
	4. Provides very few configuration options.
		1. Unmanaged switch
	5. Can be configured over a network connection.
		1. Managed switch
	6. Can be configured over a dedicated communication channel.
		1. Managed switch
7. Which of the following is required to establish a new network switch and configure its IP address for the first time?
	1. Out-of-band management
8. Which of the following methods is best to have when a network goes down?
	1. Out-of-band management
9. Which of the following is a communication device that connects other network devices through cables and receives and forwards data to a specified destination within a LAN?
	1. Switch
10. Which of the following is true about an unmanaged switch?
	1. It can connect to all devices in a small area.


# Questions 7.2
1. Which of the following is the open standard for tagging Layer 2 frames?
	1. 802.1q
2. Which of the following protocols prescribes what to do when a data channel is in use on a half-duplex device?
	1. CSMA/CD
3. A switch receives a frame with a destination MAC address that is not found in its MAC address table. What happens next?
	1. The frame is replicated and sent to every active port on the switch except the source port.
4. Which of the following is the protocol used for address resolution when you switch from IPv4 to IPv6?
	1. NDP
5. In which type of device is a MAC address table stored?
	1. Switch
6. You run a small network for your business that has a single router connected to the internet and a single switch. You keep sensitive documents on a computer that you would like to keep isolated from other computers on the network. Other hosts on the network should not be able to communicate with this computer through the switch, but you still need to access the network through the computer. Which of the following should you use in this situation?
	1. VLAN
7. For which of the following devices does a voice VLAN prioritize traffic?
	1. VoIP Phone
8. What does the **ip address dhcp** command allow you to do?
	1. Configure a switch to obtain an IP address from a DHCP server.
9. Which command would you use on a switch to enable management from a remote network?
	1. **ip default-gateway 192.168.10.185**
10. You are configuring a switch so that you can manage it using PuTTY from the same network segment. On the switch, you enter the following commands:
		switch#config terminal  
		switch(config)#interface vlan 1  
		switch(config-if)#ip address 192.168.1.10 255.255.255.0
		Will this configuration work?
	1. No. The **no shutdown** command needs to be entered.

# Questions 7.3
1. Which statements accurately describe the port states of both bridges and switches? (Select two.)
	1. In the learning state, the MAC address table can be populated, but frames are not forwarded.
	2. Ports in a blocked state still receive BPDUs.
2. You manage a single subnet with three switches. The switches are connected to provide redundant paths between themselves. Which feature prevents switching loops and ensures that there is only a single active path between any two switches?
	1. Spanning Tree
3. You manage a network with two switches. The switches are connected together through their Gigabit Ethernet uplink ports. You define VLAN 1 and VLAN 2 on each switch. A device on the first switch in VLAN 1 needs to communicate with a device on the second switch in VLAN 1. What should you configure to allow communication between these two devices through the switches?
	1. Trunking
4. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_conf_switch_ports_np6/q_conf_switch_port_vlan_id_01_np6.jpg) Computers A and B are on the same VLAN and are separated by two switches as shown in the exhibit. Computer A sends a frame to Computer B. Which of the following BEST describes the frame's composition as it travels from A to B?
	1. Computer A sends a normal frame. The first switch appends a VLAN ID to the frame. The second switch removes the VLAN ID before forwarding it to Computer B.
5. Which of the following BEST describes port aggregation?
	1. Multiple ports linked together and used as a single logical port.
6. Which of the following BEST describes Ethernet flow control?
	1. A configuration that sends a pause frame to the transmitting device when the receiving device cannot keep up with the volume of data being sent.
7. Which of the following must each device's MTU be set to for jumbo frames to transverse the network without risk of fragmentation?
	1. 9000
8. Your organization's management wants to monitor all the customer services calls. The calls are taken on VoIP phones. Which of the following configurations would BEST help you set up a way to monitor the calls?
	1. Port mirroring
9. You have a large Power over Ethernet flat screen that you are installing in a conference room that requires 70 watts of power. Which of the following IEEE standards does your PoE switch need to provide power for the flat screen?
	1. PoE++ Type 4
10. Which of the following switch features allows you to configure how the switch's MAC address table is filled?
	1. Port security

# Questions 7.4
1. Which of the following scenarios would typically utilize 802.1x authentication?
	1. Controlling access through a switch.
2. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_switch_security_np6/ivlan2.png)You have two switches connected together as shown in the following diagram. How many broadcast domains are in the network?
	1. Two
3. You are the network administrator for a city library. Throughout the library are several groups of computers that provide public access to the internet. Supervision of these computers has been difficult. You've had problems with patrons bringing personal laptops into the library and disconnecting the network cables from the library computers to connect their laptops to the internet. The library computers are in groups of four. Each group of four computers is connected to a hub that's connected to the library network through an access port on a switch. You want to restrict access to the network so that only library computers are permitted connectivity to the internet. What can you do?
	1. Configure port security on the switch.
4. Which of the following BEST describes an ARP spoofing attack?
	1. An attack that associates an attacker's MAC address with the IP address of a victim's device.
5. Which of the following is a method of VLAN hopping?
	1. Double tagging
6. Drag each description on the left to the appropriate switch attack type on the right.
	1. ARP spoofing/poisoning
		1. The source device sends frames to the attacker's MAC address instead of to the correct device.
	2. Dynamic Trunking Protocol
		1. Should be disabled on the switch's end user (access) ports before implementing the switch configuration in to the network.
	3. MAC flooding
		1. Causes packets to fill up the forwarding table and consumes so much of the switch's memory that it enters a state called fail open mode.
	4. MAC spoofing
		1. Can be used to hide the identity of the attacker's computer or impersonate another device on the network.
7. An attacker hides his computer's identity by impersonating another device on a network. Which of the following attacks did the attacker MOST likely perform?
	1. MAC spoofing attack
8. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_switch_attacks_np6/q_switch_attacks_root_01_np6.png)You have just connected four switches as shown in the Exhibit. Assuming the default switch configuration, how can you force switch C to become the root bridge?
	1. Configure a priority number of 4096 for switch C.
9. Which of the following switch attacks bypasses the normal functions of a router to communicate between VLANs and gain unauthorized access to traffic on another VLAN?
	1. Switch spoofing
10. Which of the following attacks manipulates a switch's auto-negotiation setting to access a virtual local area network that's connected to the same switch as the attacker's virtual local area network?
	17. Vlan spoofing



# Questions 7.5
1. Which of the following BEST describes dynamic routing?
	1. Routers learn about networks by sharing routing information with each other.
2. Jake is a network administrator for a hospital. There is medical equipment that relies on having uninterrupted internet connectivity. Which of the following types of routing protocols should Jake focus on to ensure that the hospital's network connectivity remains reliable?
	1. Exterior dynamic routing protocols
3. Which of the following has the least default administrative distance?
	1. Static route to an IP address
4. Under which of the following circumstances might you implement BGP on your company network and share routes with internet routers?
	1. If the network is connected to the internet using multiple ISPs.
5. A router is connected to network 192.168.1.0/24 and network 192.168.2.0/24. The router is configured to use RIP and has learned both networks. The next hop router for network 192.168.3.0 has changed. You need to make the change with the least amount of effort possible. What should you do?
	1. Wait for convergence to take place.
6. Which of the following routing protocols is a hybrid that uses a composite number for its metric based on bandwidth and delay?
	1. EIGRP
7. Which of the following are true of the IS-IS routing protocol? (Select two.)
	1. It supports IPv6 routing.
	2. It divides large networks into areas.
8. What are the main differences between the OSPF and IS-IS routing protocols?
	1. OSPF requires an area 0, while IS-IS does not.
9. What is the main difference between RIP and RIPv2?
	1. RIP is a classful protocol, while RIPv2 is a classless protocol.
10. You have only one physical interface but want to connect two IP networks. Which of the following would allow you to do so?
	1. Subinterfaces

# Questions 7.6 
1. Which of the following is true about Network Address Translation?
	1. It supports up to 5,000 concurrent connections.
2. Which of the following allows incoming traffic addressed to a specific port to move through the firewall and be transparently forwarded to a specific host on the private network?
	1. DNAT
3. Which device is NAT typically implemented on?
	1. Default gateway router'
4. Which of the following NAT implementations maps a single private IP address to a single public IP address on the NAT router?
	1. Static NAT
5. Which of the following do hosts on a private network share if the network utilizes a NAT router?
	1. A physical IP address
6. Which of the following is a method that allows you to connect a private network to the internet without obtaining registered addresses for every host?
	1. NAT
7. Kate, a network administrator, has been tasked with staying within the company budget. She has a large network and doesn't want to spend more than she needs to on purchasing and registering multiple public IP addresses for each of the hosts on her network. Which of the following methods could help her provide internet access but also keep costs low and limit the number of registered IP addresses her organization needs to purchase?
	1. Use Network Address Translation.
8. Which of the following is NOT one of the IP address ranges defined in RFC 1918 that are commonly used behind a NAT server?
	1. 169.254.0.1 to 169.254.255.254
9. You are the network administrator for a small company that implements NAT to access the internet. However, you recently acquired five servers that must be accessible from outside your network. Your ISP has provided you with five additional registered IP addresses to support these new servers, but you don't want the public to access these servers directly. You want to place these servers behind your firewall on the inside network, yet still allow them to be accessible to the public from the outside. Which method of NAT translation should you implement for these servers?
	1. Static
10. In which of the following tables does a NAT router store port numbers and their associated private IP addresses?
	1. Translation table

# Questions 7.7 
1. Which of the following best describes DHCP scope exhaustion?
	1. A denial of service from a lack of IP addresses in a DHCP server's pool.
2. You have just connected a new computer to your network. The network uses static IP addressing. You find that the computer can communicate with hosts on the same subnet, but not with hosts on a different subnet. No other computers are having issues. Which of the following configuration values would you MOST likely need to change?
	1. Default gateway
3. A workstation's network board is currently configured as follows:
-   Network Speed = Auto
-   Duplexing = Auto
The workstation is experiencing poor network performance, and you suspect that the network board is incorrectly detecting the network speed and duplex settings. Upon investigation, you find that it's running at 10 Mbps half-duplex. You know that your network switch is capable of much faster throughput. To fix this issue, you decide to manually configure these settings on the workstation.
Before you do so, you need to verify the switch port configuration for the connected workstation. Given that it's a Cisco switch, which commands can you use on the switch to show a list of all switch ports and their current settings? (Select two.)
	1. **show running-config interface**
	2. **show interface**
4. Which of the following utilities would you use to view the routing table?
	1. route
5. You are unsure if the gateway address is correct for one of your subnetworks because traffic is not leaving the network. Which of the following tables could you look at to check if the gateway address is correct?
	1. Routing table
6. Which of the following scenarios would cause a problem in asymmetric routing?
	1. Using two stateful firewalls in the traffic flow.
7. You manage a network with multiple switches. You find that your switches are experiencing heavy broadcast storms. Which of the following will help reduce the effects of these broadcast storms?
	1. Enable Spanning Tree on the switches.
8. Which of the following can cause broadcast storms?
	1. Switching loops
9. You run a small network for your business that has a single router connected to the internet and a single switch. You keep sensitive documents on a computer that you would like to keep isolated from other computers on the network. Other hosts on the network should not be able to communicate with this computer through the switch, but you still need to access the network through the computer. What should you use for this situation?
	1. Vlan
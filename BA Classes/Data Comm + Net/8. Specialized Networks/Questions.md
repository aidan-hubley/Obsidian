#DataCommNetworking
# Questions 8.1
1. Which of the following BEST defines a SAN?
	1. A block-level storage network
2. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_san_np6/q_san_cluster_np6.png) You manage a network with three dedicated storage devices, as shown in the diagram. Users on the network see only a single file server. Which network-based storage technology is being used?
	1. NAS with clustering
3. Which of the following are the components of a SAN?
	1. Hosts, storage, and SAN fabric
4. Arrange the Fibre Channel (FC) SAN implementation tasks in the order they should be performed to build a redundant FC SAN.
	1. Step 1
		1. Install two Fiber Channel host bus adapters in each server that will access the shared storage on the SAN.
	2. Step 2
		1. Deploy two FC switches.
	3. Step 3
		1. Using fiber optic cables, connect each server to each FC switch by connecting one FC HBA to one FC switch and the other FC HBA to the other FC switch.
	4. Step 4
		1. Deploy the shared storage devices, such as an external RAID device containing multiple hard disk drives and two FC HBAs.
	5. Step 5
		1. Using fiber optic cables, connect each storage device to each FC switch by connecting one FC HBA to one FC switch and the other FC HBA to the other FC switch.
5. Brett has been tasked with creating a new SAN. The company currently has Gigabit internet, and his CTO wants to use Fibre Channel over Ethernet (FCoE) in the SAN. Brett tells the CTO that this will not work. Which of the following BEST describes the problem?
	1. Fibre Channel over Ethernet requires 10 Gigabit internet.
6. What BEST describes the designed purpose of InfiniBand?
	1. High-performance supercomputers
7. You are in the process of configuring an iSCSI storage area network (SAN) for your network. You want to configu
8. re a Windows Server system to connect to an iSCSI target defined on a different server system. You also need to define iSCSI security settings, including CHAP and IPsec. Which tool should you use?
	1. ISCSI initiator
9. Within an SDN, what is commonly referred to as the brains?
	1. Controllers
10. Which option BEST describes the third layer in the SDN architecture?
	1. Infrastructure
11. What are the three layers of an SDN?
	1. Application, Control, and Infrastructure

# Questions 8.2
1. Which of the following BEST describes the main purpose of the codec used in VoIP?
	1. An algorithm to compress data in order to save on bandwidth.
2. Which of the following BEST describes VoIP (Voice over Internet Protocol)?
	1. A protocol optimized for voice data transmission (telephone calls) through a packet-switched IP network.
3. Which of the following are considered VoIP endpoints?
	1. Hard phones and soft phones
4. Larry is tasked with implementing a VoIP system in the office. He presents his research to his boss, who wants to use the current hard phones to save money. What BEST explains why this is not possible?
	1. A hard phone does not have the internal computing parts to accept VoIP transmissions.
5. Amber, a network administrator, is conducting VoIP training for other IT team members. Melanie, a new team member, is confused about the difference between latency and jitter. What is the BEST way to explain the difference?
	1. Jitter is the up and down variation in latency.
6. Dan, a network administrator, gets an email from the CEO. She is upset because people keep talking over each other on conference calls. Which option BEST describes Dan's first step to remedy this problem?
	1. Check the latency configuration. Latency should be set between 75 and 150 milliseconds.
7. Dan, a network administrator, has noticed a consistent increase in bandwidth consumption since installing a new VoIP system. The increase is outside of the parameters given by the vendor. What is MOST likely the issue Dan needs to address?
	1. The codec needs to be replaced with a more efficient one.
8. VoIP uses several protocols. Which layer of the OSI model do these protocols reside on?
	1. Transport
9. What is the MOST common Transport layer protocol that VoIP uses?
	1. UDP
10. Upper management has asked you if there is a way to integrate phone calls, emails, and instant messaging into a single platform. Which of the following systems should you recommend?
	1. Unified communications


# Questions 8.3
1. Which of the following are advantages of virtualization? (Select two.)
	1. Centralized administration.
	2. Easy system migration to different hardware.
2. Which hardware components are controlled by the hypervisor?
	1. RAM, CPU, storage
3. John is using a host machine with a Type1 hypervisor. He has 40 virtual servers using unmodified guest OSs. Which type of virtualization BEST describes this configuration?
	1. Full virtualization
4. How many types of full virtualization are there?
	1. Two
5. In virtualization, what is the role of a hypervisor?
	1. A hypervisor allows virtual machines to interact with the hardware without going through the host operating system.
6. Which of the following BEST describes an enterprise-level hypervisor?
	1. Type 1
7. Amber's employer has asked her to research what is needed to best utilize current assets in creating a scalable network. Amber knows that the company has two very robust servers. What is her BEST solution?
	1. Convert the existing servers into host servers for virtualization using a Type 1 hypervisor.
8. Which hypervisor is for bare metal use?
	1. Type 1
9. Which form of virtualization does not virtualize the hardware?
	1. Paravirtualization
10. Which resource is nearly impossible to decrease once allocated in virtualization?
	1. Storage


# Questions 8.4
1. You want to be able to monitor and filter VM-to-VM traffic within a virtual network. What should you do?
	1. Implement a virtual firewall within the hypervisor.
2. Which of the following statements are true about virtual NICs? (Select two.)
	1. Multiple virtual NICs can be added to a virtual machine.
	2. Virtual NICs need the appropriate driver to function.
3. Which key advantage does a virtual router have over a physical router?
	1. Multiple networks can connect to a single interface.
4. ![[Pasted image 20221209235125.png]]
5. ![[Pasted image 20221209235733.png]]
6. You are an application developer. You use a hypervisor with multiple virtual machines installed to test your applications on various operating system versions and editions. Currently, all of your test virtual machines are connected to the production network through the hypervisor's network interface. You are concerned that the latest application you are working on could adversely impact other network hosts if errors exist in the code. To prevent problems, you decide to isolate the virtual machines from the production network. However, they still need to be able to communicate directly with each other. What should you do? (Select two. Each response is one part of the complete solution.)
	1. Connect the virtual network interfaces in the virtual machines to the virtual switch.
	2. Create a new virtual switch configured for host-only (internal) networking.
7. You are responsible for maintaining Windows workstation operating systems in your organization. Recently, an update from Microsoft was automatically installed on your workstations that caused an in-house application to stop working. To keep this from happening again, you decide to test all updates on a virtual machine before allowing them to be installed on production workstations. Currently, none of your test virtual machines has a network connection. However, they need to be able to connect to the update servers at Microsoft to download and install updates. What should you do? (Select two. Each response is one part of the complete solution.)
	1. Connect the virtual network interfaces in the virtual machines to the virtual switch.
	2. Create a new virtual switch configured for bridged (external) networking.
8. Which component is MOST likely to allow physical and virtual machines to communicate with each other?
	1. Virtual switch
9. You need to provide DHCP and file sharing services to a physical network. These services should be deployed using virtualization. Which type of virtualization should you implement?
	1. Virtual servers
10. Your organization uses a time-keeping application that only runs on Windows 2000 and does not run on newer OS versions. Because of this, there are several Windows 2000 workstations on your network. Last week, you noticed unusual activity on your network coming from the Windows 2000 workstations. After further examination, you discovered that the Windows 2000 workstations were the victim of a malicious attack and were being used to infiltrate the network. You find out that the attackers were able to gain access to the workstations because of the legacy operating system being used. The organization still needs to use the Windows 2000 workstations, which need to be connected to the internet, but you want to make sure the network is protected from future events. Which solution should you implement to protect the network while also allowing operations to continue as normal?
	1. Configure VLAN membership so that the Windows 2000 workstations are on their own VLAN.

# Questions 8.5
1. Which of the following are true regarding cloud computing? (Select three.)
	1. Typical cloud computing providers deliver common business applications online. They are accessed from another web service or software, like a web browser.
	2. The term cloud is used as a synonym for the internet.
	3. Cloud computing consists of software, data access, computation, and storage services provided to clients through the internet.
2. Match each description on the left with the appropriate cloud technology on the right.
	1. Public cloud
		1. Provides cloud services to just about anyone.
	2. Private cloud
		1. Provides cloud services to a single organization.
	3. Community cloud
		1. Allows cloud services to be shared by several organizations.
	4. Hybrid cloud
		1. Integrates one cloud service with other cloud services.
3. You were recently hired by a small startup company. The company is in a small office and has several remote employees. You have been asked to find a business service that can both accommodate the company's current size and scale as the company grows. The service needs to provide adequate storage as well as additional computing power. Which cloud service model should you use?
	1. IaaS
4. Which of the following cloud computing solutions delivers software applications to a client either over the internet or on a local area network?
	1. SaaS
5. Which of the following are benefits that a VPN provides? (Select two.)
	1. Cost savings
	2. Compatibility
6. Which of the following provides a VPN gateway that encapsulates and encrypts outbound traffic from a site and sends the traffic through a VPN tunnel to the VPN gateway at the target site?
	1. Site-to-site IPsec VPN
7. What is a VPN (virtual private network) primarily used for?
	1. Support secure communications over an untrusted network.
8. IPsec is implemented through two separate protocols. What are these protocols called? (Select two.)
	1. ESP
	2. AH
9. Which other service is IPsec composed of, in addition to AH?
	1. Encapsulating Security Payload (ESP)
10. Which of the following are IPsec modes of operation? (Select two.)
	1. Transport mode
	2. Tunnel mode

# Questions 8.6
1. What are two major concerns regarding IoT devices? (Select two.)
	1. Privacy
	2. Hacking
2. You notice that a growing number of devices, such as environmental control systems and wearable devices, are connecting to your network. These devices, known as smart devices, are sending and receiving data via wireless network connections. Which of the following labels applies to this growing ecosystem of smart devices?
	1. Internet of Things (IoT)
3. Which of the following is considered part of a smart home?
	1. Thermostat
4. Which of the following are examples of newer devices that are often automated using IoT technology? (Select three.)
	1. Streaming media devices
	2. Security systems
	3. Home appliances
5. Match each smart device with its description.
	1. Thermostat
		1. Learns from your habits and schedule, allows you to control the climate in your home remotely, shows you energy consumption in real time, and adjusts itself depending on ambient conditions.
	2. Switch
		1. Allows you to control hardwired lights, ceiling fans, fireplaces, small appliances, and garbage disposals.
	3. Bulb
		1. Can change colors, track motion, stream audio over Bluetooth, and double as a connected camera, but it's only smart when turned on. It doesn't work when turned off.
	4. Plug
		1. Easy solution for making small appliances (such as lamps, coffee makers, and toasters) smart.
	5. Security camera
		1. Uses an RF transmitter. May include such features as motion detection, scheduled recording, remote viewing, and automatic cloud storage.
	6. Door lock
		1. Uses a wireless protocol and a cryptographic key to execute the authorization process. It can also monitor access and send alerts related to the status of the device.
	7. Speaker/digital assistant
		1. Uses voice recognition software and activates through a Wake Word or Hot Word.
6. Which frequencies does Zigbee operate on?
	1. 2.4 GHz, 900 MHz, and 868 MHz
7. Anabel purchased a smart speaker. She connected it to all the smart devices in her home. Which of the following communication models is she using?
	1. Device-to-device
8. What is the maximum number of nodes Z-Wave allows on its mesh network?
	1. 232
9. What are the two protocols used most often with IoT devices? (Select two.)
	1. Zigbee
	2. Z-Wave
10. What are the four primary systems of IoT technology?
	1. Devices, gateway, data storage, and remote control
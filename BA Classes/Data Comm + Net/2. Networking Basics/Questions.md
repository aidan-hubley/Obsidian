#DataCommNetworking
# 2.1.7 Questions
1. You've implemented a network where hosts are assigned specific roles, such as file sharing and printing roles. Other hosts access those resources, but they don't host services of their own. Which type of network do you have?
	1. Client-server
2. Which of the following geographic network types is typically managed by a city as a public utility?
	1. Metropolitan area network (MAN)
3. You've implemented a network where each device provides all other devices on the network with access to shared files. Which type of network do you have?
	1. Peer-to-peer
4. You have a network that uses a logical bus topology. How do messages travel through the network?
	1. Messages are broadcast to all devices connected to the network
5. You have a network that uses a logical ring topology. How do messages travel through the network?
	1. Messages travel from one device to the next until they reach the destination device.
6. Your manager has asked you to implement a wired network infrastructure that will accommodate failed connections. You don't have a large budget, so you decide to provide redundancy for only a handful of critical devices. Which of the following network topologies should you implement?
	1. Partial Mesh
7. Which of the following topologies connects all devices to a trunk cable?
	1. Bus
8. Your manager has asked you to implement a network infrastructure that will accommodate failed connections. Which of the following network topologies provides redundancy for a failed link?
	1. Mesh
9. Which of the following topologies connects each device to a neighboring device?
	1. Ring
10. You have a small network that uses a switch to connect multiple devices. Which physical topology are you using?
	1. Star

# 2.2.6 Questions
1. In the OSI model, which of the following functions are performed at the Application layer? (Select two.)
	1. Integration of network functionality into the host operating system.
	2. Enabling of communication between network clients and services.
2. Which of the following are included as part of the Data Link layer specifications? (Select two.)
	1. Data transmission between hosts
	2. Physical network device identification
3. In the OSI model, what is the primary function of the Network layer?
	1. Route messages between networks.
4. What is the basic purpose of the OSI Physical layer?
	1. Coordinate rules for sending and receiving electrical signals.
5. In the OSI model, which of the following functions are performed at the Presentation layer? (Select two.)
	1. Data format specifications
	2. Data encryption and compression
6. Which of the following tasks is associated with the Session layer?
	1. Connection establishment
7. During TCP/IP communication between two network hosts, information is encapsulated on the sending host and decapsulated on the receiving host using the OSI model. Match the information format on the left with the appropriate layer of the OSI model on the right.
	1. Transport Layer -> Segments
	2. Network Layer -> Packets
	3. Data Link Layer -> Frames
	4. Physical Layer -> Bits
8. Which of the following functions are performed by the OSI Transport layer? (Select three.)
	1. Data segmentation and reassembly
	2. Reliable message delivery
	3. End-to-end flow control
9. Match each networking function or device on the left with its associated OSI model layer on the right.
	1. Application Layer -> HTTP
	2. Presentation Layer -> Encapsulation
	3. Session Layer -> Session ID Number
	4. Transport Layer -> Port Number
	5. Network Layer -> Router
	6. Data Link Layer -> Switch
	7. Physical Layer -> Modem
10. Match each layer of the TCP/IP model on the left with the corresponding layer of the OSI model on the right. Each option on the left can be used more than once.
	1. Presentation Layer -> Application
	2. Data Link Layer -> Network
	3. Application Layer -> Application
	4. Session Layer -> Application
	5. Network Layer -> Internetwork
	6. Transport Layer -> Transport

# 2.3.8 Questions
1. Which of the following is the process of breaking a message into packets, adding controls and other information, and then transmitting the message through the transmission medium?
	1. Encapsulation
2. What is the purpose of a frame check sequence (FCS) footer?
	1. Checksum error detection
3. Which term does the OSI model use that's different from the TCP/IP model in reference to the terms frame, packet, and segment?
	1. Protocol Data Unit (PDU)
4. Match each TCP/IP layers with its function.
	1. Breaks the data into pieces -> Transport
	2. Prepares the data to be sent -> Application
	3. Adds physical addresses -> Link
	4. Adds logical addresses -> Internet
5. Workstation2 needs to send data to Workstation3. Identify the Layer 2 and Layer 3 addresses Workstation2 will use to send the data by dragging the corresponding address from the list on the left to its location on the right. ![[Pasted image 20220904230313.png]]
	1. Layer 2 source address -> 080046987654
	2. Layer 3 source address -> 192.168.10.12
	3. Layer 2 destination address -> 000b5f2a2222
	4. Layer 3 destination address -> 192.168.11.11
6. Workstation3 has started communicating with Workstation2. It sends a frame to the default gateway. Identify the Layer 2 and Layer 3 addresses used by the Cisco 2600 router to forward the data to Workstation2 by dragging the corresponding address from the list on the left to its location on the right.![[Pasted image 20220904230435.png]]
	1. Layer 2 source address -> 000b5f2a2222
	2. Layer 3 source address -> 192.168.11.11
	3. Layer 2 destination address -> 080046987654
	4. Layer 3 destination address -> 192.168.10.12
7. What role does ARP play in the routing process?
	1. If a router does not know a destination device's MAC address, it sends an ARP broadcast containing the destination device's IP address and requesting its MAC address.
8. Routing data between computers on a network requires several mappings between different addresses. Which of the following statements is true?
	1. Routers use ARP to resolve known IP addresses into MAC addresses.
9. During network transmission, data is transferred to various routers, which forward the data to the appropriate network. If the source and destination network addresses reside on the same network, which protocol is used to determine the destination IP's MAC address?
	1. ARP
10. TCP is a connection-oriented protocol that uses a three-way handshake to establish a connection to a system port. Computer 1 sends a SYN packet to Computer 2. Which packet does Computer 2 send back?
	1. SYN/ACK

# 2.4.6 Questions
1. Which of the following protocols allows hosts to exchange messages to indicate problems with packet delivery?
	1. ICMP
2. You have a large TCP/IP network and want to keep a host's real-time clock synchronized. Which protocol should you use?
	1. NTP
3. Your company has just acquired another company in the same city. You need to integrate the two email systems so that messages can be exchanged between email servers. Currently, each network uses an email package from a different vendor. Which TCP/IP protocol enables message exchange between systems?
	1. SMTP
4. You're an application developer, and you're writing a program for exchanging video files through a TCP/IP network. You need to select a transport protocol that will guarantee delivery. Which TCP/IP protocol provides this capability?
	1. TCP
5. Which of the following features does UDP provide? (Select two.)
	1. Low overhead
	2. Connectionless datagram services
6. You've recently installed a new Windows server. To ensure system time accuracy, you've loaded an application that synchronizes the hardware clock on the server with an external time source on the internet. Now you must configure your network firewall to allow time synchronization traffic through. Which of the following ports are you MOST LIKELY to open on the firewall?
	1. 123
7. Which port number is used by SNMP?
	1. 161
8. You're configuring a network firewall to allow SMTP outbound email traffic and POP3 inbound email traffic. Which of the following TCP/IP ports should you open on the firewall? (Select two.)
	1. 25
	2. 110
9. Which port does Telnet use?
	1. 23
10. Which of the following network services or protocols uses TCP/IP port 69?
	1. TFTP
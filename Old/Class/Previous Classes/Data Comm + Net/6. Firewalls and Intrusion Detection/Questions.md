# 6.1 Questions
1. Which of the following is true about a firewall?
	1. You must manually specify which traffic you want to allow through the firewall. Everything else is blocked.
2. Which options are you able to set on a firewall? (Select three.)
	1. Port number
	2. Packet destination address
	3. Packet source address
3. You have been given a laptop to use for work. You connect the laptop to your company network, use the laptop from home, and use it while traveling. You want to protect the laptop from internet-based attacks. Which solution should you use?
	1. Host-based firewall
4. Which of the following is true about a network-based firewall?
	1. A network-based firewall is installed at the edge of a private network or network segment
5. How does a proxy server differ from a packet-filtering firewall?
	1. A proxy server operates at the Application layer, while a packet-filtering firewall operates at the Network layer.
6. Based on the diagram, which type of proxy server is handling the client's request?![[Pasted image 20221104233820.png]]
	1. Reverse proxy server
7. Which of the following are true about reverse proxy? (Select two.)
	1. Can perform load balancing, authentication, and caching.
	2. Handles requests from the internet to a server on a private network.
8. Which device combines multiple security features, such as anti-spam, load-balancing, and antivirus, into a single network appliance?
	1. Unified Threat Management (UTM)
9. Which of the following chains is used for incoming connections that aren't delivered locally?
	1. Forward
10. Which of the following does the **sudo iptables -F** command accomplish?
	1. Clears all the current rules


# 6.2 Questions
1. Your company has an internet connection. You also have a web server and an email server that you want to make available to your internet users, and you want to create a screened subnet for these two servers. Which of the following should you use?
	1. A network-based firewall
2. Which of the following combines several layers of security services and network functions into one piece of hardware?
	1. Unified Threat Management (UTM)
3. Which of the following are specific to extended Access control lists? (Select two.)
	1. Are the most used type of ACL
	2. Use the number ranges 100-199 and 2000-2699
4. Which of the following describes how access control lists can improve network security?
	1. An access control list filters traffic based on the IP header information, such as source or destination IP address, protocol, or socket number.
5. Your Cisco router has three network interfaces configured.
	-   S0/1/0 is a WAN interface that is connected to an ISP.
	-   F0/0 is connected to an Ethernet LAN segment with a network address of 192.168.1.0/24.
	-   F0/1 is connected to an Ethernet LAN segment with a network address of 192.168.2.0/24.
	You have configured an access control list on this router using the following rules:
	-   deny ip 192.168.1.0 0.0.0.255 any
	-   deny ip 192.168.2.0 0.0.0.255 any
	These rules will be applied to the WAN interface on the router. Your goal is to block any IP traffic coming in on the WAN interface that has a spoofed source address that makes it appear to be coming from the two internal networks.
	However, when you enable the ACL, you find that no traffic is being allowed through the WAN interface. What should you do?
	1. Add a permit statement to the bottom of the access list
6. Which of the following are true about routed firewalls? (Select two.)
	1. Supports multiple interfaces
	2. Counts as a router hop
7. Which of the following is a firewall function?
	1. packet filtering
8. You have used firewalls to create a screened subnet. You have a web server that needs to be accessible to internet users. The web server must communicate with a database server to retrieve product, customer, and order information. How should you place devices on the network to best protect the servers? (Select two.)
	1. Put the web server inside the screened subnet
	2. Put the database server on the private network
9. Which of the following BEST describes a stateful inspection?
	1. Determines the legitimacy of traffic based on the state of the connection from which the traffic originated.
10. Which of the following are characteristics of a packet-filtering firewall? (Select two.)
	1. Stateless
	2. Filters IP address and port


# 6.3 Questions
1. Which of the following terms describes a network device that is exposed to attacks and has been hardened against those attacks?
	1. Bastion
2. How many network interfaces does a dual-homed gateway typically have?
	1. three
3. You have a company network that is connected to the internet. You want all users to have internet access, but you need to protect your private network and users. You also need to make a web server publicly available to the internet users. Which solution should you use?
	1. Use firewalls to create a screened subnet. Place the web server inside the screened subnet and the private network behind the screened subnet.
4. You are managing a network and have used firewalls to create a screened subnet. You have a web server that internet users need to access. It must communicate with a database server to retrieve product, customer, and order information. How should you place devices on the network to best protect the servers? (Select two.)
	1. Put the database server on the private network
	2. Put the web server inside the screened subnet
5. In which of the following situations would you MOST likely implement a screened subnet?
	1. You want to protect a public web server form attack
6. Which of the following can serve as a buffer zone between a private, secured network and an untrusted network?
	1. Screened subnet
7. What do you need to configure on a firewall to allow traffic directed to the public resources on the screened subnet?
	1. Packet filters
8. Which of the following is another name for a firewall that performs router functions?
	1. Screening router
9. Which of the following uses access control lists (ACLs) to filter packets as a form of security?
	1. Screened router
10. Which of the following is the BEST solution to allow access to private resources from the internet?
	1. VPN


# 6.4 Questions
1. Which IDS method defines a baseline of normal network traffic and then looks for anything that falls outside of that baseline?
	1. Anomaly-based
2. Which of the following describes the worst possible action by an IDS?
	1. The system identified harmful traffic as harmless and allowed it to pass without generating any alerts.
3. Which IDS traffic assessment indicates that the system identified harmless traffic as offensive and generated an alarm or stopped the traffic?
	1. False positive
4. As a security precaution, you've implemented IPsec to work between any two devices on your network. IPsec provides encryption for traffic between devices. You would like to implement a solution that can scan the contents of the encrypted traffic to prevent any malicious attacks. Which solution should you implement?
	1. Host-based IDS
5. Which of the following is true about an intrusion detection system?
	1. An intrusion detection system monitors data packets for malicious or unauthorized traffic.
6. You're concerned about attacks directed at your network firewall. You want to be able to identify and be notified of any attacks. In addition, you want the system to take immediate action to stop or prevent the attack, if possible. Which tool should you use?
	1. IPS
7. Which of the following is true about an NIDS?
	1. It detects malicious or unusual incoming and outgoing traffic in real time.
8. Which IDS type can alert you to trespassers?
	1. PIDS
9. Which IDS method searches for intrusion or attack attempts by recognizing patterns or identifying entities listed in a database?
	1. Signature-based IDS
10. You've just installed a new network-based IDS system that uses signature recognition. What should you do on a regular basis?
	1. Update the signature files
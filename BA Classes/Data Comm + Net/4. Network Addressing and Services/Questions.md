#DataCommNetworking
# 4.1 Questions
1. What is the correct binary form of the decimal IP address 192.168.1.1?
	1. 11000000.10101000.00000001.00000001
2. What is the decimal form of the following binary IP address 11001101.00111001.10101001.01000010
	1. 205.57.169.66
3. Your network uses a network address of 137.65.0.0 with a subnet mask of 255.255.0.0. How many IP addresses are available to assign to network hosts on this network?
	1. 65534
4. Which of the following best describes the purpose of using subnets?
	1. Subnets divide an IP network address into multiple network addresses
5. You have a small network with three subnets, as shown in the exhibit. IP addresses for each router interface are also indicated in the exhibit.![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_subnets_np6/q_subnets_hosts_02_np6.png)How many IP addresses that you can assign to hosts remain on each subnet?
	1. SubnetA = 125, SubnetB = 0, SubnetC = 13
6. Your network has a network address of 172.17.0.0 with a subnet mask of 255.255.255.0. Which of the following are true concerning this network? (Select two.)
	1. 172.17.0.255 is the network broadcast address.
	2. 254 IP addresses can be assigned to host devices.
7. You have a small network with a single subnet connected to the internet, as shown in the exhibit. The router has been assigned the two addresses shown. You need to manually configure the workstation to connect to the network. The workstation should use RouterA as the default gateway and DNS1 as the DNS server address. From the drop-down menu options, select the appropriate parameters to configure the workstation's TCP/IP settings.
	1. IP address
		1. 192.168.12.46
	2. Subnet mask
		1. 255.255.255.240
	3. Default gateway
		1. 192.168.12.34
	4. DNS server
		1. 198.162.1.22
8. A host has an address of 100.55.177.99/16. Which of the following is the broadcast address for the subnet?
	1. 100.55.255.255
9. Which organization is responsible for allocating public IP addresses?
	1. IANA
10. Which of the following devices is MOST LIKELY to be assigned a public IP address?
	1. A router that connects your home network to the internet.

# 4.2 Questions
1. Which network address and subnet mask does APIPA use? (Select two.)
	1. 255.255.0.0
	2. 169.254.0.0
2. Which of the following IP address ranges is reserved for Automatic Private IP Addressing (APIPA)?
	1. 169.254.0.1 - 169.254.255.254
3. CorpServ is a small company with 14 client systems and a network printer. Because there are only a limited number of network systems, you decide to use APIPA addressing. With APIPA configured, all the systems are able to communicate with each other, but you're having trouble configuring internet access. What is the MOST LIKELY cause of the problem?
	1. Private addresses cannot directly communicate with hosts outside the local subnet.
4. Which of the following is a valid APIPA address?
	1. 169.254.32.50
5. Which of the following needs to be configured when a device receives its IP configuration from APIPA?
	1. Subnet Mask
	2. IP address
6. Which protocol is used by a device to ensure that an APIPA address is not already in use on the network?
	1. ARP
7. You are the network administrator for a small consulting firm. The office network consists of 30 computers, one server, two network printers, and a switch. Due to security concerns, there is no wireless network available in the office. One of your users, Bob, travels to client sites and is generally not in the office. When Bob goes to client sites, he typically just connects to their wireless networks. When he's in the office, Bob connects his laptop to the network with an Ethernet cable. You need to make sure that Bob's laptop is setup so that when he plugs the Ethernet cable into his laptop, no further configuration is needed. Which of the following would be the BEST option to achieve this?
	1. Configure an alternate IP configuration.
8. You are the network administrator for a large hospital. One of your users, Suzie, calls you stating that she is unable to access any network resources. After some initial troubleshooting, you realize that her computer is using the IP address 169.254.0.52. You've performed the following troubleshooting steps so far: -   Verified physical network connection -   Attempted to renew the IP address -   Discovered other devices are experiencing the same issue. Which of the following is the MOST likely cause for Suzie's issue?
	1. The DHCP server is misconfigured or down.
9. You are the network administrator for a small consulting firm. Users are complaining that they are unable to reach network resources. After some troubleshooting, you've confirmed that the DHCP server is down. Your network devices should be receiving an APIPA address so that they can at least communicate on the internal network, but many devices are not receiving this address. Which of the following is the MOST likely reason the devices are not receiving their APIPA addresses?
	1. The DHCP lease has not expired.
10. You are the network administrator for a large hospital. One of your users, Suzie, calls you stating that she is unable to access any network resources. After some initial troubleshooting, you realize that her computer is using the IP address 169.254.0.52. You've confirmed that the network's physical connection is connected properly. Which of the following should you do next?
	1. Renew the IP address.

# 4.3 Questions
1. Which of the following statements about Dynamic Host Configuration Protocol (DHCP) are true? (Select two.)
	1. A DHCP server assigns addresses to requesting hosts.
	2. It can deliver other configuration information in addition to IP addresses.
2. You have a TCP/IP network with 50 hosts. There have been inconsistent communication problems between these hosts. You run a protocol analyzer and discover that two of them have the same IP address assigned. Which protocol can you implement on your network to help prevent problems such as this?
	1. DHCP
3. Due to wide network expansion, you've decided to upgrade your network by configuring a DHCP server. The network uses Linux, Windows, and Mac OS X client systems. You configure the server to distribute IP addresses from 192.168.2.1 to 192.168.2.100. You use the subnet mask of 255.255.255.0. After you make all the setting changes on the DHCP server, you reboot each client system, but they are not able to obtain an IP address from the DHCP server. Which of the following explains the failure?
	1. You must configure the clients to obtain IP addressing from a DHCP server.
4. Which of the following strategies do we use to prevent duplicate IP addresses from being used on a network? (Select two.)
	1. Install a DHCP server on the network.
	2. Use Automatic Private IP Addressing (APIPA).
5. You recently created a new network segment for the Development department. Because the hosts are now on a different network segment, they can no longer contact the DHCP server. Both network segments are connected via a Cisco router. Which of the following would be the BEST action to take to fix the problem?
	1. Implement an IP helper address on the router.
6. After you install a new DHCP server on your network, you need to verify that the network devices are receiving IP addressing via DHCP. You reboot a Windows 10 client system and, using the **ipconfig /all** command, receive the following information: Ethernet adapter Local Area Connection 1:  
	Description . . . . . . . . . . . : Intel(R) Ethernet Connection  
	Physical Address. . . . . . . . . : 02-00-4C-4F-3F-50  
	DHCP Enabled. . . . . . . . . . . : Yes  
	Autoconfiguration Enabled . . . . : Yes  
	Autoconfiguration IPv4 Address. . : 169.254.25.129  
	Subnet Mask . . . . . . . . . . . : 255.255.0.0  
	Default Gateway . . . . . . . . . :  
	DNS Servers . . . . . . . . . . . :
	
	Which of the following statements are true? (Select two).
	1. The client system is unable to reach the DHCP server.
	2. The client system is configured to use DHCP.
7. You've configured your organization's DHCP server to dynamically assign IP addresses and changed the default lease time from eight to four days. What impact, if any, will this have on the network?
	1. Increased network traffic
8. When a device renews its DHCP lease, which two steps in the DHCP process are skipped?
	1. Offer
	2. Discover
9. Which of the following DHCP scope options assigns a static IP configuration to a device using that device's MAC address?
	1. Reservation
10. You have a network with 50 workstations. You want to automatically configure the workstations with the IP address, subnet mask, and default gateway values. Which device should you use?
	1. DHCP server

# 4.4 Questions
1. You need to configure a Cisco RFC 1542-compliant router to forward any received DHCP frames to the appropriate subnet. The remote DHCP server's address is 172.16.30.1. Which of the following commands would you use to configure the router?
	1. ip helper-address 172.16.30.1
2. Which port is a DHCP Discover packet sent out on when a device first connects to a network?
	1. 67
3. Which port does the relay agent use when it sends DHCP information back to the client?
	1. 68
4. You are configuring the DHCP relay agent role on a Windows server. Which of the following is a required step for the configuration?
	1. Specify which server network interface the agent listens on for DHCP messages.
5. What is the first thing a device does when it connects to a network?
	1. Sends a DHCP Discover packet
6. On a typical network, what happens if a client attempts to receive DHCP configuration from a DHCP server that's located on a different subnet?
	1. The router drops the DHCP request.
7. Which of the following does the DHCP relay agent use to tell the DHCP server which pool of addresses to use?
	1. GIADDR
8. Which of the following would a device use to receive NTP configuration from a NTP server that's located on a different network?
	1. IP helper
9. You have a Windows Server 2016 system that you want to use as a DHCP relay agent. Which Windows Server 2016 service would you use to do this?
	1. Routing and Remote Access
10. Which of the following protocols does DHCP use when it sends out IP configuration?
	1. UDP

# 4.5 Questions
1. If dynamic DNS is in use, which of the following events causes a dynamic update of the host records? (Select two.)
	1. Renew the DHCP server's IP address lease
	2. Enter the ipconfig/registerdns command on a workstation
2. Which of the following services automatically creates and deletes host records when an IP address lease is created or released?
	1. Dynamic DNS
3. You are the network administrator for a small consulting firm. The firm has recently rolled out a new intranet site, and you are responsible for configuring the DNS. You are able to connect to the intranet site by using the IP address, but you cannot connect when you use the hostname. Which of the following do you need to configure so that the site can be accessed with the hostname?
	1. Forward lookup zone
4. Which of the following is the top-level domain in www.testout.com.'s fully qualified domain name (FQDN)?
	1. com
5. Which of the following is the first place a computer looks at during the name resolution process?
	1. HOSTS file
6. You want to implement a protocol on your network that allows computers to find a host's IP address from a logical name. Which protocol should you implement?
	1. DNS
7. Listed below are several DNS record types. Match each record type on the left with its function on the right.
	1. Points a hostname to an IPv4 address
		1. A
	2. Provides alternate names to hosts that already have a host record
		1. CNAME
	3. Points an IP address to a hostname
		1. PTR
	4. Points a hostname to an IPv6 address
		1. AAAA
	5. Identifies servers that can be used to deliver mail
		1. MX
8. What is the process of a DNS server asking other DNS servers to perform name resolution known as?
	1. Recursive lookup
9. You need to enable hosts on your network to find the IP address of logical names, such as srv1.myserver.com. Which device should you use?
	1. DNS server
10. You are the network administrator for a consulting firm. A website that users on your network visit has a habit of frequently changing its IP address. When these IP mappings change, users are unable to connect until you clear the DNS cache. Which of the following settings should you configure so that the cache does not need to be manually cleared every time?
	1. Time to live


# 4.6 Questions
1. Which of the following ports does NTP run on?
	1. 123
2. Which of the following works as an authoritative time device?
	1. Atomic clock
3. Which of the following will not function properly if there is a time mismatch error?
	1. Security certificates
4. What is it called when a system's clock begins to be off by a few seconds or even minutes?
	1. Time drift
5. Which of the following best describes NTP efficiency?
	1. One packet per minute is necessary to sync two machines to an accuracy of within a millisecond of one another.
6. What are the small, rapid variations in a system clock called?
	1. Jitter
7. You are the network administrator for a small consulting firm. You've set up an NTP server to manage the time across all the machines in the network. You have a computer that's experiencing a slight time drift of just a few seconds. Which time correction should you use to fix the system's clock?
	1. Slew
8. Which of the following is the highest stratum level allowed?
	1. 15
9. Which stratum level does the authoritative time device fall under?
	1. 0
10. Which of the following time standards does NTP use?
	1. UTC


# 4.7 Questions
1. Which of the following are valid IPv6 addresses? (Select two.)
	1. 141:0:0:0:15:0:0:1
	2. 6384:1319:7700:7631:446A:5511:8940:2552
2. Consider the following IPv6 address: FD01:0001:0001:005::7/64 Drag the component parts of this address on the left to the corresponding descriptions on the right. (Not all descriptions on the right have corresponding components on the left.) 
	1. Global routing prefix
		1. FD01:0001:0001:005
	2. Subnet ID
		1. :005
	3. Interface ID
		1. ::7
	4. Prefix length
		1. /64
	5. Global ID
	6. Unique local unicast prefix
		1. FD
3. You manage a network with two locations (Portland and Seattle). Both locations are connected to the internet. The computers in both locations are configured to use IPv6. You'd like to implement an IPv6 solution to meet the following requirements: -   Hosts in each location should be able to use IPv6 to communicate with hosts in the other location through the IPv4 internet. -   You want to use a site-to-site tunneling method instead of a host-to-host tunneling method. Which IPv6 solution should you use?
	1. 6to4 tunneling
4. You have a server at work with a custom application installed. Connections to the server that use the custom application must use IPv6, but the server is currently running IPv4. You're the only person who connects to the server, and you always use your Linux laptop for the connection. Your laptop supports both IPv4 and IPv6, but the rest of your company network runs only IPv4. You need a cost-effective solution to allow your laptop to connect to the server. Your solution must also support communication through NAT servers. Which client software should you use to connect to the server?
	1. Miredo
5. Which of the following are characteristics of Teredo tunneling? (Select three.)
	1. Can be used to send data over the internet
	2. Has dual-stack hosts
	3. Is configured between individual hosts
6. Based on the address prefix for each IPv6 address on the right, identify the address type from the list on the left. (Addresses may not represent actual addresses used in production.)
	1. 2001:6789:9078::ABCE:AFFF:FE98:0001
		1. Global Unicast
	2. FEA0::AB89:9FF:FE77:1234
		1. Link-Local
	3. FF02::1:2
		1. Multicast
	4. FD00::8907:FF:FE76:ABC
		1. Unique local
	5. FF00:98BD:6532::1
		1. Multicast
7. Which of the following IPv6 addresses is used by a host to contact a DHCP server?
	1. FF02::1:2
8. You need to design an IPv6 addressing scheme for your network. The following are key requirements for your design: -   Infrastructure hosts, such as routers and servers, are assigned static interface IDs. However, workstations, notebooks, tablets, and phones are assigned interface IDs dynamically. -   Internet access must be available to all hosts through an ISP. -   Site-to-site WAN connections are created using leased lines. Which type of IPv6 addressing is most appropriate for hosts on this network?
	1. Global unicast addressing
9. Which of the following IPv6 addresses is equivalent to the IPv4 loopback address of 127.0.0.1?
	1. ::1
10. You manage a network that uses IPv6 addressing. When clients connect devices to the network, they generate an interface ID and use NDP to learn the subnet prefix and default gateway. Which IPv6 address assignment method is being used?
	1. Stateless autoconfiguration


# 4.8 Questions
1. Which of the following address types shares multiple hosts and groups of computers that receive the same data stream?
	1. Multicast
2. Which type of address is the IP address 232.111.255.250?
	1. Multicast
3. Which address type do people use to support video conference calls consisting of multiple participants?
	1. Multicast
4. Which address type do people use to support video conference calls consisting of multiple participants?
	1. Begins with 01-00-5E and ends with a form of the IP multicast group address
5. Which of the following allows the same IPv6 address to be assigned to multiple interfaces?
	1. Anycast
6. Which of the following gives the same IP address to multiple servers and manually defines different routes on an IPv4 network?
	1. BGP
7. Which IP address do broadcast messages use?
	1. The last valid IP address on the subnet
8. Which protocol does an IP host use to inform a router that it wants to receive specific multicast frames?
	1. IGMP
9. Which type of address identifies which single host to send a packet to?
	1. Unicast
10. Which type of address is the IP address 198.162.12.254/24?
	1. Unicast


# 4.9 Questions
1. You manage a network that has multiple internal subnets. You connect a workstation to the 192.168.1.0/24 subnet. This workstation cannot communicate with any other host on the network. You run **ipconfig /all** and see the following:

Ethernet adapter Local Area Connection:  
Connection-specific DNS Suffix. : mydomain.local  
Description . . . . . . . : Broadcom network adapter  
Physical Address . . . . . : 00-AA-BB-CC-74-EF  
DHCP Enabled. . . . . . . : No  
Autoconfiguration Enabled . . : Yes  
IPv4 Address. . . . . . . : 192.168.2.102(Preferred)  
Subnet Mask . . . . . . . : 255.255.255.0  
Default Gateway. . . . . . : 192.168.1.1  
DNS Servers . . . . . . . : 192.168.2.20 
What is the MOST likely cause of the problem?
	1. Incorrect IP address
2.  You administer a network with Windows Server 2016, UNIX servers, and Windows 10 Professional, Windows 8, and Macintosh clients. A Windows 8 computer user calls you one day and says that he is unable to access resources on the network. You type **ipconfig** on the user's computer and receive the following output:

0 Ethernet adapter:

IP address. . . . . . . . . : 169.254.1.17  
Subnet Mask . . . . . . . . : 255.255.0.0  
Default Gateway . . . . . . :

You also check your NIC and see that the link light is on.What might the problem be in this scenario?
	1. An unavailable DHCP server
3. You are a network technician for a small consulting firm. One of your users is complaining that they are unable to connect to the local intranet site. After some troubleshooting, you've determined that the intranet site can be connected to by using the IP address but not the hostname. Which of the following would be the MOST likely reason for this?
	1. Incorrect DNS setting
4. Which two commands do you use to force a new IP configuration?
	1. ipconfig /release
	2. ipconfig /renew
5. You are a network technician for a small consulting firm. One of your responsibilities is to manage the intranet site and configuration. You recently had to update the site's IP mapping due to a server upgrade. A user is having an issue with connecting to the intranet site now. When the user attempts to connect through their web browser, they receive a message that the page cannot be displayed. If you type in the IP address, the page loads fine. Which of the following commands should you use to fix this issue?
	1. ipconfig /flushdns
6. You manage a network that has multiple internal subnets. You connect a workstation to the 192.168.1.0/24 subnet. This workstation can communicate with some hosts on the private network, but not with other hosts. You run **ipconfig /all** and see the following:
Ethernet adapter Local Area Connection:  
Connection-specific DNS Suffix . : mydomain.local  
Description . . . . . . . : Broadcom network adapter  
Physical Address. . . . . . : 00-AA-BB-CC-74-EF  
DHCP Enabled . . . . . . . : No  
Autoconfiguration Enabled. . . : Yes  
IPv4 Address . . . . . . . : 192.168.1.102(Preferred)  
Subnet Mask . . . . . . . : 255.255.255.0  
Default Gateway. . . . . . . . . : 192.168.2.1  
DNS Servers. . . . . . . . . . . : 192.168.2.20
What is the most likely cause of the problem?
	1. Incorrect default gateway
7. You are the network administrator for a consulting firm. Your network consists of:
-   40 desktop computers
-   Two servers
-   Three network switches
-   Two network printers
You've been alerted to an issue with two desktop computers that are having problems communicating with the network. When only one computer is on, everything is fine. But when both computers are connected, the network connection is randomly dropped or interrupted. Which of the following would be the MOST likely cause for this?
	1. Duplicate MAC addresses
8. You manage a network that has multiple internal subnets. You connect a workstation to the 192.168.1.0/24 subnet. This workstation can communicate with some hosts on the private network, but not with other hosts. You run **ipconfig /all** and see the following:
Ethernet adapter Local Area Connection:  
Connection-specific DNS Suffix . : mydomain.local  
Description . . . . . . . : Broadcom network adapter  
Physical Address. . . . . . : 00-AA-BB-CC-74-EF  
DHCP Enabled . . . . . . . : No  
Autoconfiguration Enabled. . . : Yes  
IPv4 Address . . . . . . . : 192.168.1.102(Preferred)  
Subnet Mask. . . . . . . . : 255.255.0.0  
Default Gateway . . . . . . : 192.168.1.1  
DNS Servers . . . . . . . : 192.168.1.20  
192.168.1.27
What is the MOST likely cause of the problem?
	1. Incorrect subnet mask
9. You are a network technician for a small consulting firm. Many users have reported issues with accessing the network. After some initial troubleshooting, you discover that many devices have the same IP address assigned or incorrect IP configurations. Which of the following would be the MOST likely cause for this?
	1. Rogue DHCP server
10. You are a network technician for a small consulting firm. Many users have reported issues with accessing the network. After some initial troubleshooting, you discover that devices are not receiving their IP configurations. You look into the issue and discover that the network is being targeted by a denial-of-service attack. Which of the following is your network MOST likely experiencing?
	1. DHCP starvation attack

# 4.10/11 Questions
1. You're troubleshooting an IP addressing issue, and you issue a command to view the system's TCP/IP configuration. The command you use produces the following output:
fxp0: flags=8843<UP,BROADCAST,RUNNING,SIMPLEX,MULTICAST> mtu 1500  
inet6 fe80::2a0:83ff:fe30:57a%fxp0 prefixlen 64 scopeid 0x1  
inet 192.168.1.235 netmask 0xfffffc00 broadcast 255.255.255.255  
ether 00:a0:83:30:05:7a  
media: Ethernet autoselect (100baseTX <full-duplex>)  
status: active  
lo0: flags=8049<UP,LOOPBACK,RUNNING,MULTICAST> mtu 16384  
inet6 ::1 prefixlen 128  
inet6 fe80::1%lo0 prefixlen 64 scopeid 0x7  
inet 127.0.0.1 netmask 0xff000000

Which of the following operating systems are you working on?
	1. Linux 
2. You've been called in to troubleshoot a connectivity problem on a newly installed Windows Server system. The system is operating well and is able to communicate with other systems on the local network. However, it's unable to access any systems on other segments of the corporate network. You suspect that the system's default gateway parameter hasn't been configured or may be configured incorrectly. Which of the following utilities are you MOST likely to use to view the system's default gateway information?
	1. ipconfig
3. Examine the following output:

Reply from 64.78.193.84: bytes=32 time=86ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=43ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=44ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=47ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=44ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=44ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=73ms TTL=115  
Reply from 64.78.193.84: bytes=32 time=46ms TTL=115

Which of the following utilities produced this output?
	1. ping
4. Which TCP/IP utility gives you the following output?
![[Pasted image 20221104001125.png]]
	1. ping
5. While working on a Linux server, you're unable to connect to your Windows Server system across the internet. You're able to ping the default gateway on your own network, so you suspect that the problem lies outside of the local network. Which utility would you use to track the route a packet takes as it crosses the network?
	1. traceroute
6. Which TCP/IP utility gives you the following output?
Interface: 192.168.4.101 on Interface 0x3  
Internet Address Physical Address Type  
192.168.1.23 00-d1-b6-b7-c2-af dynamic
	1. arp
7. Which of the following tools would you use to view the MAC addresses associated with IP addresses that the local workstation has contacted recently?
	1. arp
8. Which TCP/IP utility gives you the following output?
![[Pasted image 20221104001235.png]]
	1. netstat -r
9. Your computer is sharing information with a remote computer using the TCP/IP protocol. Suddenly, the connection stops working and appears to hang. Which command can you use to check the connection?
	1. netstat
10. Examine the following output:
Active Connections  
Proto Local Address Foreign Address State  
TCP SERVER1:1036 localhost:4832 TIME_WAIT  
TCP SERVER1:4798 localhost:1032 TIME_WAIT  
TCP SERVER1:1258 pool-141-150-16-231.mad.east.ttr:24076 CLOSE_WAIT  
TCP SERVER1:2150 cpe-66-67-225-118.roc.res.rr.com:14100 ESTABLISHED  
TCP SERVER1:268 C872c-032.cpe.net.cale.rers.com:46360 ESTABLISHED  
TCP SERVER1:2995 ip68-97-96-186.ok.ok.cox.net:23135 ESTABLISHED

Which of the following utilities produced this output?
1. netstat

# 4.11 Questions
1. You are troubleshooting a network connectivity issue on a Unix system. You're able to connect to remote systems by using their IP address, but you're unable to connect using the hostname. You check the TCP/IP configuration and notice that a DNS server IP address is configured. You decide to run some manual resolution queries to ensure that the communication between the Unix system and the DNS server are working correctly. Which utilities can you use to do this? (Select two.)
	1. dig
	2. nslookup
2. Consider the following output.

;; res options: init recurs defnam dnsrch  
;;got answer:  
;;->>HEADER<<-opcode:QUERY, status; NOERROR,id:4  
;;flags: qr rd ra; QUERY:1, ANSWER:1, AUTHORITY:2, ADDITIONAL:0  
;;QUERY SECTION:  
;; westsim111.com, type = A, class = IN  
  
;;ANSWER SECTION:  
westsim111.com. 7h33m IN A 76.141.43.129  
;;AUTHORITY SECTION:  
westsim111.com. 7h33m IN NS dns1.deriatct111.com.  
westsim111.com. 7h33m IN NS dns2.deriatct222.com.  
;;Total query time: 78 msec  
;;FROM: localhost.localdomain to SERVER: default -- 202.64.49.150  
;;WHEN: Tue Feb 16 23:21:24 2005  
;;MSG SIZE sent: 30 rcvd: 103

Which of the following utilities produced this output?
	1. dig
3. Consider the following output from a **dig** command run on a Linux system.

; <<>> DiG 8.2 <<>> westsim111.com  
;;res options:init recurs defnam dnsrch  
;;got answer:  
;;->>HEADER<<-opcode:QUERY, status: NOERROR, id:4  
;;flags: qr rd ra; QUERY:1, ANSWER:1, AUTHORITY:2, ADDITIONAL:0  
;;QUERY SECTION:  
;; westsim111.com, type = A, class = IN  
  
;;ANSWER SECTION:  
westsim111.com. 7h33m IN A 76.141.43.129  
;;AUTHORITY SECTION:  
westsim111.com. 7h33m IN NS dns1.deriatct111.com.  
westsim111.com. 7h33m IN NS dns2.deriatct222.com.  
;;Total query time: 78 msec  
;;FROM: localhost.localdomain to SERVER:default -- 202.64.49.150  
;;WHEN: Tue Feb 16 23:21:24 2005  
;;MSG SIZE sent: 30 rcvd:103

What is the IP address of the DNS server that performed this name resolution?
	1. 202.69.49.150
4. Which of the following can you append to the end of the **dig** command to run a query for all the records in the zone?
	1. -axfr
5. A user reports that they cannot browse to a specific website on the internet. From the user's computer, a computer tech finds that a ping test to the web server succeeds. A traceroute test shows 17 hops to the destination web server. What is the MOST likely cause of the problem?
	1. Incorrect DNS server address
6. Which of the following commands do you use to clear the local DNS cache?
	1. ipconfig /flushdns
7. Mary calls to tell you that she can't connect to an intranet server called WebSrv1. From her computer, you ping the server's IP address. The ping test is successful. Which tool would you use on her workstation next to troubleshoot the problem?
	1. nsloopup
8. Examine the following output:
Server: to.xct.mirrorxhq.net  
Address: 209.53.4.130  
Name: westxsim.com  
Address: 64.78.193.84
Which of the following utilities produced this output?
	1. nslookup
9. You are using Linux and need to perform a reverse lookup of the IP address 10.0.0.3. Which command would you use to accomplish this?
	1. **dig -x 10.0.0.3**
10. Which of the following commands should you use to check the route a packet takes between a workstation and the DNS server?
	1. tracert
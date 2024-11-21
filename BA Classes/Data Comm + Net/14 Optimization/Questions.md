#DataCommNetworking
# Questions 14.1
1. A web server on your network hosts your company's public website. You want to make sure that an NIC failure doesn't prevent the website from being accessible on the internet. Which solution should you implement?
	1. Ethernet bonding
2. What is the purpose of using Ethernet bonding? (Select two.)
	1. Increases network performance.
	2. Provides a failover solution for network adapters.
3. Which of the following components do switches use to optimize network performance by performing switching operations in hardware rather than using the CPU and software?
	1. An application-specific integrated circuit
4. You have a website that uses multiple servers for different types of transactions. For example, one server is responsible for static web content, while another is responsible for secure transactions. You would like to implement a device to speed up access to your web content. The device should be able to distribute requests between the various web servers using specialized hardware, not just software configurations. In addition, SSL sessions should use the hardware components in the device to create the sessions. Which type of device should you use to accomplish this?
	1. Content switch
5. Which of the following statements about DSCP are true? (Select two.)
	1. Classification occurs at Layer 3.
	2. It uses the DiffServ field to add precedence values.
6. Which type of switch optimizes network performance by using ASIC to perform switching at wire speed?
	1. Multilayer switch
7. Match the Class of Service (CoS) priority on the left with its corresponding value on the right.
	1. 0
		1. Background
	2. 1
		1. Best effort
	3. 2 
		1. Excellent effort
	4. 3
		1. Critical applications
	5. 4
		1. Video (< 100 ms latency)
	6. 5
		1. Voice (< 10 ms latency)
	7. 6
		1. Internetwork control
	8. 7
		1. Network control
8. Which Class of Service (CoS) priority value should be assigned to a video conference call?
	1. 4
9. You are in the process of implementing a network access protection (NAP) infrastructure to increase your network's security. You are currently configuring the remediation network that non-compliant clients will connect to in order to become compliant. You need to isolate the remediation network from the secure network. Which technology should you implement to accomplish this task?
	1. Network segmentation
10. Your organization uses a time-keeping application that only runs on Windows 2000 and does not run on newer OS versions. Because of this, there are several Windows 2000 workstations on your network. Last week, you noticed unusual activity on your network coming from the workstations. After further examination, you discover that they were victims of a malicious attack and were being used to infiltrate the network. You find out that the attackers were able to gain access to the workstations because of the legacy operating system being used. Your organization still needs to use the Windows 2000 workstations (which need to be connected to the internet) but you want to make sure that the network is protected from future attacks. Which solution should you implement to protect the network while also allowing operations to continue as normal?
	1. Configure VLAN membership so that the Windows 2000 workstations are on their own VLAN.

# Questions 14.2
1. A user reports that she can't connect to the internet. After some investigation, you find that the wireless router has been misconfigured. You're responsible for managing and maintaining the wireless access point. What should you do next?
	1. Create an action plan.
2. A user reports that she can't connect to a server on your network. You check the problem and find out that all users are having the same problem. What should you do next?
	1. Determine what has changed.
3. Users report that the network is down. As a help desk technician, you investigate and determine that a specific router is configured so that a routing loop exists. What should you do next?
	1. Determine if escalation is needed.
4. A user reports that he can't connect to a specific website. You go to the user's computer and reproduce the problem. What should you do next?
	1. Identify the affected areas of the network.
5. A user is unable to connect to the network. You investigate the problem and determine that the network adapter is defective. You replace the network adapter and verify that it works. What should you do next?
	1. Identify the results and side effects of the solution.
6. A router periodically goes offline. Once it goes offline, you find that a simple reboot puts the router back online. After doing some research, you find that the MOST likely cause is a bug in the router software. A new patch is available from the manufacturer that is supposed to eliminate the problem. What should you do next?
	1. Identify possible side effects of the solution.
7. When troubleshooting network issues, it's important to carry out tasks in a specific order. Drag each trouble shooting task on the left to the correct step on the right.
	1. Step 1
		1. Identify the problem.
	2. Step 2
		1. Establish a theory of probable cause.
	3. Step 3
		1. Test the theory to determine the cause.
	4. Step 4
		1. Establish a plan of action.
	5. Step 5
		1. Implement the solution or escalate.
	6. Step 6
		1. Verify full system functionality.
	7. Step 7
		1. Document findings, actions, and outcomes.
8. You are a network administrator for your company. A frantic user calls you one morning exclaiming that nothing is working. What should you do next in your troubleshooting strategy?
	1. Establish the symptoms.
9. You are a network administrator for your company. A user calls and tells you that after stepping on the network cable in her office, she can no longer access the network. You go to the office and see that some of the wires in the Cat 5 network cable are now exposed. You make another cable and attach it from the wall plate to the user's computer. What should you do next in your troubleshooting strategy?
	1. Test the solution.
10. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_network_issues_np6/q_network_issues_loop_np6.jpg)

A new assistant network administrator was recently hired by your organization to relieve some of your workload.

You assigned the assistant network administrator to replace a defective patch cable that connected port 1 on your patch panel to one of your network switches. You noticed that it took him an unusually long time to complete this task. Once done, users almost immediately began to report that the network had gone down.

Upon entering the server room, you see that the assistant administrator has configured your network rack as shown below.

What should you do? (Choose two. Each response is a complete solution.)
	1. Remove the patch cable connecting the first switch to the third switch.
	2. Enable STP on each switch.

# Questions 14.3
1. Which of the following tools would you use to view the MAC addresses associated with IP addresses that the local workstation has contacted recently?
	1. arp
2. You are troubleshooting a connectivity problem on a Linux server. You're able to connect to another system on the local network but not to a server on a remote network. You suspect that the default gateway information for the system may be configured incorrectly. Which of the following commands would you use to view the default gateway information on the Linux server?
	1. ifconfig
3. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_cli_utilities_np6/q_cli_utilities_ipconfig_01_np6.png)Which TCP/IP utility gives you the following output?
	1. ipconfig
4. Examine the following output:

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
5. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_cli_utilities_np6/q_cli_utilities_ping_02_np6.png)Which TCP/IP utility gives the following output?
	1. ping
6. While working on a Linux server, you're unable to connect to the Windows Server system on the internet. You are able to ping the default gateway on your own network, so you suspect that the problem lies outside the local network. Which utility would you use to track the route a packet takes as it crosses the network?
	1. traceroute
7. A security analyst is using tcpdump to capture suspicious traffic detected on port 443 of a server. The analyst wants to capture the entire packet with hexadecimal and ASCII output only. Which of the following tcpdump options will achieve this output?
	1. **-SX port 443**
8. You want to make sure that a set of servers will only accept traffic for specific network services. You have verified that the servers are only running the necessary services, but you also want to make sure that the servers will not accept packets sent to those services. Which tool should you use?
	1. Port scanner
9. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_trouble_wireshark_np6/q_trouble_wireshark_data_01_np6.jpg)You have been asked to perform a penetration test for a company to see if any sensitive information can be captured by a potential hacker. You used Wireshark to capture a series of packets. Using the tcp contains Invoice filter, you found one packet. Using the captured information shown, which of the following is the name of the company requesting payment?
	1. ACME, Inc
10. ![](https://cdn.testout.com/_version_6023/netpro2021v6-en-us/en-us/resources/text/t_trouble_wireshark_np6/q_trouble_wireshark_filter_02_np6.jpg)With Wireshark, you've used a filter to capture only the desired packet types. Using the information shown in the image, which of the following BEST describes the effects of using the host 192.168.0.34 filter?
	1. Only packets with 192.168.0.34 in either the source or destination address are captured.
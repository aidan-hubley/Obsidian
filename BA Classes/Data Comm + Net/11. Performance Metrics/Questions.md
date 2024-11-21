# Questions 11.1
1. What is the definition of bandwidth?
	1. The amount of data that can be transferred from one place to another in a specific amount of time.
2. Which of the following is a best practice when establishing a baseline?
	1. Determine baselines over time by analyzing network traffic.
3. Which of the following is the term for when a system is unable to keep up with the demands placed on it?
	1. Bottleneck
4. Which of the following is the term for a calculation of how often bits are damaged in transit due to electromagnetic interference?
	1. Error rate
5. When packets arrive at their destination at different speeds, they sometimes arrive out of order. What does this cause?
	1. Jitter
6. What is the definition of latency?
	1. The speed at which data packets travel from source to destination and back.
7. Your computer seems to be running slowly. In particular, you notice that the hard drive activity light remains lit when you run multiple applications and switch between open windows. This happens even though you aren't saving large files. What should you do to troubleshoot the problem?
	1. Use Resource Monitor to monitor memory utilization.
8. Which of the following is true about processor performance?
	1. A healthy system's CPU utilization should average around 40%.
9. Which of the following could be to blame if your computer is regularly crashing or restarting?
	1. The processor is too hot.
10. Where can you check your CPU's temperature?
	1. BIOS

# Questions 11.2
1. Which of the following does an agent send to the manager to confirm the receipt of a transmission?
	1. Inform
2. What is the name of the computer that queries agents and gathers responses by sending messages?
	1. Manager
3. Because of an unexplained slowdown on your network, you decide to install monitoring software on several key network hosts to locate the problem. You will then collect and analyze the data from a central network host. Which protocol will the software use to detect the problem?
	1. SNMP
4. What does SNMP use to identify a group of devices under the same administrative control?
	1. Community strings
5. Which of the following is true about a community string?
	1. A community string identifies devices under the same administrative control.
6. Which protocol uses traps to send notifications from network devices?
	1. SNMP
7. When an event occurs, the agent logs details regarding the event. What is this event called?
	1. Trap
8. You have been using SNMP on your network for monitoring and management, but you're concerned about the security of this configuration. What should you do to increase security in this situation?
	1. Implement version 3 of SNMP
9. Which of the following improvements to SNMP are included in version 3? (Select two.)
	1. SNMP message encryption
	2. Agent and manager authentication
10. Which SNMP component uses GETNEXT messages to navigate the MIB structure?
	1. Walk

# Questions 11.3
1. Some users report that frequent system crashes have started happening on their workstations. Upon further investigation, you notice that these users all have received a recent update to the same application. Where would you go to conduct a root cause analysis?
	1. Application log
2. You suspect that cache poisoning or spoofing has occurred on your network. Users are complaining of strange web results and being redirected to undesirable sites. Which log would help you determine what's going on?
	1. DNS logs
3. You suspect that a bad video driver is causing a user's system to randomly crash and reboot. Where would you go to identify and confirm your suspicions?
	1. Dump files
4. Which Syslog severity level indicates a debugging message?
	1. Level 7
5. Which Syslog level indicates an emergency that could severely impact the system and cause it to become unusable?
	1. Level 0 
6. Which of the following is a standard for sending log messages to a central logging server?
	1. Syslog
7. You are concerned that an attacker can gain access to your web server, make modifications to the system, and alter the log files to hide his or her actions. Which of the following actions would BEST protect the log files?
	1. Use Syslog to send log entries to another server
8. You are the network administrator for a growing business. When you were hired, the organization was small, and only a single switch and router were required to support your users. During this time, you monitored log messages from your router and switch directly from each device's console. The organization has grown considerably in recent months. Now you manage eight individual switches and three routers. It's becoming more and more difficult to monitor these devices and stay on top of issues in a timely manner. What should you do?
	1. Use Syslog to implement centralized logging
9. Over the past few days, a server has gone offline and rebooted automatically several times. You would like to see a record of when each of these restarts occurred. Which log type should you check?
	1. System
10. Which log file type is one of the most tedious to parse but can tell you exactly when a user logged onto your site and what their location was?
	1. Web server logs

# Questions 11.4
1. You want to identify the traffic that is generated and sent through a network by a specific application on a device. Which tool should you use?
	1. Protocol analyzer
2. Which of the following conditions can low humidity result in?
	1. Electrostatic discharge
3. You are using a protocol analyzer to capture network traffic. You want to only capture the frames coming from a specific IP address. Which of the following can you use to simplify this process?
	1. Capture filters
4. Most equipment is cooled by bringing cold air in the front and ducting the heat out the back. What is the term for where heat is sent?
	1. Hot aisle
5. You decide to use a packet sniffer to identify the type of traffic sent to a router. You run the packet sniffing software on a device that's connected to a hub with three other computers. The hub is connected to a switch that's connected to the router. When you run the software, you see frames addressed to the four workstations but not to the router. Which feature should you configure on the switch?
	1. Port mirroring
6. You want to know which protocols are being used on your network. You'd like to monitor network traffic and sort traffic by protocol. Which tool should you use?
	1. Packet sniffer
7. Which deviation in power is the longest?
	1. Blackout
8. You maintain the network for an industrial manufacturing company. You're concerned about the dust in the area getting into server components and affecting network availability. Which of the following should you implement?
	1. Positive pressure system
9. Your 24U rack currently houses two 4U server systems. To prevent overheating, you've installed a rack-mounted environmental monitoring device within the rack. Currently, the device shows that the temperature within the rack is 70 degrees Fahrenheit (21 degrees Celsius). What should you do?
	1. Nothing, the temperature within the rack is within acceptable limits.
10. Which of the following ensures that power is supplied to a server or device during short power outages?
	1. Uninterruptible power supply

# Questions 11.5
1. In business continuity planning, what is the primary focus of the scope?
	1. Business processes
2. You plan to implement a new security device on your network. Which of the following policies outlines the process you should follow before you implement that device?
	1. Change Management
3. Which of the following pieces of information are you MOST likely to find in a policy document?
	1. A requirement for using encrypted communications for web transactions
4. Which of the following information are you MOST likely to find in a procedure document?
	1. Details on how to test and deploy patches
5. Which of the following is a contract in which both parties agree not to share proprietary or confidential information gathered during the business relationship?
	1. Non-Disclosure Agreement
6. Which of the following defines an Acceptable Use Agreement?
	1. An agreement that identifies the employees' rights to use company property, such as internet access and computer equipment, for personal use.
7. You want to make sure that the correct ports on a firewall are open or closed. Which document should you check?
	1. Baseline configurations
8. Which of the following provides a layout of all electrical, plumbing, HVAC, and networking wiring and components?
	1. Floor plan
9. Which of the following provides information on the subnets within your network, including the subnet addresses and the routers connecting each subnet?
	1. Network diagram
10. Which type of documentation would you consult to find the location of RJ45 wall jacks and their endpoints in the intermediate distribution closet?
	1. Wiring schematic

# Questions 11.6
1. You manage your company's website, which uses a cluster of two servers with a single shared storage device. The shared storage device uses a RAID 1 configuration. Each server has a single connection to the shared storage and a single connection to your ISP. You want to provide redundancy so that a failure on a single component doesn't cause the website to become unavailable. What should you add to your configuration to accomplish this?
	1. Connect one server to the internet through a different ISP.
2. Why should you store backup media off site?
	1. To prevent the same disaster from affecting both the network and the backup media
3. In addition to performing regular backups, what must you do to protect your system from data loss?
	1. Regularly test restoration procedures.
4. You have purchased a solar backup power device to provide temporary electrical power to critical systems in your data center should the power provided by the electrical utility company go out. The solar panel array captures sunlight, converts it into direct current (DC), and stores it in large batteries. The power supplies on the servers, switches, and routers in your data center require alternating current (AC) to operate. Which electrical device should you implement to convert the DC power stored in the batteries into AC power that can be used in the data center?
	1. Inverter
5. Which of the following is the least effective power loss protection for computer systems?
	1. Surge protector
6. You are adding a new rack to your data center, which will house two new blade servers and a new switch. The new servers will be used for virtualization. The only space you have available in the data center is on the opposite side of the room from your existing rack, which already houses several servers, a switch, and a router. You plan to configure a trunk port on each switch and connect them with a straight-through UTP cable that will run across the floor of the data center. To protect equipment from power failures, you also plan to install a UPS on the rack along with redundant power supplies for the server. Will this configuration work?
	1. No, you should not run a cable across the data center floor.
7. You are adding a new rack to your data center, which will house two new blade servers and a new switch. The new servers will be used for file storage and a database server. The only space you have available in the data center is on the opposite side of the room from your existing rack, which already houses several servers, a switch, and a router. You plan to configure a trunk port on each switch and connect them with a crossover UTP plenum cable that will run through the suspended tile ceiling in the data center. To provide power for the new devices, you had an electrician install several new 20-amp wall outlets near the new rack. Each device on the rack will be plugged directly into one of these new wall outlets. What is wrong with this configuration? (Select two.)
	1. You should implement redundant power supplies for the network devices.
	2. You should implement a UPS between the wall outlet and the network devices.
8. Which of the following devices accepts incoming client requests and distributes those requests to specific servers?
	1. Load balancer
9. What is the purpose of using Ethernet bonding? (Select two.)
	1. Increases network performance
	2. Provides a failover solution for network adapters
10. A web server on your network hosts your company's public website. You want to make sure that a NIC failure on the server does not prevent the website from being accessible on the internet. Which solution should you implement?
	1. Ethernet bonding

# Questions 11.7
1. Which of the following are backed up during a differential backup?
	1. Only files that have changed since the last full backup.
2. Which backup strategy backs up only files that have the archive bit set and does not mark them?
	1. Differential
3. Which backup strategy backs up all files from a computer's file system (regardless of whether the file's archive bit is set or not) and then marks them as backed up?
	1. Full
4. Your network performs a full backup every night. Each Sunday, the previous night's backup tape is archived. On a Wednesday morning, the storage system fails. How many restore operations would you need to perform to recover all of the data?
	1. One
5. Of the following restoration processes, which would result in the fastest restoration of all data if a system failure occurred on Friday?
	1. Restore the full backup from Sunday and the last differential backup.
6. Your disaster recovery plan (DRP) calls for backup media to be stored at a different location. The location is a safe deposit box at the local bank. Because of this, the disaster recovery plan specifies that you must choose a method that uses the least amount of backup media but also allows you to quickly back up and restore files. Which backup strategy would BEST meet the DRP's specifications?
	1. Perform a full backup once per week and a differential backup the other days of the week.
7. Your network uses the following backup strategy. You create: Full backups every Sunday night. Differential backups Monday night through Saturday night. On Thursday morning, the storage system fails. How many restore operations would you need to perform to recover all of the data?
	1. Two
8. Which of the following are backed up during an incremental backup?
	1. Only files that have changed since the last full or incremental backup.
9. Your network uses the following backup strategy. You create: Full backups every Sunday night. Incremental backups Monday night through Saturday night. On a Thursday morning, the storage system fails. How many restore operations would you need to perform to recover all of the data?
	1. Four
10. Which of the following describe a system image backup?
	1. A system image contains everything on the system volume, including the operating system, installed programs, drivers, and user data files.

# Questions 11.8
1. Which port does Remote Desktop use?
	1. Port 3389
2. Which of the following is a tool that allows access to the graphical desktop environment of another Windows client system over a network connection?
	1. Remote Desktop
3. Which of the following is a role service that allows users with the Remote Desktop Connection client and an internet connection to connect on an internal network.
	1. RD Gateway
4. You are the desktop administrator for your company. You would like to manage the computers remotely using a tool with a graphical user interface (GUI). Which actions should you take to accomplish this? (Select two. Each answer is a possible solution.)
	1. Open Computer Management and connect to each remote computer.
	2. Establish a Remote Desktop connection to each computer.
5. You manage a server at work that has just been configured with a new application. Consequently, the server has crashed several times during the last week. You think that you've resolved the problem, but you'd like to be able to manage the server remotely just in case more issues occur. Which of the following protocols should you use for remote management? (Select two.)
	1. VNC
	2. ICA
6. Which of the following protocols or services would you associate with Windows Remote Desktop network traffic?
	1. RDP
7. You are in the middle of a big project at work. All of your work files are on a server at the office. You want to be able to access the server desktop, open and edit files, save the files on the server, and print files to a printer that's connected to a computer at home. Which protocol should you use?
	1. RDP
8. You just deployed a new Cisco router that connects several network segments in your organization. The router is physically located in a server room that requires an ID card for access. You backed up the router configuration to a remote location with an encrypted file. You access the router configuration interface from your notebook computer using a Telnet client with the username **admin** and the password **admin**. You used the MD5 hashing algorithm to protect the password. What else should you do to increase the security of this device? (Select two.)
	1. Use an SSH client to access the router configuration.
	2. Change the default administrative username and password.
9. Which of the following is a protocol used for terminal emulation?
	1. SSH
10. Which of the following remote protocols was originally designed for UNIX?
	1. VNC
#DataCommNetworking
# Questions 12.1
1. Which of the following BEST describes an inside attacker?
	1. An unintentional threat actor (the most common threat).
2. Which of the following is an example of an internal threat?
	1. A user accidentally deletes the new product designs.
3. Telnet is inherently unsecure because its communication is in plaintext and is easily intercepted. Which of the following is an acceptable alternative to Telnet?
	1. SSH
4. Which of the following protocols can you use to securely manage a network device from a remote connection?
	1. SSH
5. Which protocol does HTTPS use to offer greater security for web transactions?
	1. SSL
6. You want to allow traveling users to connect to your private network through the internet. Users will connect from various locations, including airports, hotels, and public access points (like coffee shops and libraries). As such, you won't be able to configure the firewalls that might be controlling access to the internet in these locations. Which of the following protocols is MOST likely to be allowed through the widest number of firewalls?
	1. SSL
7. Which of the following protocols are often added to other protocols to provide secure data transmission? (Select two.)
	1. SSL
	2. TLS
8. Which of the following intrusion detection and prevention systems uses fake resources to entice intruders by displaying a vulnerability, configuration flaw, or valuable data?
	1. Honeypot
9. Creating fake resources such as honeypots, honeynets, and tarpits fulfills which of the following main intrusion detection and prevention goals? (Select two.)
	1. Offers attackers a target that occupies their time and attention while distracting them from valid resources.
	2. Reveals information about an attacker's methods and gathers evidence for identification or prosecution purposes.
10. Members of the sales team use laptops to connect to the company network. While traveling, they connect their laptops to the internet through airport and hotel networks. You are concerned that these computers will pick up viruses that could spread to your private network. You would like to implement a solution that prevents the laptops from connecting to your network unless antivirus software and the latest operating system patches have been installed. Which solution should you use?
	1. NAC

# Questions 12.2
1. A network utilizes a network access control (NAC) solution to defend against malware. When a wired or wireless host tries to connect to the network, a NAC agent on the host checks it to make sure it has all of the latest operating system updates installed and that the latest antivirus definitions have been applied. What is this process called?
	1. Posture assessment
2. When analyzing assets, which analysis method assigns financial values to assets?
	1. Quantitative
3. What is the main difference between vulnerability scanning and penetration testing?
	1. Vulnerability scanning is performed within the security perimeter; penetration testing is performed outside of the security perimeter.
4. A security administrator is conducting a penetration test on a network. She connects a notebook system running Linux to the wireless network and then uses Nmap to probe various network hosts to see which operating system they are running. Which process did the administrator use for the penetration test in this scenario?
	1. Active fingerprinting
5. Drag each penetration test characteristic on the left to the appropriate penetration test name on the right.
	1. Known test
		1. The tester has detailed information about the target system prior to starting the test.
	2. Partially known test
		1. The tester has the same amount of information that would be available to a typical insider in the organization.
	3. Unknown test
		1. The tester has no prior knowledge of the target system.
	4. Single-blind test
		1. Either the attacker has prior knowledge about the target system or the administrator knows that the test is being performed.
	5. Double-blind test
		1. The tester does not have prior information about the system, and the administrator has no knowledge that the test is being performed.
6. Which SIEM component is responsible for gathering all event logs from configured devices and securely sending them to the SIEM system?
	1. Collectors
7. Which of the following Security Orchestration, Automation, and Response (SOAR) system components helps to document the processes and procedures that are to be used by a human during a manual intervention?
	1. Playbook
8. You want to make sure that a set of servers only accepts traffic for specific network services. You have verified that the servers are only running the necessary services, but you also want to make sure that the servers do not accept packets sent to those services. Which tool should you use?
	1. Port scanner
9. A security administrator logs on to a Windows server on her organization's network. Then she runs a vulnerability scan on that server. Which type of scan did she conduct in this scenario?
	1. Credentialed scan
10. You want to be able to identify the services running on a set of servers on your network. Which tool would BEST give you the information you need?
	1. Vulnerability 

# Questions 12.3
1. Five salespeople work out of your office. They frequently leave their laptops on the desks in their cubicles. You are concerned that someone might walk by and take one of these laptops. Which of the following is the BEST way to address your concerns?
	1. Use cable locks to chain the laptops to the desks.
2. What is the primary benefit of CCTV?
	1. Expands the area visible to security guards.
3. Which of the following CCTV types would you use in areas with little or no light?
	1. Infrared
4. Match each physical security control on the left with an appropriate example of that control on the right. Each security control may be used once, more than once, or not at all.
	1. Hardened carrier
		1. Protected cable distribution
	2. Biometric authentication
		1. Door locks
	3. Barricades
		1. Perimeter barrier
	4. Emergency escape plans
		1. Safety
	5. Alarmed carrier
		1. Protected cable distribution
	6. Anti-passback system
		1. Physical access control
	7. Emergency lighting
		1. Safety
	8. Exterior floodlights
		1. Perimeter barrier
5. You want to use CCTV as a preventative security measure. Which of the following is a requirement for your plan?
	1. Security guards
6. Which of the following is the MOST important way to prevent console access to a network switch?
	1. Keep the switch in a room that is locked by a keypad.
7. Which of the following controls is an example of a physical access control method?
	1. Locks on doors
8. Which of the following can you use to stop piggybacking from occurring at a front entrance where employees swipe smart cards to gain entry?
	1. Deploy a mantrap
9. You are an IT consultant and are visiting a new client's site to become familiar with their network. As you walk around their facility, you note the following:

-   When you enter the facility, a receptionist greets you and directs you down the hallway to the office manager's cubicle. The receptionist uses a notebook system that is secured to her desk with a cable lock.
-   The office manager informs you that the organization's servers are kept in a locked closet. Only she has the key to the closet. When you arrive on site, you will be required to get the key from her to access the closet.
-   She informs you that server backups are configured to run each night. A rotation of external USB hard disks are used as the backup media.
-   You notice the organization's network switch is kept in an empty cubicle adjacent to the office manager's workspace.
-   You notice that a router/firewall-content filter all-in-one device has been implemented in the server closet to protect the internal network from external attacks.

Which security-related recommendations should you make to this client? (Select two.)
	1. Control access to the work area with locking doors and card readers.
	2. Relocate the switch to the locked server closet.
10. Which of the following is a secure doorway that can be used with a mantrap to allow an easy exit but actively prevents re-entrance through the exit portal?
	1. Turnstiles

# Questions 12.4
1. An organization's receptionist received a phone call from an individual claiming to be a partner in a high-level project and requesting sensitive information. Which type of social engineering is this individual engaging in?
	1. Authority
2. What is the primary countermeasure to social engineering?
	1. Awareness
3. Match each social engineering description on the left with the appropriate attack type on the right.
	1. Phishing
		1. An attacker sends an email pretending to be from a trusted organization, asking users to access a website to verify personal information.
	2. Whaling
		1. An attacker gathers personal information about the target individual, who is a CEO.
	3. Spear phishing
		1. An attacker gathers personal information about the target individual in an organization.
	4. Dumpster diving
		1. An attacker searches through an organization's trash for sensitive information.
	5. Piggybacking
		1. An attacker enters a secure building by following an authorized employee through a secure door without providing identification.
	6. Vishing
		1. An attacker uses a telephone to convince target individuals to reveal their credit card information.
4. What is the definition of any attack involving human interaction of some kind?
	1. Social engineering
5. Dumpster diving is a low-tech way of gathering information that may be useful for gaining unauthorized access or as a starting point for more advanced attacks. How can a company reduce the risk associated with dumpster diving?
	1. Establish and enforce a document destruction policy.
6. You have just received a generic-looking email that is addressed as coming from the administrator of your company. The email says that as part of a system upgrade, you need enter your username and password in a new website so you can manage your email and spam using the new service. What should you do?
	1. Verify that the email was sent by the administrator and that this new service is legitimate.
7. Which of the following is a common social engineering attack?
	1. Hoax virus information emails.
8. On your way into the back entrance of your work building one morning, a man dressed as a plumber asks you to let him in so he can fix the restroom. What should you do?
	1. Direct him to the front entrance and instruct him to check in with the receptionist.
9. Which of the following are examples of social engineering attacks? (Select two.)
	1. Shoulder surfing
	2. Dumpster diving
10. A senior executive reports that she received a suspicious email concerning a sensitive internal project that is behind production. The email was sent from someone she doesn't know, and he is asking for immediate clarification on several of the project's details so the project can get back on schedule. Which type of attack BEST describes the scenario?
	1. Whaling

# Questions 12.5
1. While browsing the internet, you notice that the browser displays ads linked to recent keyword searches you performed. Which attack type is this an example of?
	1. Adware
2. What should you try first if your antivirus software does not detect and remove a virus?
	1. Update your virus detection software.
3. Which of the following best describes spyware?
	1. It monitors the actions you take on your machine and sends the information back to its originating source.
4. What is the main difference between a worm and a virus?
	1. A worm can replicate itself, while a virus requires a host for distribution.
5. Which of the following BEST describes the key difference between DoS and DDoS?
	1. Attackers use numerous computers and connections.
6. Which type of denial-of-service (DoS) attack occurs when a name server receives malicious or misleading data that incorrectly maps hostnames to IP addresses?
	1. DNS poisoning
7. Which of the following is an attack that either exploits a software flaw or floods a system with traffic in order to prevent legitimate activities or transactions from occurring?
	1. Denial-of-service attack
8. You are using a password attack that tests every possible keystroke for each single key in a password until the correct one is found. Which of the following technical password attacks are you using?
	1. Brute force attack
9. Which of the following is a text file that a website stores on a client's hard drive to track and record information about the user?
	1. Cookie
10. You are cleaning your desk at work. You toss several stacks of paper in the trash, including a sticky note with your password written on it. Which of the following types of non-technical password attacks have you enabled?
	1. Dumpster diving
11. As you are helping a user with a computer problem, you notice that she has written her password on a note stuck to her computer monitor. You check your company's Password Policy and find that the following settings are currently required:

-   Minimum password length = 10
-   Minimum password age = 4
-   Maximum password age = 30
-   Password history = 6
-   Account lockout clipping level = 3
-   Require complex passwords that include numbers and symbols

Which of the following is the best action to take to make remembering passwords easier so that the user no longer has to write their password down?
	1. Implement end user training

# Questions 12.6
1. A router on the border of your network detects a packet with a source address from an internal client, but the packet was received on the internet-facing interface. Which attack form is this an example of?
	1. Spoofing
2. What is spoofing?
	1. Changing or falsifying information in order to mislead or re-direct traffic.
3. Which type of activity changes or falsifies information in order to mislead or re-direct traffic?
	1. Spoofing
4. Which of the following is the term used to describe what happens when an attacker sends falsified messages to link their MAC address with the IP address of a legitimate computer or server on the network?
	1. ARP poisoning
5. Which of the following attacks can also be used to perform denial of service (DoS) attacks?
	1. ARP spoofing
6. Using sniffers has become one way for an attacker to view and gather network traffic. If an attacker overcomes your defenses and obtains network traffic, which of the following is the BEST countermeasure for securing the captured network traffic?
	1. Use encryption for all sensitive traffic.
7. Your network administrator is configuring settings so the switch shuts down a port when the max number of MAC addresses is reached. What is the network administrator taking countermeasures against?
	1. Sniffing
8. Which of the following is the MOST effective protection against IP packet spoofing on a private network?
	1. Ingress and egress filters
9. Which of the following describes an on-path attack?
	1. A false server intercepts communications from a client by impersonating the intended server.
10. Which of the following attack types consists of capturing packets as they travel from one host to another with the intent of altering the contents?
	1. On-path
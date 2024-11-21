# Why Database Security?
  
Most databases provide access spanning several  
networks and across the world  
- Most online transactions involve a database  
- Water supplies, electricity grids, and gas and oil production depend on a computer network to thrive  
	- Breach could have disastrous impact  
- Network intruders are well trained and growing more sophisticated

## A Secure Data Environment
- Multiple layers of security - user training, email filter, firewall
- 3 layers of security for secure data storage - database security, computer security, network security
- Database security
	- set of established procedures, standards, policies, and tools 
	- protect against theft, misuse, and attacks
	- deals with permissions and access to the data structure.
- Common vendor features for database security
	- database-level access control
	- database-level authentication
	- data storage encryption
- Computer security
	- Necessary element of database security
	- Typically defined by the operating system
- Common computer security features
	- Operating system-level access control
	- Operating system-level authentication
	- Application security
	- Hardware and software monitors and logs
Network security  
- Outermost layer of the database  
- Arguably biggest security concern  
- Set of established procedures, standards, policies, and tools  
– Goal: protect network from theft, misuse, and attacks  
Hardware and software devices used to secure a network  
- Firewalls, antivirus programs, network monitors, intrusion detections systems, proxy servers, and authentication servers

## Database Security Objectives
Security measures
- Keep information private from outside viewing
- Maintain consistency of data
- Ensure resources remain at a high degree of availability 
Key to achieve effective data security architecture
- Organization must maintain confidentiality, integrity, and availability of its environment
Confidentiality requirements
- Ensure information remains private by limiting authorized access to resources
- Block unauthorized access to resources
Confidentiality protected using authentication and access  
controls  
- State and federal laws may apply to these measures  
Breaches in confidentiality could result in:  
- Stolen identity  
- Exposed business trade secrets
Integrity  
- Reliable, accurate, and consistent data stored in and retrieved from the database  
- Protected by preventing accidental or deliberate  
modifications  
- Most difficult item to measure  
Auditing used to compare data with older, backed-up versions of the data  
Results of integrity breaches  
- Unreliable data, flawed programs, system failures
Availability  
- Maintaining accessible network or database resources  
- Business cannot operate without it  
Must identify potential threats to availability  
- Assess threat level  
- Plan appropriate intervention  
- Example of threats: technical failures, natural disasters, intrusions, user-caused harm
Must understand what poses a threat
- More threat exist on the inside of a network than on the outside
Overly restrictive database are as ineffective as those that give too much access
- Healthy balance is needed

## Social Engineers
- People who manipulate others to gain access to systems, unauthorized areas, or confidential information
	- Often build trust with authorized user  
	- Use deception and trickery to convince people to break normal security policies  
	- Example: asking for a password

## Computer Users
- Network users cause over half of security breaches
- Major contributing factors
	- Lack of education
	- Disregard of policy
- Examples of most common user errors
	- Poor habits (computers unlocked and unattended)
	- Password error (writing passwords on sticky notes)
	- Disregard for company policy (downloading unauthorized software)
	- Opening unknown e-mail attachments
	- Inappropriate disclosure (giving information over the phone to a social engineer)
	- Procrastination (failing to report computer issues in a timely manner)
- Computer-literate users may take risks and find shortcuts to security measures
- Disgruntled employee on a network can abuse access rights and destroy files

## Network and Database Administrators
- Not often viewed as threats to networks they run
	- Room for error exists
	- Their mistakes have consequences for integrity, availability, and reliability of the network
- Dynamic nature of the data environment
	- Can cause new security flaws to be created
	- Network components must be regularly audited
- Common mistake
	- Not removing a user's rights and account credentials

## The Internet
- Two billion internet users
- 100 million Web sites
- 85% of US residents have Internet access
- Online education and social networking increasing in popularity
- Threats on the Internet continue to increase
- 600,000 viruses on networks today
- Social interactions contribute to growing number of identity thefts
- Web page code purposes
	- To inform browser how to display the content
	- To inform browser how to react to user responses
- Hijacking
	- Web pages rewritten to distribute malicious code or redirect user to attacker's Web site
- Malware
	- Malicious software 
	- Written and used by unauthorized intruders
	- Often intended to be harmful and destructive
- Spoofing
	- Fraudulent Web site made to look identical to legitimate Web site
	- Objective: draw in a user to gather personal information (such as a password)
	- Can be easy as registering a domain name that is a slight misspelling of legitimate site (example: Google)
- Web browser
	- Application that interfaces client machine to Internet
	- Responsible for sending and receiving user pages
	- Has built-in programming language that can be manipulated
- SQL injection 
	- Intruders append malicious code onto a database-directed URL
	- Intended to manipulate database into sending confidential information
- HTTP portion of Web address informs browser of protocol used to send request for the Web site
	- Can include form-related data appended to URL
- Domain name server (DNS)
	- Database of domain names and their respective IP addresses
- DNS poisoning
	- Cracker gains control over DNS server
	- Cracker substitutes their site IP address for the legitimate domain name IP address
	- User may be fooled into providing personally identifiable information (PII)

## Misleading Application
- Applications designed to deceive users into believing their computer's security has been breached
	- User downloads and purchases fake antivirus tools
	- Tools deliver malware to user's computer
	- User has no knowledge of true security breach

## E-mails
- One of most common forms of communication today
- Biggest threat to network and database environment
	- Simple channel of attack for crackers
	- Most common way malicious code gains access to a business
- Common threats to e-mail
	- Attachments, phishing, HTML code attacks

## Malware
- Capable of performing harmful and destructive tasks on victim's computers
- Can be written in many programming languages
- Types of malware
	- Computer viruses
	- Worms
	- Trojans
	- Spyware
	- Adware
	- Bots

## Computer Viruses
- Form of malware designed to spread from one computer to another without detection
- Degree of danger varies:
	- From annoying disturbances to destruction of entire systems
- Characteristics found in malicious code
	- Self-encryption
		- Virus disguises the way it appears to a network
	- Stealth
		- Viruses make changes to the system
		- Need to avoid detection by antivirus program
		- Intercepts requests from antivirus programs and answers them, instead of the OS
	- Polymorphism
		- Ability to change forms to avoid detection
		- Code changes signature each time it infects a file 
	- Residence
		- Virus install itself directly in computer's main system memory
		- Virus does not need a user to make it active
- Classes of viruses
	- Logic bombs: viruses that corrupt data when certain conditions are met
	- Time bombs: time-delayed viruses
	- Spyware: software that intentionally monitors user's activities
	- Adware: malware used for marketing purposes
- Virus types
	- Boot sector viruses load themselves onto the hard drive's boot sector
	- Macro viruses: attached to or replace a macro in a document
	- File-infected viruses attach themselves to executable file which user must run to activate
	- Multipartite viruses combine characteristics of boot sector virus and file-infected virus

## Worms 
- Self-replicating malware
- Do not need users to travel from one computer to another
	- Propagate across networks
- Elements of a worm's travel
	- Find a weak target
	- Take control of the machine
	- Interrogate the machine
	- Test a new target
![[Pasted image 20230117104814.png]]

## Trojan Viruses
- Malware that disguises itself and its harmful code
- Hide within programs such software updates, games, and movies
- Purpose: gain access to sensitive information, destroy files, or create opportunities for installing bigger threats
- Types of Trojans
	- Remote access and administration Trojan (RAT)
		- Allows attacker to control victim's computer from a remote location
	- Data-sending Trojan
		- Sends information to attacker, usually with key loggers
	- Destructive Trojan
		- Randomly deletes files and corrupts the registry
	- Proxy Trojan
		- Attackers uses victim's IP address to commit cybercrime
	- File transfer protocol (FTP) Trojan
		- Allows attacker to download files from victim's computer

## Bots
- Also known as software robots
- Able to perform automated tasks for an intruder at a remote location
- Used for spamming and launching DoS attacks
- Can be hidden in games and other programs
- Can be e-mailed from one infected machine to another
- Able to disguise themselves, and run in the background
- Many bots controlled together known as a botnet

# Security Architecture: Never-Ending Cycle
- Creating a security architecture is not an easy task
- Techniques used to attack database developed using same technology used to protect the systems
	- Intruders become more advanced as technology advances
- New intrusions developed constantly
- Process of creating and maintaining security architecture has four phases

## Phase 1: Assessment and Analysis
- Determining an organization's data security needs
	- Identify existing vulnerabilities, threats, and assets
- Security audit
	- Used to identify threats
	- Can be conducted internally or by a third party
- Determine cost of breached or lost asset
	- Security measures should never exceed value of assets they protect
- Questions to ask to guide this phase are listed on Page 25 of the text 
	- What are the devices and resources with the database environment?
	- What type of threats exist within the database environment?
	- What are the assets that need protection?
	- What value do the assets have?
	- What cost would the threats incur?
	- What is the likelihood that each threat will occur?
	- What level of security is needed for each threat?
- Risk assessment steps
	- List all devices and resources within a database environment
	- Identify vulnerabilities and assets involved with each resource and device
	- Define asset value and cost of damage from the threats
	- Create security measures to counteract the threats
	- Prioritize the security measures

## Phase 2: Design and Modeling
- Create policies and prototype security architecture to fit business needs
- Entire organization should be included in the process
	- Policies must be realistic for user and business needs
- Questions to ask to guide this phase are listed on Page 26 of the text
- Design steps
	- Define needed policies and procedures
	- Identify firmware and software changes to support the policies
	- Create an implementation plan
	- Create baselines to determine success and failure
	- Define a plan for user training and awareness

## Phase 3: Deployment
- Security policies, firmware, and tools put in place
- Test environment usually create first
- Firmware and software purchased and tested
- Questions to guide this phase are listed on Page 26 of the text
	- Have user training adjustments been well accepted?
- Deployment steps
	- Adjust user awareness training as needed
	- Test firmware and software changes in a controlled simulation environment
	- Deploy changes according to the deployment plan

## Phase 4: Management and Support
- Monitor security system performance
- Reevaluate architecture after any failures or breaches
- Questions to guide this phase are listed on Page 27 of the text
- Management and support steps
	- Monitor performance of security architecture and user security awareness and training
	- Make minor policy revisions as necessary
	- Identify need for reassessment and initiate the start of the security life cycle

# Global Policies for the Database Environment
- Operational information security
	- Ensures secure operation of an organization
	- Uses reliable policies and procedures
	- Necessary component of maintaining database environment
- Aspects of information security
	- Security policies
	- Change management
	- Update management
	- Disaster recovery plan

# Security Policies
- Security policy objectives
	- Define overall security goal
	- Identify scope of what to secure
	- Define roles and responsibilities of people in the organization 
	- Identify specific communication processes
	- Discuss policy enforcement
- Should be created by a committee of invested stakeholders
- Plan for communicating policy should be created

# Update and Upgrade Management
- Update 
	- Small change to already installed software or firmware
- Upgrade
	- Replacement for older version of software
- Components of an update management policy
	- Patch update procedures
	- Software update procedures
	- OS upgrade procedures
	- Firmware change procedures
- Upgrades should not be applied to a database immediately after release
	- Is the update/upgrade really necessary?
	- What are the possible repercussions of the install?
- Create a test environment to test the upgrade
- Put a recovery and restore plan in place to reverse the upgrade if needed
	- Back up files in case reversal does not work
- Types of updates and upgrades
	- Patch
		- Small program used to fix or update software programs or firmware devices
		- Often created in response to newly discovered vulnerability
	- Software upgrade
	- OS upgrade
		- Most significant and risky upgrade
		- Involves radical change to both clients and servers

# Backup Management
- Backup
	- Intentional copy of data, files, and system configurations
	- Used to archive and store information
	- Used to replace files after network failure or attack
- Backup management plan
	- Process to ensure safety of network data
- Backup solutions
	- Many available today
	- Choose best fit for data and business goals
![[Pasted image 20230117114419.png]]
- Questions to answer when choosing backup strategy
	- What media should I use?
	- Where will backup be placed?
	- What should be backed up?
	- How often should information be saved?
	- What time of day should backup occur?
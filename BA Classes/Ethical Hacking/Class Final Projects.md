#EthicalHacking
# Grace - Exploiting Vulnerability in VSFTPD 2.3.4
- Normal Ubuntu on VirtualBox
- Followed setting up VSFTPD 2.3.4
- Searched for exploits related to this 
- Metasploit to run exploit
- Later removed all logged that proved she was connected to machine
- Why?
	- Wanted an Ubuntu vulnerability, this seemed easy
- What was challenging?
	- Harder than expected to find a vulnerable application
- Learned about Metasploit?
	- How to find exploits and how to use them

---
# Hope - Credential Harvesting / Phishing Attack
- Phishing email vulnerability to apache website
- Assumes their login to Facebook is the same as their login to a windows VM
- Writes logins to a local file, uses the login information in the user's machine
- Used OpenSSH server
- Learned?
	- How simple it is to acquire credentials 
- What tools could have been used?
	- Possibly (Yes, GoPhish)

---
# Ray - Drupalgeddon2 RCE
- Take victim IP address, namp scan, port 80, default Ubunutu page
- Directory bust it
- Navigate to Drupal (like wordpress)
- Use Wappalyzer (search for drupal 8 exploits)
- Metasploit search for drupal, use number 1
- Get merterpreter shell
- Add execute permissions to file
- Sudo command (ask ray for site)

---
# Ben - Ethical Hacking
- Used Oracle VM hypervisor, Metasploit
- Victim - LAMP stack, open 21, 22, http
- Started with only IP address, used CURL / NMAP, found ports / Apache / username
- Found default apache page
- Using OSINT name and username from namp and apache
- Found school, name, job
- Online stalked himself, found some online information
- Created a google account posing as a friend from history, asking for basic account on the server to practice
- Create reverse shell nsfvenom, used SCP back to home directory
- SSH file back, added execute permissions 
- Convinces host root admin to run malicious python file
- Now has root permission bc host ran it form root 

- Issues?
	- Relies on a trusting server admin
	- Requires root permissions
- Improve?
	- Obscuring or removing logs
	- Rely less on human interaction
	- Persistence 
- Dr. B is a fan of OSINT and social engineering

---
# Brandan - VSFTPD 2.3.4
- namp scanning - found VSFTPD
- set rhost to vulnerable machine, exploit, provided shell
- whoami, am root
- found flag, transffered to attack machine
- clearing logs from VSFTPD by deleting folder and recreated
- Resources?
	- Metasploitable-2 on kali linux
	- download metaspoitable, used nmap
- Improve?
	- Wipe log file of nmap scans

---
# Wade - Samba / Metasploitable 2
- Metasploitable 2 on UTM
- Samba exploit 3.0.20
- Exploit DB to find CVE-2007-2447 (using metacharacters to inject payload)
- namp ports on 139, 445 
- Metaspolit usermap_script
- found flag, only copied it over to a new terminal (need to do more)
- Improvements?
	- Remove traces in logs
	- Backdoor to return?
- Learn?
	- Samba payload differences

---
# Mitch - VSFTPD 2.3.4
- Kali attacker - UTM Hypervisior - VSFTPD 2.3.4 - Metasploitable 2 on UTM
- Exploit contains a backdoor on specific port
- Using metasploitable, search for VSFTPD 2.3.4 exploit, 'use 1'
- Set remote host, run exploit through backdoor
- Whoami (root), find flag, copied flag over to other terminal
- Improvements?
	- Trash logs, more surveillance by namping the vm

---
# Justin - WiFi Mouse 1.7.8.5
- Remote Code Execution (V2)
- Window 10 vulnerable - ServerMouse 
- How to identify w/ Wireshark, traffic on port 1978
- Used py file to set up listening port
- Uses netcat 
- Found the 'outdated' exploit is still functional w/ netcat on the current version of ServerMouse
- Improve?
	- Dynamic Command Execution
	- Interface
- 

---
# Carolina - Shellshock / Metasploitable 2
- Used Metasploit to find shellshock
- Exploits bash shells to run code
- Found another exploit on exploit db
- Find process id for netlink (run on root)
- Improvements?
	- More reconnaissance
- Complicated, felt legit to Dr. B (he likes unique attacks)
	- Noted her confusion, wishes she presented clearly and more articulated 

---
# Nate - Metasploitable 2
- Metasploitable 2 / kali Linux
- Find the php version of metasploitable, using the ip address
- Using the php version, using meterpreter 
- 'code = searchsploit apache 2.2.8 | grep php'
- cgi, meterpreter, reverse shell
- Found flag, copied into kali
- Improvement:
	- Whoami to find which user in reverse shell
	- Use surveillance 
	- Clear logs

---
# Adi - Metasploitable 2 w/ VSFTPD 2.3.4
- Metasploitable 2 from sourceforge
- the username ":)" triggers a backdoor
- find port of VSFTPD 2.3.4 (21/tcp) w/ nmap
- use exploit module for VSFTPD 2.3.4
- set rhost to target machine
- run the exploit
- triggered backdoor, remote shell open
- find flag (Adi wants to get married)

---
# Owen / Logan - VSFTPD 2.3.4 + Password Cracking
- Created closed network
- Victim machine - Metasploitable 2.6.24
- Hacker Machine - Kali 2023.4
- Survalence 
	- Nmap -O 
- Metasploitable portscan, found plenty of open ports
- VSFTPD 'smiley face' backdoor

- Hydra SSH Password Attack
- Used Kalitweaks to open
- Get password, from a password list
- Connect SSH with password
- Used scp to copy flag to own device 
# Notes
- Multifactor Authentication / End Point Response / Backups
	- Top three of what companies are interested in
- He personally values hands on experience more than certifications
- Seniors, about to leave Messiah Undergrad, should apply to the CA/CSA program
- Digital Forensics and Incident Response
	- Includes investigation into various types of computer systems
		- Unauthorized access, insider threats, data leak investigations, malware investigations, email compromises, ransomware, etc.
		- A company get hacked, now what?
			- What did the hacker do?
			- Are they still in the network?
			- Did they take something, how did they take it?
			- How did they get in?
				- Are we secure?
# Ransomware Investigation
- Preparation
- Detect
- Contain
- Eradicate
- Recovery
- Post Incident
## The Initial Call
- Usually 5 PM on a Friday
- Everything is done under Attorney Client Privilege 
- We work at direction of counsel, not IT or Security
	- This is to protect reports/work product from being public
- Common Scenarios:
	- "Well when we got to work this morning, there were a ton of help desk tickets saying users couldn't access anything"
	- "I see notes everywhere saying to download 'Tor' and go to a weird web address"
	- "We received an alert from our SOC about an ongoing attack and need to know if we have contained it."
- Common Questions:
	- Do we have to pay the ransom?
	- Are the "bad guys" still inside?
	- Can hack them back or nuke them?
## The Coordination of Teams
- Teams involved
	- Outside Counsel
	- DFIR Team (that's Zach)
	- Executive Team (CFO, CEO, etc)
	- Public Relation Firms
	- Information Technology Teams
	- Human Resources
	- Application Administrators
	- Endpoint Detection and Response Vendors
	- Ransom negotiators
## The Attack
- Attackers follow a common "kill chain"
	- Essentially a chain of events
		- External Recon
		- Compromised Machines
		- Internal Recon
			- Local Privilege Escalation
			- Compromise Creds
			- Admin Recon
			- Remote Code Execution
			- (Repeat)
		- Domain Admin Creds
		- Domain Dominance
			- Threat Actor's will achieve highest level's of privileges possible
			- Once gained
				- They will search the network for critical data to steal
				- They will package this data and exfiltrate it to hold it hostage
				- They will then deploy "ransomware malware" which encrypts user files
					- Double Extortion Technique
				- They will also sometimes conduct "Denial of Service Attacks" (i.e. make your internet very very slow)
					- Triple Extortion
## Common Attack Pattern
- Send Phishing Email
- Infect Systems with a backdoor that talks to a Command and Control (C2)
	- Multiple types of backdoor
- Collect Files
- Exfiltrate Files
- Encrypt the network
## Phishing Email
- Password protected attachment in the email
	- Password protected because it bypasses any scanner that looks more malware, but password protected documents get overlooked by these scanners
## Backdoor
- Huge encoded mess run through powershell
- Not Human Readable
	- Machine Level, position independent code
		- "Shell Code"
## Ransomware Execution
- Finally, once a persistence within the network is complete, ransomware is executed
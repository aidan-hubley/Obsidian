# Questions 13.1
1. A network switch is configured to perform the following validation checks on its ports:

-   All ARP requests and responses are intercepted.
-   Each intercepted request is verified to ensure that it has a valid IP-to-MAC address binding.
-   If the packet has a valid binding, the switch forwards the packet to the appropriate destination.
-   If the packet has an invalid binding, the switch drops the ARP packet.

Which security feature was enabled on the switch to accomplish this task?
	1. Dynamic ARP inspection
2. A network switch detects a DHCP frame on the LAN that appears to have come from a DHCP server that is not located on the local network. In fact, it appears to have originated from outside the organization's firewall. As a result, the switch drops the DHCP message from that server. Which security feature was enabled on the switch to accomplish this?
	1. DHCP snooping
3. You are in the process of implementing a Network Access Protection (NAP) infrastructure to increase your network's security. You are currently configuring the remediation network that non-compliant clients will connect to in order to become compliant. The remediation network needs to be isolated from the secure network. Which technology should you implement to accomplish this task?
	1. Network segmentation
4. Match the Network Access Protection (NAP) component on the left with its description on the right.
	1. Generates a Statement of Health (SoH) that reports the client configuration for health requirements.
		1. NAP client
	2. Runs the System Health Validator (SHV) program.
		1. NAP server
	3. Is clients' connection point to the network.
		1. Enforcement server (ES)
	4. Contains resources accessible to non-compliant computers on a limited-access network.
		1. Remediation server
5. You manage a network that uses switches. In the lobby of your building are three RJ45 ports connected to a switch. You want to make sure that visitors cannot plug their computers in to the free network jacks and connect to the network, but you want employees who plug in to those same jacks to be able to connect to the network. Which feature should you configure?
	1. Port authentication
6. Which type of security uses MAC addresses to identity devices that are allowed or denied a connection to a switch?
	1. Port security
7. Match the port security MAC address type on the left with its description on the right.
	1. A MAC address that is manually identified as an allowed address.
		1. SecureConfigured
	2. A MAC address that has been learned and allowed by the switch.
		1. SecureDynamic
	3. A MAC address that is manually configured or dynamically learned and is saved in the config file.
		1. SecureSticky
8. Which of the following is a best practice for router security?
	1. Disable unused protocols, services, and ports.
9. You have a company network with a single switch. All devices connect to the network through the switch. You want to control which devices will be able to connect to your network. For devices that do not have the latest operating system patches, you want to prevent access except to a special server that holds the patches the computers need to download. Which of the following components should be part of your solution? (Select two.)
	1. Remediation servers
	2. 802.1x authentication
10. Which of the following are best practices for hardening a server? (Select three.)
	1. Disable or uninstall unnecessary software.
	2. Apply the latest patches and service packs.
	3. Ensure that a host-based firewall is running.

# Questions 13.2
1. Which of the following is an example of two-factor authentication?
	1. A token device and a PIN
2. Match the authentication factor types on the left with the appropriate authentication factor on the right. (You can use each authentication factor type more than once.)
	1. PIN
		1. Something you know
	2. Smart card
		1. Something you have
	3. Password
		1. Something you know
	4. Retina scan
		1. Something you are
	5. Fingerprint scan
		1. Something you are
	6. Hardware token
		1. Something you have
	7. Voice recognition
		1. Something you are
	8. Wi-Fi triangulation
		1. Somewhere you are
	9. Typing behaviors
		1. Something you do
3. Which of the following is the strongest form of multi-factor authentication?
	1. A password, a biometric scan, and a token device
4. Which of the following actions typically involve the use of 802.1x authentication? (Select two.)
	1. Controlling access through a switch.
	2. Controlling access through a wireless access point.
5. You are a contractor that has agreed to implement a new remote access solution based on a Windows Server 2016 system for a client. The customer wants to purchase and install a smart card system to provide a high level of security to the implementation. Which of the following authentication protocols are you MOST likely to recommend to the client?
	1. EAP
6. Which EAP implementation is MOST secure?
	1. EAP-TLS
7. With Kerberos authentication, which of the following terms describes the token that verifies the user's identity to the target system?
	1. Ticket
8. Which of the following is a feature of MS-CHAPv2 that is not included in CHAP?
	1. Mutual authentication
9. Which of the following is a mechanism for granting and validating certificates?
	1. PKI
10. Which of the following is a platform-independent authentication system that maintains a database of user accounts and passwords to centralize the maintenance of those accounts?
	1. RADIUS

# Questions 13.3
1. You want to make sure that all users have passwords over eight characters in length and that passwords must be changed every 30 days. What should you do?
	1. Configure account policies in Group Policy.
2. You manage a single domain named widgets.com. Organizational units (OUs) have been created for each company department. User and computer accounts have been moved into their corresponding OUs. You define a password and account lockout policy for the domain. However, members of the Directors OU want to enforce longer passwords than are required for the rest of the users. You need to make the change as easily as possible. Which of the following actions should you take?
	1. Implement a granular password policy for the users in the Directors OU.
3. You manage a single domain named widgets.com. Organizational units (OUs) have been created for each company department. User and computer accounts have been moved into their corresponding OUs. Members of the Directors OU want to enforce longer passwords than are required for the rest of the users. You define a new granular password policy with the required settings. All users in the Directors OU are currently members of the DirectorsGG group, which is a global security group in that OU. You apply the new password policy to that group. Matt Barnes is the chief financial officer, and he would like his account to have even stricter password policies than are required for other members in the Directors OU. What should you do?
	1. Create a granular password policy for Matt. Apply the new policy directly to Matt's user account.
4. You are configuring the Local Security Policy on a Windows system. You want to require users to create passwords that are at least 10 characters in length. You also want to prevent login after three unsuccessful login attempts. Which policies should you configure? (Select two.)
	1. Account lockout threshold
	2. Minimum password length
5. For users on your network, you want to automatically lock user accounts if four incorrect passwords are used within 10 minutes. What should you do?
	1. Configure account lockout policies in Group Policy
6. You have just configured the password policy and set the minimum password age to 10. What is the effect of this configuration?
	1. Users cannot change the password for 10 days.
7. Upon running a security audit in your organization, you discover that several sales employees are using the same domain user account to log in and update the company's customer database. Which action should you take? (Select two. Each response is part of a complete solution.)
	1. Train sales employees to use their own user accounts to update the customer database.
	2. Delete the account that the sales employees are currently using.
8. You have performed an audit and found an active account for an employee with the username joer. This user no longer works for the company. Which command can you use to disable this account?
	1. **usermod -L joer**
9. An employee named Bob Smith, whose username is bsmith, has left the company. You have been instructed to delete his user account and home directory. Which of the following commands would produce the desired outcome? (Select two.)
	1. **userdel -r bsmith**
	2. **userdel bsmith;rm -rf /home/bsmith**
10. Which of the following utilities could you use to lock a user account? (Select two.)
	1. usermod
	2. passwd

# Questions 13.4
1. You have a Windows 10 system. You have used the Settings app to access Windows Update. From this location, how long can you pause updates?
	1. 7 days
2. Which of the following are true about Windows Update for Business? (Select three.)
	1. Windows Update for Business can be configured with Group Policy, Mobile Device Management, or Systems Center Configuration Manager.
	2. Windows Update for Business provides the latest features for your Windows 10 devices, including security upgrades.
	3. Windows Update for Business works with all versions of Windows 10 except Windows 10 Home.
3. Windows Update for Business (WUfB) lets you keep your devices current with the latest security upgrades and features. Which operating system releases does WUfB support
	1. Windows 10
4. Your Windows system is a member of a domain. Windows Update settings are being controlled through Group Policy. How can you determine whether a specific security update from Windows Update is installed on the computer?
	1. Go to **Programs and Features** in Control Panel.
5. While deploying Windows updates, when would you use the critical update ring?
	1. When deploying updates to important systems (only after the update has been vetted).
6. When deploying Windows updates, when would you use the preview update ring?
	1. When deploying updates to users that want to stay on top of changes.
7. What does the Windows Update Delivery Optimization function do?
	1. Delivery Optimization provides you with Windows and Store app updates and other Microsoft products.
8. What is WindowsUpdate.log?
	1. A log file you can create and save in order to locate errors or problems.
9. Dan wants to implement reconnaissance countermeasures to help protect his DNS service. Which of the following actions should he take?
	1. Install patches against known vulnerabilities and clean up out-of-date zones, files, users, and groups.
10. Which of the following tools can you use to troubleshoot and validate Windows updates? (Select three.)
	1. Windows Update Troubleshooter
	2. PowerShell
	3. Windows Server Update Service (WSUS)
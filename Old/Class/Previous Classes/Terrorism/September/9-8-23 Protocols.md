# Stacks - Solve One Problem At a Time
-- Each layer solved one problem at a time --
- Application Layer - Communicate
	- SNMP, HTTP
- Transport Layer - Get a stream of data anywhere
	- TCP, UCP, ICMP
	- Problem: What if something goes wrong?
		- Solved by Application layer
- Network Layer - Gat a message over multiple links
	- IPv6 - IPv4
	- Problem: What if I don't know where to send it?
		- Gets solved by Transport Layer
- Link Layer - Get a message from A to B
	- Ethernet - WiFi
	- Problem: What if a packet gets lost?
		- Gets solved by Network/Transport Layer
- Physical layer - Gat a bit from A to B 
	- PSK - simple connection
	- Problem: What if a bit gets flipped??
		- Gets solved by Link Layer

-- NMAP can scan up to Transport Layer --

# [Telnet]
- Once the most common
- Rarely used today
- Used port 23
- Unencrypted
- Superseded by SSL

# [FTP] ([File Transport Protocol])
- Port 21, 22
- Telnet's More Popular Cousin
- Moves Files
- Port 21 and 22
- Unencrypted
- Still Used Today
- [SCP] ([Secure Copy Protocol])

# [HTTP] ([HyperText Transfer Protocol])
- Most popular
- Get / Post
	- Runs in plain text
- Does other functions faster
- Server programs
	- [Apache]
	- [IIS] ([Internet Information Service])
	- [NGINX]
- Defaults

# [SMTP] / [POP] / [IMAP]
- [Simple Mail Transfer Protocol]
	- Sending Mail
	- Used in between mail servers
- [Post Office Protocol]
	- Used to receive mail
- [Internet Message Access Protocol]
- POP / IMAP
	- Most use IMAP over POP
		- It can retrieve messages more than once
- All of these are plain text
# Tactic
- What hosts?
- What services?
- What software?
- What data?
- Can I talk to it?

# Most Basic
- Starting Assumption
	- Ping (is it on)
	- Three-way handshake (is it listening)
		- Must have at least an open port
			- An entry point 
		- Port Assumptions
			- Systems might be set up intentionally differently
	- Connect (open ports allow connection)

# Cat and Mouse
- Detecting Scanning
	- Being Stealthy
	- NMAP has tools to avoid getting caught scanning ports
- Firewalls
- SIEMs

# [UDP] vs. [TCP]
- UDP basically have nothing
	- Source Port
	- Destination Port
	- UDP length
	- Checksum
- TCP has everything
	- 3 way handshake
	- Series of acknowledge numbers
	- Window size
	- Urgent pointer
	- Options
	- More

- Use UDP for streaming, audio call, broadcast message
	- Best effort, used when cannot stop and wait to retransmit a package
	- Sometimes, certain messages only need 1 packet
		- DNS messages

-- [Ping] is specific an [ICMP] ([Internet Control Message Protocol])

# [ARP] ([Address Resolution Protocol]) Scans
- Publicly asks for IP address, simply cycle through IP addresses
	- Usually provided MAC address
![[Pasted image 20230904142135.png]]
- Works for LOCAL Scans
- Link with Network Structure
- Broadcast Domain
- Detection

# [DHCP] ([Dynamic Host Configuration Protocol])
![[Pasted image 20230904142807.png]]
- Private IPs (Non-routable):
	- 192.168.*
	- 10.*

- Widely used
- ....

# Reverse [DNS] ([Domain Name Server]) Lookups
![[Pasted image 20230904144310.png]]
- DNS is an essential Piece of Information
- On Mac:
	```
	SCUTIL -DNS
	```
- Reverse Lookup on Mac:
	```
	dig -x 151.101.67.5
	```
- [NMAP] will be default do a reverse DNS lookup on all targets it finds
- nslookup
![[Pasted image 20230904144956.png]]
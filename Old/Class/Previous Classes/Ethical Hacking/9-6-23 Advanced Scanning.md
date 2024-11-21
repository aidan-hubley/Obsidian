# Packet Fragmentation
-- One of the ways to do advanced scanning --
![[Pasted image 20230906141031.png]]
- How is this helpful?
	- Sending smaller packets to avoid detection

# Spoofed IP's / MAC
-- Faking the original sending address --
- Simple as rewriting the address you send out
- Note: will need to monitor traffic to monitor the traffic sent from recipient 
- Helps because you won't be recognized as the attacker, aka won't be blocked from network

# Zombie Scan
-- Within network header the Identification number is manipulatable, it sits next to the fragment offset --
- Every time a new packet is generated the id num is incremented, will eventually roll over
- ID num is used to reconstruct a fragmented packet
- IP ID Field
- Why Idle
- Closed Port Behavior (Nothing)
- Open Port Behavior

# Traceroute
-- Only alive until Time to Live (header field) expires --
- Packets can be killed on route, but returns the ip address of where it was killed
- Can then create the packet again with a longer Time to Live 

# Service Version
-- Example: Apache/2.2.22 (Debian) Server at 192.168.1.7 Port 80 --
- 3-Way Handshake
- What then?
- Helpful Developers
- Welcome Banner (3.000)
- Get Requests
- UDP Ports
- RCP Grinding
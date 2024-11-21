# IPv6 - Dan Baker
## Review of IPv4
### Bootstrapping
- Client gets address, subnet mask, default gateway, DNS server, etc. FROM DHCP
	- address 192.168.0.50/24
	- gateway 192.168.0.1
	- DNS 8.8.8.8
- How does the client communicate with another client/
	- Address Resolution Protocol to gateway
	- send ip packet to default gateway
- How do you ping 8.8.8.8?
	- Network Address Translation!
- Why do we need NAT?
	- Running out of IPv4 addresses
		- 32 bits
		- 2^32 = 4.3 billion
	- World population of 7.8 billion
	- Multiple devices per person
	- Not enough IP addresses!
- No NAT is used at Messiah
	- Messiah is IPv4 rich
	- 65k addresses
	- Originally assigned to HP in the early days, reassigned to Messiah in the last 90s
	- Every host is assigned a globally unique IPv4 address
		- no RFC1918
		- no NAT
### IPv4 as Commodity
- bc there are no more new IPv4 blocks, there is a market to trade IP allocations
- Get large IPv4 allocation today?
	- $50/address. for /16 that's $3.3 million

### Why not NAT?
- NAT allows you to share one public (expensive) IP among devices with private RFC1918 IPs - sounds great right?
	- NAT breaks end-to-end communication
		- Bad for gaming, voice, 2-way video
	- NAT does not scale very well
		- resource-intensive at large scale
		- NAT device must store a tuple for every connection through the NAT
			- millions of connections
			- thousands of new connections every second

# Solution IPv6
- 128-bit address, 340 billion billion billion billion permutations
## Benefits
- extremely vast that will never* be exhausted
- can get large IPv6 allocation for free
- native end-to-end connectivity, highly beneficial for real-time audio, video, and gaming
- IPv6 routing is simpler and marginally faster than IPv4
- Avoiding NAT saves resources and time
- Simpler client bootstrapping process (no DHCP needed!)
## Why do we still have IPv4?
- IPv6 is not backward-compatible
	- Have to run "dual stack" - both IPv4 and IPv6 on the network
	- More configuration and maintenance than running one protocol
- Network as a cost center rather than a business driver
- Some people are change-averse, or near retirement, or just don't want to do it!
- Legacy business
## How do we move Forward?
- IPv4 will still be with us for a long time
- We should enable IPv6 everywhere we can
### Two approaches to IPv6
#### IPv6 Only
- Facebook/Instagram
	- IPv6-Only datacenters since 2017
	- IPv4 users reach Facebook through a transition mechanism (dual-stacked software load balancer)
- T-Mobile
	- IPv6 LTE network
- Microsoft
	- been moving towards IPv6-only internal networks since 2018 with NAT64/DNS64
- Apple
	- requires that all iOS apps must work in IPv6-only networks
#### Dual-stack
- Comcast
	- leader in IPv6
	- entire cable Internet network is dual-stacked
- Content providers are dual-stacked
	- Akamai
	- Cloudflare
	- Google
	- YouTube
	- Many others
- Enterprise network
	- Support legacy systems, but also enable users to reach IPv6 cloud/Internet resources
### Who cares?
- Providers are marking a big push towards IPv6 now
- IPv6 is going to play a role in your future

# IPv6 addresses
- 128 bits
- Written in hexadecimal groups of 16 bits separated by colons
## Subnetting
- IPv4 - many subnet sizes (/24, /20, /27, etc.)
- IPv6 - one subnet size (/64)
- Routers summarized on nibble boundaries
	- /64, /60, /56, /52, /48, /44, /40, /36, /32, etc.
- Basic subnetting rules
	- Site or building - /48
	- Subnet - /64
## IPv6 vs. IPv4
- How many IPv4 addresses does a host get?
	- 1 address
- How many IPv6 addresses does a host get?
	- at least 1 address
	- Link-local
	- DHCPv6
	- SLAAC - stateless addresses autoconfiguration
- No ARP - Neighbor Discovery Protocol (NDP)
- No NAT!
## Special cases of IPv6 addressing
- ULA - similar to RFC1918
	- Private address space
	- Not typically recommended, but has its use cases
- NPTv6 - network prefix translation
	- Not NAT66!
	- Totally stateless
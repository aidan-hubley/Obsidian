# Table of Contents
- Router Components
- Router Boot
- Router Modes
- Programming the Router
- The Show Command

# Router Components
- Internal Configuration
	- RAM
	- NVRAM
	- Flash
	- ROM
- RAM Specifics
	- As the router is booted, the following is loaded into RAM's Working Storage
		- Command Executive
		- Internetwork Operating System (IOS)
		- Programs
		- Active Config File
		- Tables
			- ARP
			- RIP
		- Buffers
			- Packets

# Router Modes
- User EXEC Mode
	- Limited examination of router.
	- Remote access.
		- Router>
- Privileged EXEC Mode
	- Detailed examination of router
	- Debugging and testing
	- File manipulation
	- Remote Access
		- Router#
- SETUP Mode
	- Prompted dialog used to establish an initial configuration
- Global Configuration Mode
	- Simple configuration commands
		- Router (config)#
- 
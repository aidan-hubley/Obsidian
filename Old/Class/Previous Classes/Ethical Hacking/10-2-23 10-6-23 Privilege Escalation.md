-- Getting the Power --
# Why?
- Post Exploit
- Social Engineering
- Persistence
- Cover Tracks
- Utilize Access

# Getting Practical 
- Mterpreter
- NetCat
- Socat
- MSFVenom

# CPU Protection Rings
- Dates to the 1970s
- Intel introduced in the 1980s with the 80286 CPU
- Often uses only 2
	- Kernel Mode
	- User Mode
- ARM Version 8+
	- Application Mode
	- OS Mode
	- Hypervisor Mode
	- Secure Monitor / Firmware 

## What do these Rings DO?
- Access to Memory
- Access to Instructions
- Access to Hardware
- Expensive (Typically 1000-1500 cycles to switch)

## Virtual Memory
- Mis-Behaving Applications
- Application given own address space
- Think they are alone
- Cannot interfere with each other
- Only the OS (Privilege Ring) sees the real memory
- Memory is Divided into pages
- Application can request any memory it wants

# The View from Inside the Matrix
- Linux
- Address Space Layout Randomization
	- Used to scramble address space 

## How does this make life better?
- Misbehaving application
	- Example: application leaking memory? It's fine because the memory stays within it's given space
	- Stability improvement
- Hardware Independence
- Inter-process communication
- Protecting the Operating System
- Crashing Application
- Operating System Size

# Sandboxes
- Java
- Safari

# Virtual Machine and Containers
- Docker
- Hypervisor

# IOS Security
- When loading an app, a set of keys is created. They are used to encrypt all data that an application stores

# Secure Guard Extensions - Intel
- Specific space in memory created by application for highly sensitive data that can only be decrypted by the . . .

# SEL4 Microkernel
- Microkernel
- Non-Interference
- Formally Proven

-- --

# Assumptions
##### Once you are on
- Whoami - Display the current user's username
- Hostname - Show the system's name or network node name
- PS - What processes are running
- ID - what privileges you have based on groups you're apart of
- Passwd - Change user password
- Sudo -l - Lise user's sudo privileges
- Ifconfig - Networking data / settings
- Netstat- Network statistics / connections established
- Find - search for something

## Script Execution
- Who can write?
- Who executes?
- Who can Cron? - schedule tasks
- Interaction with the path variable
- 
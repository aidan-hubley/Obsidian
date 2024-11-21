#EthicalHacking
# What is it?
- Framework for exploitation
	- Scriptkiddie's paradise
	- Useful for pen testing
- Consistent way to use vulnerabilities
- Fills in the process
- Terminal for Hacking

-- "Nobody Makes their First Jump" --

## Modules 
- What is vulnerable to the Module?
- How it works / Side effects?
- Has it been tested?
- What are necessary pre-conditions?

### Module Stages
![[Pasted image 20230927141054.png]]
- Some modules are single stages
- Most require multiple stages
- Can be combined like lego bricks
- Tailoring to specific target
- Obfuscation

## What is encoding?
- Remember our shell code form the buffer overflow?
- We encode it as s string
- Ended in Zero - Had to avoid
- Other limitations
- Signatures evasions

## Metasploit Database
- Not Required
- Keep track of multiple systems
- Hosts
- Credentials
- Services
- Routes
- "Loot"

## Reverse Shell
- Compromised machine reaches out to you for instructions
- You must have an open port
- Not always required
- Avoids firewalls
- Avoids NAT firewalls

## Meterpreter 
- Payload Module
- Implant on a compromised Machine
- Live in Memory
- Hosted on compromised process but doesn't create its own
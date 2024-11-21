# [Buffer Overflow]
-- Flawed Design --
- Ultimate Goal: is to get another machine to run my code
- Class of Exploits
- First published in 1996
- Remote Exploit

# Smashing the Stack
### What is a Stack?
- Data Structure
- LIFO - Last In First Out
- Access from Top Only
- Push / Pop

# Implementation
- Region of Memory
- Register

## Function Call
~~~
void function (short a, short b, short c) {
	int d;
	d = a + b + c;
	printf("s\n", d);
}

void main () {
	function(1, 2, 3);
}
~~~

# Consider the Following Code
~~~
void function (char *str) {
	char buffer[4];
	strcpy(buffer, str);
}

void main() {
	char large_str[256];
	large_str = "BlahBlahBlah"
	function(large_str);
	return();
}
~~~

# Code we want to run
~~~
#include stdio.h

void main() {
	char *name[2];
	name[0] = "/bin/sh";
	name[1] = NULL;
	execve(name[0], name, NULL);
}
~~~

# Smashing the Stack
- String Program that executes a shell
- Know how big the buffer is
	- By intentionally crashing with different lengths
- Need a killer string

-- NOP slide - allows for a larger range to guess where the buffer is 


# Type Safety
- Attempt to design language to prevent data types from being manipulated to become other datatypes 
- All data is stored as unsigned numbers
- We encoded data strings, signed numbers, floating point numbers, Code, Arrays, Etc.
- We want to guarantee that the type is preserved after each step
- Example we treat a string as if it was code
- Memory Safety is the part that will ensure that a buffer overflow cannot occur
- Good to aim for, hard to prove
- Examples:
	- C#
	- Java
	- Standard ML
	- Pascal
	- LISP

# Bounds Checking
- Make sure that arrays always have a Limit
- Check to make sure variables are stay within the bounds
- Examples:
	- Ada
	- C#
	- Paskell
	- java
	- Javascript
	- Python
	- Ruby
	- Rust
	- Visual Basic

## Address Space Layout Randomization (ASLR)
- Each time the system boots, the libraries and code is placed in a different location
- All major operations system have adopted this
- Several attacks aim to cause the OS to reveal the address space for a good guess

# Data-Execution Prevention
- Designate Regions of Memory as Non-Executable
- AMD NX (No Execute Bit)
- Intel XD (Execute Disable)
- ARM XN (Execute Never)

# Anti ASLR
- 1st Gen ASLR randomizes the most significant bytes of memory, but the relative memory stays the same
	- Guess
	- Only writing the least significant bytes
- Accidental disclosure of the memory location
	- Probe locations
	- Speculative Execution
- Get the target to load an anti-ASLR module
	- Old Libraries
	- Libraries that cannot support ASLR

# Return to LIBC
- 1st Widespread Exploit to Bypass Data-Execution Prevention
- LIBC is a library that contains nearly all of the most common functions used in C programming
- Overwrite the return address to point to LIBC
- System("/Bin/Bash")
- Pass a pointer to the argument ("/Bin/Bash")
- Add and eixt call for general termination
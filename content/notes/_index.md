[[Workflow]]
[[DLL Reference]]

### Basic Static Techniques
[[Hashing]]
[[Strings]]
[[Packers]] 
	[[Packing Files]]
	[[Detecting Packers]]
[[PE File Format]]
[[Linked Libraries and Functions]]

### Basic Dynamic Analysis 
[[Sandboxes]]
[[Running Malware]]
[[Viewing Processes]]
[[Regshot]]
[[Faking a Network]]
	apatedns 
	netcat  
Wireshark
inetsim 
in practice 

## Advanced Static Analysis 
### x86 Disassembly
Abstraction
Reveng 
Architecture 
	Main Memory 
	Instructions 
	Opcodes and Endianness
	Operands
	Registers
	Simple Instructions
	The Stack 
	Conditionals 
	Branching
	Rep Instructions
	C Main Method and Offsets 
	IA Manual 
### IDA Pro 
Interface 
X-refs 
Analyzing functions 
Graphing options 
Enhancing Disassembly 
	Renaming Locations 
	Comments 
	Formatting Operands 
	Using Named Constants 
	Redefining Code and Data 
Plugins 

### Recognizing C Code Constructs in Assembly 
Global vs Local 
Disassembling Arithmetic Operations 
If Statements 
Loops
Function Call Conventions 
Switch Statements 
Disassembling Arrays 
Identifying Structs 
Linked List Traversal 

### Analyzing Malicious Windows Programs 
WinAPI
	Types and hungarian notation 
	handles 
	file system functions 
	special files 
Registry 
	Root Keys 
	regedit 
	Autorun Programs 
	Common Registry Functions 
	Analyzing Registry Code 
	Scripting with .reg files 
Networking APIs 
	Berkeley Compatible Sockets 
	Server and Client Sides of Networking 
	WinINet API 
Following Running Malware 
	DLLs 
	Processes 
	Threads 
	Interprocess Coordination with Mutexes 
	Services 
	Component Object Model 
	When Things Go Wrong 
Native API 

## Advanced Dynamic Analysis 
### Debugging 
Source-Level vs Assembly-Level Debuggers 
Kernel vs. User-Mode Debugging 
Using a Debugger 
	Single-Stepping
	Stepping-Over vs. Stepping-Into 
	Pausing with Breakpoints
Exceptions 
	First and Second-Chance Exceptions 
	Common Exceptions 
Modifying Execution with a Debugger 
Modifying Program Execution in Practice 

### Ollydbg
Interface 
Memory Map 
	Rebasing 
Viewing Threads and Stacks 
Breakpoints 
	Software
	Conditional 
	Hardware
	Memory 
Loading DLLs 
Tracing 
	Standard Back Trace 
	Call Stack 
	Run Trace 
	Tracing Poison Ivy 
Exception Handling
Patching
Analyzing ShellCode
Assistance Features
Plugins
Scripting

### Kernel Debugging with Windbg
Drivers and Kernel Code 
Using WinDbg 
	Reading from Memory 
	Using arithmetic operators 
	Setting Breakpoints 
	Listing Modules 
Microsoft Symbols
	Searching for Symbols 
	Viewing struct information 
	Configuring Windows Symbols
Kernel Debugging in Practice 
	Looking at User Code 
	Looking at Kernel Mode 
	Finding Driver Objects 
Rootkits
Loading Drivers 


## Malware Functionality 


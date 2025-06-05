**Packers** are a tool to help obfuscate a program by compression.
**How it works:** When a packed program is run, a small wrapper runs first to decompress the file and then run the unpacked file. 
**How to detect:** [[Detecting Packers]]
**Packing Files:** [[Packing Files]]

> [!TIP]
> Packed and obfuscated code usually includes LoadLibrary and GetProcAddress 

> [!caution] 
> PEiD plugins may run the executable without warning!


---
#### Original vs. Packed
![[image-30.png|388x197]]

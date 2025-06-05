**Packers** are a tool to help obfuscate a program by compression.
**How it works:** When a packed program is run, a small wrapper runs first to decompress the file and then run the unpacked file. 
**How to detect:** [Detecting Packers](Detecting Packers.md)
**Packing Files:** [Packing Files](Packing Files.md)

> [!TIP]
> Packed and obfuscated code usually includes LoadLibrary and GetProcAddress 

> [!caution] 
> PEiD plugins may run the executable without warning!


---
#### Original vs. Packed
![image-30.png|388x197](image-30.png|388x197.md)

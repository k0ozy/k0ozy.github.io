>[!info] 
>Functions can be imported by ordinal instead of name

**[Static Linking](Static Linking.md):** All code from libraries is copied into the executable
**[Runtime Linking](Runtime Linking.md):** Commonly used in malware especially when it is packed or obfuscated. Executables only connect to libraries when that function is needed.
**[Dynamic Linking](Dynamic Linking.md):** Host OS searches for the necessary libraries when the program is loaded. When called, the function executes within the library. 

**Imported Functions:** Windows functions that are documented within MSDN.

**Exported Functions:** Most common in DLLs since EXEs are not designed to provide functionality to other EXEs. Names of exported functions can have any name or omit names entirely.

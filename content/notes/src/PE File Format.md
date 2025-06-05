**Portable Executable File Format** is the file format used by Windows executables, object code, and DLLs
**Contains:** A header with information about the code, type of application, required functions, space requirements, etc.
**Tools:** PEview, Resource Hacker, PE Explorer
#### Headers
- Contains metadata about the file itself 
- **IMAGE_DOS_HEADER** - Historical
- **MS-DOS Stub** - Historical
- **IMAGE_NT_HEADERS**
	- **Signature**
	- **IMAGE_FILE_HEADER** - Contains basic information about the file. Time Date Stamp = compilation date
	- **IMAGE_OPTIONAL_HEADER** - 
- **IMAGE_SECTION_HEADER**  
	- Virtual Size - How much space is allocated for a section during the loading process
	- Size of Raw Data - How big the section is on disk
	> Should usually be equal. If Virtual is larger than Raw, indicative of packed code (especially in .text)


#### Sections
- **.text** - Contains the instructions the CPU executes. Only section that can execute, or contain code.
- **.rdata** - Contains import and export information. Can store read-only data used by the program
- **.data** - Contains global data. Local data is not stored here or anywhere else in the PE file
- **.idata** - Sometimes present. Stores import function information. If not present, stored in .rdata
- **.edata** - Sometimes present. Stores export function information. If not present, stored in .rdata
- **.pdata** - Only in 64 bit executables. Stores exception-handling information
- **.rsrc** - Contains resources that are not part of executable. Icons, menus, images, strings, etc.
- **.reloc** - Contains information for relocation of library files 

![image-70.png](image-70.png.md)
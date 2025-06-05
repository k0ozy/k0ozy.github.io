### Virtual Machine Setup
#### 2 Windows VM 
1- Clean for Static Analysis 
2- Dirty for Debugging 
##### Static Analysis VM
Network Enabled 
DO NOT run malware 
Contains notes, work etc 
Use snapshots 
Static Analysis Tools 
	IDA 
	HxD Hex Editor 
	Python
	PE Bear 
	Visual Studio
	Resource Hacker 
	DiE - Detect it Easy 
	PE Studio 
	DNSpyEx - NET 
	Jupyterlab for notes 
##### Dynamic Analysis VM 
Shut off Networking 
Disable Share Drives
Dynamic Analysis Tools 
	x64dbg 
	same tools as static analysis vm 
	Change background color to something ugly 
	System Informer 
Office 2019 - https://www.reddit.com/r/microsoftoffice/comments/17r7jls/how_to_download_microsoft_office_2019_or_2021/
	https://github.com/massgravel/Microsoft-Activation-Scripts
	

### Workflow 
Run sample in sandbox before manual analysis 
	CAPEv2 
	AnyRun
	Triage 
	Unpac.me 
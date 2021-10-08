# Autopilot HAADJ
Deploys script which runs as scheduled task to retry the HAADJ join process every 60 seconds. This makes in possible to deploy Autopilot HAADJ where the VPN connection is established during the initial Windows 10 login.

## Intune Package Details

### Install Command: 
powershell.exe -executionpolicy bypass -windowstyle hidden -nologo -file .\Deploy-HAADJOOBE.ps1

### Uninstall Command
cmd /c

### Install Behavior: 
SYSTEM

### Detection Method: 
File
File Location: C:\ProgramData\HAADJOOBE\HAADJOOBEDeployment.tag

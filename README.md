# tool-upload-oscp
tools to upload to target machines. Loud. Noisy. For the OSCP

## win.zip:
├── domain_user
│   ├── adalanche-collector-windows-386-v2024.1.11.exe
│   ├── adalanche-windows-x64-v2024.1.11.exe
│   ├── Carbon-2.15.1
│   │   ├── Carbon
│   │   │   ├── bin
│   │   │   │   ├── args.exe
│   │   │   │   ├── coreclr
│   │   │   │   │   ├── Carbon.dll
│   │   │   │   │   ├── Carbon.Iis.dll
│   │   │   │   │   ├── Carbon.Xdt.dll
│   │   │   │   │   ├── Microsoft.Web.Administration.dll
│   │   │   │   │   └── Microsoft.Web.XmlTransform.dll
│   │   │   │   ├── fullclr
│   │   │   │   │   ├── Carbon.dll
│   │   │   │   │   ├── Carbon.Iis.dll
│   │   │   │   │   ├── Carbon.Xdt.dll
│   │   │   │   │   └── Microsoft.Web.XmlTransform.dll
│   │   │   │   ├── Ionic.Zip.dll
│   │   │   │   ├── Protect-String.ps1
│   │   │   │   ├── Remove-DotNetAppSetting.ps1
│   │   │   │   ├── Remove-EnvironmentVariable.ps1
│   │   │   │   ├── Set-DotNetAppSetting.ps1
│   │   │   │   ├── Set-DotNetConnectionString.ps1
│   │   │   │   ├── Set-EnvironmentVariable.ps1
│   │   │   │   └── Use-CarbonPrefix.ps1
│   │   │   ├── Carbon.format.ps1xml
│   │   │   ├── Carbon.psd1
│   │   │   ├── Carbon.psm1
│   │   │   ├── CHANGELOG.md
│   │   │   ├── DscResources
│   │   │   │   ├── Carbon_EnvironmentVariable
│   │   │   │   │   ├── Carbon_EnvironmentVariable.psm1
│   │   │   │   │   └── Carbon_EnvironmentVariable.schema.mof
│   │   │   │   ├── Carbon_FirewallRule
│   │   │   │   │   ├── Carbon_FirewallRule.psm1
│   │   │   │   │   └── Carbon_FirewallRule.schema.mof
│   │   │   │   ├── Carbon_Group
│   │   │   │   │   ├── Carbon_Group.psm1
│   │   │   │   │   └── Carbon_Group.schema.mof
│   │   │   │   ├── Carbon_IniFile
│   │   │   │   │   ├── Carbon_IniFile.psm1
│   │   │   │   │   └── Carbon_IniFile.schema.mof
│   │   │   │   ├── Carbon_Permission
│   │   │   │   │   ├── Carbon_Permission.psm1
│   │   │   │   │   └── Carbon_Permission.schema.mof
│   │   │   │   ├── Carbon_Privilege
│   │   │   │   │   ├── Carbon_Privilege.psm1
│   │   │   │   │   └── Carbon_Privilege.schema.mof
│   │   │   │   ├── Carbon_ScheduledTask
│   │   │   │   │   ├── Carbon_ScheduledTask.psm1
│   │   │   │   │   └── Carbon_ScheduledTask.schema.mof
│   │   │   │   ├── Carbon_Service
│   │   │   │   │   ├── Carbon_Service.psm1
│   │   │   │   │   └── Carbon_Service.schema.mof
│   │   │   │   └── Initialize-CarbonDscResource.ps1
│   │   │   ├── en-US
│   │   │   │   ├── about_Carbon_2.0.help.txt
│   │   │   │   ├── about_Carbon_Contributing.help.txt
│   │   │   │   ├── about_Carbon_Extended_Type_Data.help.txt
│   │   │   │   ├── about_Carbon.help.txt
│   │   │   │   ├── about_Carbon_Installation.help.txt
│   │   │   │   └── about_Carbon_Support.help.txt
│   │   │   ├── Formats
│   │   │   │   ├── Carbon.Security.HttpUrlAcl.format.ps1xml
│   │   │   │   └── Schedule.Service.RegisteredTask.format.ps1xml
│   │   │   ├── Functions
│   │   │   │   ├── Initialize-Lcm.ps1
│   │   │   │   └── Use-CallerPreference.ps1
│   │   │   ├── Import-Carbon.ps1
│   │   │   ├── LICENSE.txt
│   │   │   ├── NOTICE.txt
│   │   │   └── README.md
│   │   └── examples
│   │       ├── Initialize-BuildServer.ps1
│   │       └── Initialize-WebServer.ps1
│   ├── Find-WMILocalAdminAccess.ps1
│   ├── Kerbrute_386.exe
│   ├── powerview.ps1
│   ├── Rubeus.exe
│   └── SharpHound.ps1
├── local_admin
│   ├── Find-WMILocalAdminAccess.ps1
│   ├── lateral.txt
│   ├── Mimikatz
│   │   ├── mimikatz64.exe
│   │   └── mimikatz.exe
│   ├── powerview.ps1
│   ├── Procdump
│   │   ├── Eula.txt
│   │   ├── procdump64a.exe
│   │   ├── procdump64.exe
│   │   ├── procdump.exe
│   │   └── Procdump.zip
│   ├── PSTools
│   │   ├── PsExec64.exe
│   │   ├── PsExec.exe
│   │   ├── PsLoggedon64.exe
│   │   ├── PsLoggedon.exe
│   │   └── PSTools.zip
│   └── weaken.bat
├── local_user
│   ├── Find-WMILocalAdminAccess.ps1
│   ├── ncat.exe
│   ├── nc.exe
│   ├── nmap.exe
│   ├── PowerUp.ps1
│   ├── Seatbelt.exe
│   ├── SeImpersonatePrivilege
│   │   ├── GodPotato-NET2.exe
│   │   ├── GodPotato-NET35.exe
│   │   ├── GodPotato-NET4.exe
│   │   ├── PrintSpoofer64.exe
│   │   ├── Rogue-Potato
│   │   │   ├── Chisel
│   │   │   │   ├── Linux
│   │   │   │   │   └── chisel_1.7.7_linux_amd64.gz
│   │   │   │   └── Windows
│   │   │   │       └── chisel_1.7.7_windows_amd64.gz
│   │   │   ├── _config.yml
│   │   │   ├── LICENSE
│   │   │   ├── nc64.exe
│   │   │   └── README.md
│   │   └── RoguePotato.exe
│   ├── weaken.bat
│   ├── wget.exe
│   └── winPEASx64.exe
├── pivot
│   ├── ligolo_agent
│   │   └── ligolo_x64
│   │       ├── agent.exe
│   │       ├── LICENSE
│   │       ├── ligolo-ng_agent_0.6.2_windows_amd64.zip
│   │       └── README.md
│   ├── nmap.exe
│   ├── powercat.ps1
│   ├── pscp64.exe
│   └── putty
│       ├── putty_x64
│       │   ├── PAGEANT.EXE
│       │   ├── PLINK.EXE
│       │   ├── PSCP.EXE
│       │   ├── PSFTP.EXE
│       │   ├── PUTTY.CHM
│       │   ├── PUTTY.EXE
│       │   ├── PUTTYGEN.EXE
│       │   └── putty_x64.zip
│       └── putty_x86
│           ├── PAGEANT.EXE
│           ├── PLINK.EXE
│           ├── PSCP.EXE
│           ├── PSFTP.EXE
│           ├── PUTTY.CHM
│           ├── PUTTY.EXE
│           ├── PUTTYGEN.EXE
│           └── putty_x86.zip
├── windows-resources__kali-list.zip
└── win.zip

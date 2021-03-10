DPGLUE by MjK
======================

This version is used for commandline.

It is not used with SnapCenter !

Version is DPGLUE v1.1.3 - 20210310

Use dpgl.exe -h from Win64.

Use dpgl.bin -h from Linux (x86_64) primarily RH/Centos builds tested

Support for Element OS is provided via dpgl.<exe|bin> -dubr "-ln2sf-" or "ln4sf" etc.

There is an extensive readme file provided within the zipped package.

Unzip to use.

Note:  PSHELL scripts are open source. PowerShell and PWSH 7.0 is required.  Sync64.exe for windows should be installed and manually run once for FS sync. Powershell is solely used for proper Restful API to/from Element and for calling FS sync. Otherwise the entire software is written in ANSI C and LUA.  The SolidFire Powershell cli toolkit are not used. This is so the DPGLUE platform is portable and usable for myriad of platforms.  The goal of DPGLUE is around Data protections. It can execute the Element integration on behalf of other app "plugins" too. 


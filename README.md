# Citrix-ADC-Upgrade
Upgrade your Citrix ADC from Windows with this small tool. Select the Firmware file, input the username, password and NSIP.
The tool will then check SSH access to the ADC
Cleanup some folders to create enough space for the upgrade
Check if the ADC is a passive node
Perform the upgrade and a reboot.
When the upgrade is done, you can review the upgrade.log in the same folder.

The hta file needs putty.exe and pscp.exe [from putty.org](https://putty.org) in the same directory. If these are not present, they will be downloaded.

The exe file contains all these files and an icon and was created with [WinRAR](https://www.winrar.com)

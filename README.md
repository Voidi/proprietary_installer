proprietary_installer
=====================
**Simplyfing installation of stuff**

ksp_installer
-------------
This scripts searches for an existing KSP Installation in the current dir or at Path given as commandline argument.
If no KSP executable is found it will try to download the newest release from https://kerbalspaceprogram.com.
You will be ask for your KSP Store login credentials (if correct, they will saved in YOUR copy of this script).
After extracting to the desired Path, it applys the patch against segfaults, creates a launch script with the right language enviroment and a program starter with icon.

Dependencies: aside from standard *nix tools, `xxd` (included in the vim project) and `perl` are required for binary patching
```shell
wget https://raw.githubusercontent.com/Voidi/proprietary_installer/master/ksp_installer
chmod u+x ksp_installer
./ksp_installer <Path to Game directory>
```
teamspeak3_installer
-------------
This scripts searches for an existing TeamSpeak3 Client Installation in the current dir or at Path given as commandline argument.
If no TeamSpeak3 Client executable is found it will try to download the newest release from https://files.teamspeak-services.com/releases/.
After extracting to the desired Path, it creates a program starter with icon.

```shell
wget https://raw.githubusercontent.com/Voidi/proprietary_installer/master/teamspeak3_installer
chmod u+x teamspeak3_installer
./teamspeak3_installer <Path to Game directory>
```

proprietary_installer
=====================
**Simplyfing installation of stuff**

ksp_installer
-------------
This scripts searches for an existing KSP Installation in the current dir or at Path give as commandline argument.
If no KSP executable is found it will try to download the newest release from https://kerbalspaceprogram.com.
You will be ask for credentials (the will saved in YOUR copy of this script).
After extracting to desired Path, it applys the patch against segfaults, creates a launch script with the right language enviroment and a program starter with icon.
```
wget https://raw.githubusercontent.com/Voidi/proprietary_installer/master/ksp_installer
chmod u+x ksp_installer
./ksp_install <Path to Game directory>
```

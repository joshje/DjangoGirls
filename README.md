[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

# DjangoGirls Tutorial
This is a version of the DjangoGirls tutorial (https://tutorial.djangogirls.org/en/).
>This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/

## Using Windows 10 Host and Ubuntu Xenial64 in VirtualBox with Vagrant

After installing VirtualBox, add VirtualBox to the Windows path. One way to do this is to launch PowerShell as administrator and then run this command:

```sh
[Environment]::SetEnvironmentVariable("Path", "C:/Program Files/Oracle/VirtualBox;" + $env:Path, "Machine")
```

After installing Vagrant make sure to install the Vagrant VirtualBox Guest manager:
```sh
vagrant plugin install vagrant-vbguest
```

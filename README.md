# iron-pepperflash
Install and configure SRWare Iron with Pepperflash (Adobe Flash Player for Chromium-based browsers)

*Currently this script will only work on Debian/Ubuntu and derivative distros*

## Installation
```
$ git clone https://github.com/uberhacker/iron-pepperflash
$ cd iron-pepperflash
$ chmod +x iron-pepperflash
$ sudo cp iron-pepperflash /usr/local/bin
$ iron-pepperflash
```
To verify the installation, launch SRWare Iron and visit chrome://plugins/.  The Adobe Flash Player plugin should be visible.
## Upgrade
```
$ cd /path/to/iron-pepperflash
$ ./iron-pepperflash up|upgrade
```

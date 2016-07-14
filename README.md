# HuaweiE173LinuxDriver

This project is for Linux users who need to use [Huawei E173 USB Modem][1].

Fetch the source codes from [Mobile Partner 21][2].

## Modifications of Codes

The modifications of codes are:

1. From [here][3].

   > Locate to the line Ln 2718,change dbg ("cant't kmalloc dev"); to //dbg ("cant't kmalloc dev");(adding double // infront of dbg),save the file and close the terminal.
2. Modify the Makefiles to install driver easily. 

## Usage
1. Git clone or download zip to your computers.
2. Install build kernel module packages.
3. Go to source codes directory.
4. ```make```
5. ```sudo make install```
6. Use your Linux distro. network manager to dial modem on this device.

## Remove Module
1. Go to source code directory.
2. ```sudo make mclean```

### I don't have copyright for codes, and I just make this driver useful and install easily. If Huawei Tech or somebody get infringement for this project, you can send message to me to remove this project, thanks.



[1]:http://www.3g-modem-wiki.com/page/Huawei+E173
[2]:http://www.mediafire.com/download/9oa5g9dx5xeoy97/mp21.zip
[3]:https://askubuntu.com/questions/323031/how-to-install-ndis-driver-for-huawei-mobile-broadband-devices/414401

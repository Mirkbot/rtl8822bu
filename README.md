# RTL8822BU for Linux supporting Kernel 4.14.5

## About

Driver for 802.11ac USB Adapter with  
RTL8822BU chipset  
Only STA/Monitor Mode is supported, no AP.  

This is my version of the rtl8822bu driver supporting kernel 4.14.5.
It is based on this driver: https://github.com/jeremyb31/rtl8822bu

Currently only tested on X86_64 - Fedora 27 with Kernel 4.14.5

## Installation

### Using DKMS

DKMS will make sure the driver is recompiled with each new kernel version
that gets installed and is the least effort over all.

To install use `dkms-install.sh`
For removal `dksm-remove.sh`

### Without DKMS

For compiling type  
`make`  
in source dir  

To install the firmware files  
`sudo make install`

# OBDX Pro J2534 4.04 Releases and Information

The purpose of this repository is to allow developers and individuals to download and access the latest OBDX J2534 releases for all supported scantools.
Please see the changelog of each scantool for specific changes.

These releases include 32bit and 64bit installers, along with the individual DLL for developers looking to embed the J2534 DLL API into their application. Both 32bit and 64bit installers/DLLs can exist on the same PC.

There are no public dealership softwares (As of March 2023) that we are aware of which use 64bit J2534, thus the 64bit J2534 install and DLL should only be used by developers that are compiling their application for 64bit. If using 64bit, then it is recommended to embed the DLL into your application/installer to minimise confusion to end users.


## Supported J2534 Software ##

Our J2534 API has been tested on a variety of dealership and 3rd party J2534 applications including:
* GM ACDelco Techline SPS2 and SPS1
* GM GDS2
* Ford FJDS
* PCM Hammer (Using the J2534 option)
* PCMTEC
* Forscan
* Bitbox
We have had reports of many other J2534 applications being used and working from customers.


## Custom J2534 Commands ##

We also support adding custom commands to the J2534 standard. The following custom commands are available:
1) Reading 128bit OBDX Serial (J2534-2 Serial_Number only provides a 32bit serial)
2) Requesting all available OBDX Pro scantools before connecting
Additional custom commands can be added, please contact us for any suggestions or requests.


## Issues and Support ##

If you come across an issue while using a J2534 application, or while developing your own J2534, please contact us with as much information as possible so that we can assist.
If using a 3rd party J2534 application, we will need to know which scantool you are using, what application, what vehicle (Year, manufacture, model ect) and what ECU/Module you are trying to connect to.
If developing your own J2534 application, we will need to know the above information along with what issue is occuring/
There will be a switchable logging option to enable in a future update which will also be encouraged to help with debugging.


Regards,
OBDX Pro Team

# OBDX Pro J2534 Releases and Information

The purpose of this repository is to allow developers and individuals to download and access the latest OBDX J2534 releases for all supported scantools.
Please see the changelog of each scantool for specific changes.

These releases include 32bit and 64bit installers, both 32bit and 64bit installers/DLLs can exist on the same PC 64bit computer.

There are no public dealership softwares (As of March 2023) that we are aware of which use 64bit J2534, thus the 64bit J2534 install and DLL should only be used by developers that are compiling their application for 64bit. If using 64bit, then it is recommended to embed the DLL into your application/installer to minimise confusion to end users.

J2534 has been split into two main folders, J2534 4.04 and J2534 5.00.
The 4.04 API is what 99.9% of J2534 sofwtare use, only a very small portion of software use the latest 5.00 API.
We have yet to complete our 5.00 API but will as soon as we have an ECU and software setup which utilises the 5.00 API.


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


If developing your own J2534 application, we will need to know the above information along with what issue is occuring.
There will be a switchable logging option to enable in a future update which will also be encouraged to help with debugging.


## Common Questions and Answers ##

**Q: Does your scantool support "enter J2534 software name"?**

A: We have tested many different J2534 softwares, but have not tested for every single application out there. If there is one you want us to specifically test that we have not listed, then let us know so we can investigate!

- - - -

**Q: Does your scantool/J2534 API support "enter your vehicle"?**

A: As there are several thousands of different vehicles, we unfortunately cannot test every car. But all of our tools (Except the OBDX Pro VT) support CANBus which is used in 90%+ of vehicles from when OBD2 become SAE standardized. Each of our scantools indicate which OBD2 protocols they support on their product pages so make sure to check if your vehicle uses one of those protocols, this is typically indicated in workshop manuals or can typically be found online.

- - - -

**Q: Do you have a windows J2534 template project to develop with the OBDX J2534 API?**

A: Unfortunaely we do not have a J2534 specific windows template at this time. But we do have template applications for windows and MAUI that allow direct communciation to the OBDX Pro without needing the J2534 API installed.

- - - -


Regards,
OBDX Pro Team

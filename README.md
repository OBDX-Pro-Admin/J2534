# OBDX Pro J2534 4.04 Releases and Information

The purpose of this repository is to allow developers and individuals to download and access the latest OBDX J2534 releases for all supported scantools.
Please see the changelog of each scantool for specific changes.

These releases include 32bit and 64bit installers, along with the individual DLL for developers looking to embed the J2534 DLL API into their application. Both 32bit and 64bit installers/DLLs can exist on the same PC.

There are no public dealership softwares (As of March 2023) that we are aware of which use 64bit J2534, thus the 64bit J2534 install and DLL should only be used by developers that are compiling their application for 64bit. If using 64bit, then it is recommended to embed the DLL into your application/installer to minimise confusion to end users.

We also support adding custom commands to the J2534 standard. The following custom commands are available:
1) Reading 128bit OBDX Serial (J2534-2 Serial_Number only provides a 32bit serial)
2) Requesting all available OBDX Pro scantools before connecting
Additional custom commands can be added, please contact us (support@obdxpro.com) for any suggestions or requests.

Regards,
OBDX Pro Team

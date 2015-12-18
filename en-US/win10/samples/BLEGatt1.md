---
layout: default
title: BLE GATT Sample - Tools
permalink: /en-US/win10/samples/BLEGatt1.htm
lang: en-US
---

### GATT Attribute Table Dump Tool
In order to communicate with a BLE device using GATT, you will need to know the UUIDs of the desired GATT services and characteristics. Luckily for us TI has provided us with a GATT attribute table for the SensorTag [here](http://processors.wiki.ti.com/images/a/a8/BLE_SensorTag_GATT_Server.pdf){:target="_blank"}. 

When a GATT attribute table is not provided for the device you are working with, you can use the Bluetooth GATT Database Viewer (BthGATTDump.exe) to generate a GATT attribute table as understood by Microsoft Windows. The tool is part of the Windows Driver Kit (WDK) which can be found [here](https://msdn.microsoft.com/en-us/library/windows/hardware/ff557573(v=vs.85).aspx){:target="_blank"}. Once installed the tool and a README.txt containing instructions are located here `C:\Program Files (x86)\Windows Kits\10\Tools\<ARCH>\Bluetooth\BthGATTDump\` where <ARCH> is the architecture of the system you installed the tool on.

Remember this is a command line tool and [here]({{site.baseurl}}/{{page.lang}}/win10/samples/BLEGattDump.htm){:target="_blank"} is an example GATT attribute table dump file of the SensorTag.

### What's Next?
[Using and Dissecting the Code]({{site.baseurl}}/{{page.lang}}/win10/samples/BLEGatt2.htm) --- Learn how to use the sample along with a walkthrough of the code.

#### Previous Page
[Sample Overview]({{site.baseurl}}/{{page.lang}}/win10/samples/BLEGatt.htm) --- Learn about BLE, GATT, and the TI CC2541 SensorTag.

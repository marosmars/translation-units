# show version

## REST call

```
http://localhost:8181/restconf/operational/network-topology:network-topology/topology/cli/node/IOS1/yang-ext:mount/ios-essential:version
```

## REST response body

```
{
    "version": {
        "conf-reg": "0x2102",
        "os-family": "Cisco IOS",
        "platform": "7200",
        "os-version": "15.2(4)S5, RELEASE SOFTWARE (fc1)",
        "serial-id": "4279256517",
        "sys-memory": "491520K/32768K",
        "sys-image": "tftp://255.255.255.255/unknown"
    }
}
```


---

<pre>
R121#show version
<b><mark>Cisco IOS</b></mark> Software, <b><mark>7200</b></mark> Software (C7200-ADVIPSERVICESK9-M), <b><mark>Version 15.2(4)S5, RELEASE SOFTWARE (fc1)</b></mark>
Technical Support: http://www.cisco.com/techsupport
Copyright (c) 1986-2014 by Cisco Systems, Inc.
Compiled Thu 20-Feb-14 06:51 by prod_rel_team

ROM: ROMMON Emulation Microcode
BOOTLDR: 7200 Software (C7200-ADVIPSERVICESK9-M), Version 15.2(4)S5, RELEASE SOFTWARE (fc1)

R121 uptime is 5 minutes
System returned to ROM by unknown reload cause - suspect boot_data[BOOT_COUNT] 0x0, BOOT_COUNT 0, BOOTDATA 19
System image file is "<b><mark>tftp://255.255.255.255/unknown</b></mark>"
Last reload reason: Unknown reason



This product contains cryptographic features and is subject to United
States and local country laws governing import, export, transfer and
use. Delivery of Cisco cryptographic products does not imply
third-party authority to import, export, distribute or use encryption.
Importers, exporters, distributors and users are responsible for
compliance with U.S. and local country laws. By using this product you
agree to comply with applicable laws and regulations. If you are unable
to comply with U.S. and local laws, return this product immediately.

A summary of U.S. laws governing Cisco cryptographic products may be found at:
http://www.cisco.com/wwl/export/crypto/tool/stqrg.html

If you require further assistance please contact us by sending email to
export@cisco.com.

Cisco 7206VXR (NPE400) processor (revision A) with <b><mark>491520K/32768K</b></mark> bytes of memory.
Processor board ID <b><mark>4279256517</b></mark>
R7000 CPU at 150MHz, Implementation 39, Rev 2.1, 256KB L2 Cache
6 slot VXR midplane, Version 2.1

Last reset from power-on

PCI bus mb0_mb1 (Slots 0, 1, 3 and 5) has a capacity of 600 bandwidth points.
Current configuration on bus mb0_mb1 has a total of 1000 bandwidth points. 
The set of PA-2FE, PA-POS-2OC3, and I/O-2FE qualify for "half 
bandwidth points" consideration, when full bandwidth point counting 
results in oversubscription, under the condition that only one of the 
two ports is used. With this adjustment, current configuration on bus 
mb0_mb1 has a total of 1000 bandwidth points. 
This configuration has oversubscripted the PCI bus and is not a 
supported configuration. 

PCI bus mb2 (Slots 2, 4, 6) has a capacity of 600 bandwidth points.
Current configuration on bus mb2 has a total of 400 bandwidth points 
This configuration is within the PCI bus capacity and is supported. 

Please refer to the following document "Cisco 7200 Series Port Adaptor
Hardware Configuration Guidelines" on Cisco.com <http://www.cisco.com>
for c7200 bandwidth points oversubscription and usage guidelines.

WARNING: PCI bus mb0_mb1 Exceeds 600 bandwidth points

1 FastEthernet interface
3 Gigabit Ethernet interfaces
509K bytes of NVRAM.

8192K bytes of Flash internal SIMM (Sector size 256K).
Configuration register is <b><mark>0x2102</b></mark>
</pre>



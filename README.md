# VirtualNetwork
Two virtual networks, internal and external, made with virtual machines.

The internal network contains:
- 2 HTTP Server (Ubuntu Server 18.04)
- 1 FTP Server (Ubuntu Server 18.04)
- 2 Clients (Ubuntu 18.04)
- 1 DNS Server (CentOS 8)

The external network contains:
- 1 DNS Server (CentOS 8)
- 1 Client (Windows 10)

The communication between the servers is made with real devices, a router, Cisco 1941 Series, and two switches, Catalyst 2960 Plus Series.

Here are presented the OVF files from the virtual machines used to represent the different servers. The virtualization software is Oracle VM VirtualBox. The real machines, running the virtual ones, were connected by cable.

In order to set up the communication of the virtual machines to the outside of the machine where they are running, just follow these steps:

1. Select virtual machine;
2. Click on "Settings";
3. Select "Network";
4. Select "Adapter 1";
5. Choose "Bridged Adapter" in "Attached to" option;
6. Open "Advanced";
7. Choose "Allow All" in "Promiscuous Mode".

12 jan 2020 16:56

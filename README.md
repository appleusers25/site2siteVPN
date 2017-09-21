# Site2SiteVPN
Hi,

this is a Site 2 Site VPN service for the CISCO Network Service Orchestration (NSO).

Cisco Network Services Orchestrator enabled by Tail-f® is an industry-leading orchestration platform for hybrid networks. It provides comprehensive lifecycle service automation to enable you to design and deliver high-quality services faster and more easily.

My Lab environment will use following tools/operating systems/software:
* GNS3 Graphical Network Simulator
* Virtualbox
* Linux CentOS 7
* NSO
* Itential Pronghorn

## GNS3 
GNS3 is a Graphical Network Simulator. This tool allows easy network mapping and testing. First, the appropriate router or vms must be added to GNS3. For more information, visit GNS3's official [website](https://www.gns3.com/).

## Virtualbox / Linux CentOS 7 / NSO / Itential Pronghorn
These four components are required for the administrative interface to the routers. First, create a virtual machine with a Linux server. Then install NSO system on the server, followed by the Pronghorn system.
Depending on how your Lab environment looks in GNS3, you need to configure your network card.
For more information visit the websites of the manufacturers.

The following figure illustrates the lab environment described above:

![Lab-Enviroment](/images/lab-environment.png)


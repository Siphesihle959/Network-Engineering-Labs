# Inter Vlan Routing Basics

## Objectives
configure the router and verify connection between two devices.

## Devices Used
- 2 switches 2960
- 2 PCs
- 1 Router 2911

## IP Configurations
- PC0 IP: 192.168.1.2 255.255.255.0 Gateway: 192.168.1.1
- PC1 IP: 192.168.2.2 255.255.255.0 Gateway: 192.168.2.1

## Steps Performed
- Added 2 PCs, 2 Cisco 2960 switches and a 2911 router to the workspace.
- COnfigured the PCs with the IP addresses and their default Gateway.
- Configured the router with the appropriate configurations.
- Tested connectivity by pinging PC1 from PC0.

## Test Result
The ping from PC1 to PC0 was successfully, verifying communication/connectivity.

## Skills Demonstrated
- Basic router configuration for inter-network communication
- Default gateway configuration and subnet separation
- Inter-network connectivity testing using ICMP ping

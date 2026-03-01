# Router Inter Vlan Lab

## Objective
Enable communication between four PCs on different VLANs by using a router for inter-VLAN routing.

## Devices Used
- 2 Cisco Switches 2960
- 4 PCs
- 1 Router 2911

## IP Configurations
- PC0: 192.168.100.2 255.255.255.0 **Gateway**: 192.168.100.1
- PC1: 192.168.100.3 255.255.255.0 **Gateway**: 192.168.100.1
- PC2: 192.168.200.2 255.255.255.0 **Gateway**: 192.168.200.1
- PC3: 192.168.200.3 255.255.255.0 **Gateway**: 192.168.200.1 
- **Router Interfaces**
- G0/1.10: 192.168.100.1 255.255.255.0 (Vlan 10 Gateway)
- G0/2.20: 192.168.200.1 255.255.255.0 (Vlan 20 Gateway)

 ## Steps Performed
- Added 4 PCs, 2 Cisco 2960 switches, and 1 Cisco 2911 router to the Packet Tracer workspace.
- Connected PC0 and PC1 to Switch0 and PC2 and PC3 to Switch1 using copper straight-through cables.
- Connected Switch0 to Router interface G0/0 and Switch1 to Router interface G0/1.
- Created VLAN 100 and VLAN 200 on the switches.
- Assigned PC ports to their respective VLANs.
- Configured trunk links between switches and router interfaces.
- Configured router subinterfaces for VLAN 100 and VLAN 200 using encapsulation dot1Q.
- Assigned IP addresses to router subinterfaces to act as default gateways.
- Configured PCs with appropriate IP addresses and default gateways.
- Tested connectivity by pinging PC2 and PC3 from PC1.

## Test Results
- Ping from PC1 → PC2 and PC1 → PC3 succeeded, confirming successful inter-VLAN routing.
- The router successfully routed traffic between different VLAN networks.

## Skills Demonstrated
- Router-on-a-Stick configuration
- VLAN creation and switch port assignment
- Router subinterface and gateway configuration
- Trunk link configuration between switch and router
- Inter-VLAN routing implementation and verification

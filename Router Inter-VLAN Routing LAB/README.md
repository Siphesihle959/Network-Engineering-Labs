# Router Inter-VLAN Routing Using Router-on-a-Stick

## Objective
Enable communication between two PCs on different VLANs by using a router for inter-VLAN routing.

## Devices Used
- 2 Cisco Switches 2960
- 2 PCs
- 1 Router 2911

## IP Configurations
- PC0: 192.168.10.2 255.255.255.0 **Gateway**: 192.168.10.1
- PC1: 192.168.20.2 255.255.255.0 **Gateway**: 192.168.20.1
**Router Interfaces**
- G0/1.10: 192.168.10.1 255.255.255.0 (Vlan 10 Gateway)
- G0/2.20: 192.168.20.1 255.255.255.0 (Vlan 20 Gateway)

 ## Steps Performed
- Added 2 PCs, 2 Cisco 2960 switches, and 1 Cisco 2911 router to the Packet Tracer workspace.
- Connected PC0 to Switch0 and PC1 to Switch1 using copper straight-through cables.
- Connected Switch0 to Router interface G0/0 and Switch1 to Router interface G0/1.
- Created VLAN 10 and VLAN 20 on the switches.
- Assigned PC ports to their respective VLANs.
- Configured trunk links between switches and router interfaces.
- Configured router subinterfaces for VLAN 10 and VLAN 20 using encapsulation dot1Q.
- Assigned IP addresses to router subinterfaces to act as default gateways.
- Configured PCs with appropriate IP addresses and default gateways.
- Tested connectivity by pinging PC1 from PC0.

## Test Results
- Ping from PC0 → PC1 succeeded, confirming successful inter-VLAN routing.
- The router successfully routed traffic between different VLAN networks.

## Skills Demonstrated
- Router-on-a-Stick configuration
- VLAN creation and switch port assignment
- Router subinterface and gateway configuration
- Trunk link configuration between switch and router
- Inter-VLAN routing implementation and verification

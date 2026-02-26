# Inter-Network Routing Using Layer 3 Switch (Cisco 3560)

## Objective
Configure a Cisco Layer 3 switch to enable communication between two PCs on different subnets and verify connectivity.

## Devices Used
- 2 × Cisco 2960 Switches
- 1 × Cisco 3560 Layer 3 Switch
- 2 × PCs

## IP Configurations
- **PC0:** IP 192.168.1.2 /24, Gateway 192.168.1.1
- **PC1:** IP 192.168.2.2 /24, Gateway 192.168.2.1
- **3560 Switch:** 
  - VLAN10 SVI → 192.168.1.1 /24
  - VLAN20 SVI → 192.168.2.1 /24

## Steps Performed
1. Added 2 PCs, 2 Cisco 2960 switches, and 1 Cisco 3560 switch to the Packet Tracer workspace.
2. Configured VLANs 10 and 20 on the Layer 3 switch.
3. Configured SVI interfaces on the Layer 3 switch for each VLAN and assigned the appropriate IP addresses.
4. Assigned switch ports to their respective VLANs.
5. Connected switches and PCs using copper straight-through cables.
6. Tested connectivity by pinging PC1 from PC0.

## Test Results
- Ping from PC0 → PC1 succeeded, verifying inter-network connectivity.

## Skills Demonstrated
- Layer 3 switch configuration for inter-network routing
- VLAN and SVI setup for multi-subnet networks
- Network connectivity verification using ICMP ping

# Office Network, Clusters, and Second Home Setup Documentation

## Objective

Install and connect network devices using a patch panel and wall mount, verify connectivity, manage clusters, and create a new home network cluster connected to an ISP.


## Devices Used

* Office-SW2 Switch
* Office-User PC
* Copper Wall Mount
* Patch Panel
* PC0
* Home Gateway1
* Cable Modem0


## IP Addressing

* Office-User → Tested connectivity to **192.168.20.5** (Office-Admin PC)


## Steps Performed

* Added Office-SW2 to the rack.
* Connected Office-SW2 to the Patch Panel using FastEthernet0/1.
* Connected Office-SW2 to Office-SW1 using GigabitEthernet interfaces.
* Connected Office-User PC to the wall mount.
* Connected wall mount to the Patch Panel.
* Verified network connectivity from Office-User.
* Unclustered and re-clustered the Library devices.
* Added PC0, Home Gateway1, and Cable Modem0.
* Connected PC0 to Home Gateway1.
* Connected Home Gateway1 to Cable Modem0.
* Created and named the **Second Home** cluster.
* Connected the Second Home cluster to the ISP using a coaxial cable.
* Added a note documenting the new devices.


## Test Results

* Successful ping from Office-User to **192.168.20.5**.
* Successfully accessed **office.srv** through the web browser.
* Second Home cluster successfully connected to the ISP.


## Skills Demonstrated

* Switch installation
* Structured cabling
* Patch panel configuration
* End-device connectivity
* Connectivity testing
* Cluster management
* ISP connection setup
* Network documentation


## Key Concepts Learned

* Purpose of patch panels and wall mounts.
* Switch-to-switch and switch-to-end-device connectivity.
* Verifying network communication using ping and web access.
* Organizing large topologies using clusters.
* Connecting a home network to an ISP through a cable modem.


## Conclusion

Successfully expanded the office network, verified connectivity, managed network clusters, and deployed a new home network connected to the ISP.

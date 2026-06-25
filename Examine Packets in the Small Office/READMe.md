# Simulation Mode and PDU Analysis Documentation

## Objective

Create and analyze Simple and Complex PDUs in Simulation Mode to understand packet flow and protocol operation within a network.


## Devices Used

* Office-Admin PC
* Printer0


## IP Addressing

* Source: Office-Admin
* Destination: Printer0 (IPv4 address automatically detected in Complex PDU)


## Steps Performed

* Entered Simulation Mode.
* Created a Simple PDU from Office-Admin to Printer0.
* Used Capture/Forward to observe packet movement.
* Viewed ICMP packet details in the Event List.
* Examined OSI Model and Outbound PDU Details tabs.
* Deleted the Simple PDU.
* Created a Complex PDU between Office-Admin and Printer0.
* Configured Sequence Number as **1234**.
* Configured periodic transmission every **5 seconds**.
* Played the simulation and observed continuous packet generation.


## Test Results

* ICMP Echo Request successfully reached Printer0.
* ICMP Echo Reply successfully returned to Office-Admin.
* PDU information displayed source and destination IPv4 addresses.
* Protocol header information was successfully viewed.
* Complex PDU generated packets automatically every 5 seconds.


## Skills Demonstrated

* Simulation Mode operation
* Packet flow analysis
* ICMP troubleshooting
* Event List navigation
* PDU inspection
* OSI layer analysis
* Protocol header interpretation
* Network traffic monitoring


## Key Concepts Learned

* Difference between Realtime Mode and Simulation Mode.
* How ICMP packets travel through a network.
* Structure of a PDU across OSI layers.
* Viewing protocol headers and packet details.
* Difference between Simple and Complex PDUs.
* How periodic traffic generation works in Packet Tracer.


## Conclusion

Successfully created, monitored, and analyzed both Simple and Complex PDUs. Gained practical understanding of packet movement, ICMP communication, OSI layer processing, and protocol header analysis using Packet Tracer Simulation Mode.

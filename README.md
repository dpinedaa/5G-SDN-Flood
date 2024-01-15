# 5G-SDN-flood 

Welcome to 5G-SDN-flood, an innovative project that leverages Software-Defined Networking (SDN) principles to address and mitigate network floods in 5G environments. This project offers two distinct approaches, each designed to detect and manage SYN, UDP, and ICMP floods effectively.

Approach 1: OVSDetector with RYU Controller
The first approach utilizes Open vSwitch (OVS) in conjunction with the RYU controller to detect and handle floods. All GTP (GPRS Tunnelling Protocol) traffic is directed to the RYU controller, which in turn adds flows to a MongoDB. The system then checks if an IP address has been blocked, providing an efficient mechanism for flood detection and mitigation.

Approach 2: P4 with ONOS Controller
In the second approach, we employ P4 (Programming Protocol-Independent Packet Processors) along with the ONOS (Open Network Operating System) controller. Here, GTP traffic is managed at the switch level, reducing the load on the controller. The controller adds initial flows and dynamically blocks traffic based on its behavior, ensuring a robust and responsive flood management system.

Explore the capabilities of 5G-SDN-flood and enhance the security of your network infrastructure. Feel free to contribute, share ideas, and collaborate on making our networks more resilient against floods.


<!-- Add a link to get into the 5G setup folder  -->
[5G setup folder](/c:/Users/Diana/Documents/GitHub/5G-SDN-Flood/5G-setup)




# Study Café Network


## Description
The Study Café Network demonstrates the implementation of a computer network architecture for a study café with branches in two cities: Jeddah and Riyadh. Each branch is designed to ensure seamless connectivity and efficient network management between its Local Area Networks (LANs).


## Network Design

### Devices:
- Each study room has a PC with a unique IP address assigned via DHCP.
- PCs connect to switches (Cisco 2960) using straight-through cables.
- Switches connect to routers with copper cross-over cables.

### Routing:
- RIP protocol enables communication between LANs across branches.
- Static routes and router hops ensure efficient packet forwarding.

## Features
- Automatic IP assignment using DHCP.
- Full inter-branch communication via RIP.
- Successful ping connectivity between all PCs.


## How to Set Up
1. Deploy PCs, switches, and routers as described.
2. Configure DHCP for automatic IP assignment.
3. Set up RIP on routers to enable inter-LAN communication.
4. Verify connectivity using `ping` commands.

##  Contributors
1. Hadeel Balahamr
2. Nada Khalefa
3. Marh ALmutairi
4. Sarah Alshareef

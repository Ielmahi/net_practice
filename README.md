*This project has been created as part of the 42 curriculum by ilelmahi.*

## Description

This project consists of completing **NetPractice**, a networking training project from the 42 curriculum.  
Its goal is to develop a solid understanding of fundamental **TCP/IP networking concepts** through hands-on configuration exercises.

The project is composed of a series of progressive levels, each presenting a network topology made up of hosts, routers, and switches. For each level, the objective is to correctly configure network interfaces, subnet masks, default gateways, and routing tables so that all required hosts can communicate successfully.

Through these exercises, the project focuses on practical networking rather than theory alone, reinforcing how data flows across networks and how routing decisions are made.

**Main learning objectives include:**
- IPv4 addressing and subnetting
- Subnet masks and CIDR notation
- Default gateways and routing logic
- Static routing configuration
- The role of routers and switches
- Practical understanding of OSI layers (Layer 2 and Layer 3)

## Instructions

### Running the Training Interface

1. Open the NetPractice interface by opening the `index.html` file in a web browser.
2. Select a level from the interface.
3. Configure each device according to the topology requirements by:
   - Assigning valid IP addresses
   - Setting correct subnet masks
   - Defining default gateways when required
   - Adding static routes on routers

4. Validate the configuration to ensure all required communications succeed.

### Exporting Configurations

- After completing a level, use the **Export** feature provided by the interface.
- The configuration is exported as a JSON file (e.g. `level1.json`, `level2.json`, etc.).
- Each exported file contains:
  - `ifs`: network interface configurations (IP address and subnet mask)
  - `routes`: routing table entries (destination and gateway)

### Submission Requirements

- All required level configuration files must be present at the root of the repository.
- Each JSON file must correspond to its respective level and contain a valid configuration.
- All network paths required by the level must be functional and correctly routed.

## Resources

### Networking Concepts Studied

This project covers the following networking fundamentals:

- **TCP/IP Addressing**: IPv4 structure, network and host portions
- **Subnet Masks**: Network segmentation using dotted decimal and CIDR notation
- **Default Gateway**: Routing traffic outside the local subnet
- **Routers and Switches**: Differences between Layer 2 and Layer 3 devices
- **OSI Model**: Practical use of Layer 2 (Data Link) and Layer 3 (Network)
- **Static Routing**: Manual routing table configuration
- **Network Topologies**: Understanding connectivity and routing paths

### References

- RFC 791 — Internet Protocol (IPv4)
- RFC 1519 — Classless Inter-Domain Routing (CIDR)
- *TCP/IP Illustrated, Volume 1* — W. Richard Stevens
- *Computer Networks* — Andrew S. Tanenbaum
- Cisco Networking Academy documentation
- 42 Network internal documentation
- **YouTube — شرح مفصل لل IP Address وال Subnet Mask, الفرق بين Public IP Vs Private IP**  
  https://www.youtube.com/watch?v=Nnv36wG_iCI — a visual tutorial explaining IPv4 addressing and subnet masks, useful for understanding base concepts used in this project. :contentReference[oaicite:0]{index=0}

### AI Usage

Artificial intelligence tools were used for:
- Structuring and writing the `README.md` file according to 42 requirements
- Improving clarity and accuracy of networking concept descriptions

All network configurations and level solutions were completed manually through study and practice.

# OSI Model – Layer Chart (Day 12)

## Objective
Understand network communication architecture by studying the seven layers of the OSI model and mapping common protocols to each layer.

## Tools Used
- Browser
- Google Docs

## OSI Layer Chart

| Layer | Name | Function | Protocols / Examples | Data Unit |
|-------|------|----------|----------------------|-----------|
| 7 | Application | User-facing network services | HTTP, HTTPS, FTP, SMTP, DNS | Data |
| 6 | Presentation | Encryption, compression, formatting | SSL/TLS, JPEG, ASCII | Data |
| 5 | Session | Opens, manages, closes sessions | NetBIOS, RPC, PPTP | Data |
| 4 | Transport | End-to-end delivery, ports | TCP, UDP | Segment |
| 3 | Network | Logical addressing, routing | IP, ICMP, OSPF | Packet |
| 2 | Data Link | MAC addressing, framing | Ethernet, ARP, PPP | Frame |
| 1 | Physical | Raw bit transmission | Cables, Wi-Fi, hubs | Bits |

Memory trick (top to bottom): **All People Seem To Need Data Processing**

## Interview Q&A
- **What is the OSI model?** A 7-layer reference model that standardizes how data moves between devices over a network.
- **Which layer uses IP?** Layer 3 – Network.
- **Which layer uses TCP?** Layer 4 – Transport.

## Approach
1. Studied each of the seven layers and their roles.
2. Mapped protocols such as HTTP, TCP, IP and Ethernet to their layers.
3. Built the layer chart in Google Docs.

## Outcome
I can now explain how data is encapsulated and travels from application to physical layer, and use the model to reason about where network issues and attacks occur (e.g., ARP spoofing at Layer 2, IP spoofing at Layer 3, SYN flood at Layer 4).

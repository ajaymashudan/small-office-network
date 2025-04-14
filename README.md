💻 Simulated Small Office Network using Cisco Packet Tracer
This project presents the design and implementation of a simulated Small Office Network using Cisco Packet Tracer. The network is designed in a ring topology and showcases dynamic routing, server-client interactions, and core networking principles suited for a small business environment.

📌 1. Introduction
The simulation demonstrates how a small office environment can be effectively networked using Cisco 2811 routers, switches, and various end-user devices. Key network services like DNS and HTTP are configured on a local server to provide realistic service infrastructure. The design supports seamless communication and data sharing across the network.

🎯 2. Objective
Design a ring topology-based small office network.

Implement RIP (Routing Information Protocol) for dynamic routing between routers.

Configure a DNS & HTTP server to simulate real-world office services.

Ensure all devices can communicate efficiently and access web and domain services.

🛠️ 3. Tools & Technologies Used
Cisco Packet Tracer (Simulation software)

Cisco 2811 Routers

Switches (Generic)

End Devices (PCs, Printer)

Server (Configured for DNS and HTTP)

RIP (Routing Information Protocol)

Static IP Addressing

HTML (Simple index.html for web server)

📁 4. Code Implementation (Overview)
🔗 Network Design
Topology: Ring

Devices: 4 Routers → Each connected to a Switch → Each Switch connected to 2 PCs

Extra Devices: 1 Printer, 1 Server

⚙️ Server Configuration
DNS: Maps a domain (e.g., www.office.local) to the HTTP server's IP.

HTTP: Hosts a sample index.html representing the company homepage.

📡 Routing
RIP v1 is configured across routers to dynamically learn paths to other networks.

📊 5. Results and Analysis
All PCs successfully communicate with each other across networks.

PCs can access the local DNS and HTTP server.

Ping and traceroute tests validate proper routing and connectivity.

The HTTP server serves the index.html page to all clients.

✅ 6. Conclusion
This project demonstrates practical knowledge of:

IP Addressing and Network Design

Dynamic Routing using RIP

Server and Service Configuration (DNS/HTTP)

Device-level Communication in a simulated environment

It serves as a foundational guide to understanding and deploying a reliable Small Office Network.

📚 7. References
Cisco Networking Academy materials

Cisco Packet Tracer Documentation

YouTube Tutorials & Community Forums

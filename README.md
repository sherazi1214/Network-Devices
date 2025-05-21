# Network-Devices

### 🔹 1. Router
Function: Connects multiple networks together and directs data packets between them.

Use Case: Connects a home or office LAN to the internet.

#### Key Features:

Assigns IP addresses using DHCP.

Uses NAT (Network Address Translation) to share a public IP.

Often includes a firewall for security.

#### Types:

Wired Router – connects via Ethernet cables.

Wireless Router (Wi-Fi Router) – connects devices wirelessly.

### 🔹 2. Switch
Function: Connects devices within a LAN and forwards data to the specific device it's intended for.

Use Case: Used in offices or data centers to interconnect computers, printers, servers.

#### Key Features:

Works at the Data Link Layer (Layer 2).

Uses MAC addresses to forward data intelligently.

Can be managed (configurable) or unmanaged (plug-and-play).

### 🔹 3. Hub
Function: Broadcasts incoming data to all ports regardless of destination.

Use Case: Rarely used today due to inefficiency.

#### Key Features:

Works at the Physical Layer (Layer 1).

No intelligence – causes data collisions.

#### Types:

Active Hub: Amplifies signals.

Passive Hub: Only splits the signal, no amplification.

### 🔹 4. Modem
Function: Converts digital data from a computer into analog for phone lines and vice versa.

Use Case: Provides internet by connecting with your ISP.

#### Key Features:

Stands for Modulator-Demodulator.

Used in DSL, cable, or fiber connections.

Usually built-in with routers today.

### 🔹 5. Access Point (AP)
Function: Allows wireless devices to connect to a wired network.

Use Case: Extends Wi-Fi coverage in buildings.

#### Key Features:

Connects to a switch or router.

Broadcasts a Wi-Fi signal for client devices.

### 🔹 6. Network Interface Card (NIC)
Function: A hardware component that allows a device to connect to a network.

Use Case: Installed in computers and laptops.

#### Types:

Wired NIC (Ethernet)

Wireless NIC (Wi-Fi)

Modern Computers: Usually have both wired and wireless NICs built-in.

### 🔹 7. Bridge
Function: Connects two different LANs and filters traffic.

Use Case: Splits traffic to reduce collisions in busy networks.

#### Key Features:

Works at Data Link Layer (Layer 2).

Learns MAC addresses to forward data correctly.

### 🔹 8. Gateway
Function: Acts as a translator between different network protocols.

Use Case: Used when two different types of networks need to communicate (e.g., LAN to the internet).

#### Key Features:

Works at All OSI layers.

Used in VoIP, email, and cloud communications.

### 🔹 9. Repeater
Function: Boosts and regenerates signals to extend network range.

Use Case: Used to extend LAN or Wi-Fi signals.

#### Key Features:

Operates at Physical Layer (Layer 1).

Helps in overcoming signal attenuation over distance.

### 🔹 10. Firewall (Hardware-based)
Function: Controls incoming and outgoing traffic based on security rules.

Use Case: Protects a network from external threats.

#### Key Features:

Can be standalone hardware or part of a router.

Filters based on IP, port, or protocols.








🔹 Comparison Table:
Device  	        OSI Layer	            Function	              Intelligence
Hub              	Layer 1     	Broadcasts data	                      No
Switch	          Layer 2     	Sends data to intended device	        Yes
Router	          Layer 3	      Connects different networks	          Yes
Bridge	          Layer 2     	Connects and filters LANs           	Yes
Gateway	All layers	Protocol conversion	Yes
Modem	Layer 1	Converts analog ↔ digital signals	No
Repeater	Layer 1	Signal amplification	No
Access Point	Layer 2	Wireless connectivity	Yes
NIC	Layer 1 & 2	Network access for a device	Yes
Firewall	Layer 3/4/7	Network security	Yes

# Complete Networking Complete Course 
Complete Networking Complete Course with real life examples. I will be covering below Networking Concepts in this complete course. Stay tuned and Keep Learning!
<hr>

### TOPIC 1: OSI MODEL AND TCP/IP MODEL  <hr>

 #### 1. OSI MODEL:
 - Seven Layers in OSI Model
 - Protocols at Each OSI Layer

 #### 2. TCP/IP MODEL 

 - Four Layers in TCP/IP Model
 - Protocols at Each OSI Layer
 - IP Addressing in TCP/IP
 - Comparison between OSI and TCP/IP
<hr>

### TOPIC 2: IP ADDRESSING, SUBNET, CIDR BLOCK, PORTS, PROTOCOLS <hr>

#### 1. IP Addressing
- IP Address Overview: Definition and significance in networking
- IPv4 vs IPv6: Differences, advantages, and limitations.
- Private vs Public IP Addressing: Range of private addresses (Class A, B, C)
- IP Address Classes: Class A, B, C, D, E (networking context).

#### 2. Subnet
- Subnetting Overview: Breaking networks into smaller, more manageable parts.
- Subnet Mask: Identifying the network and host portion.
- Subnet Mask: Identifying the network and host portion.
- Classful and Classless Addressing: Traditional Class A, B, C vs CIDR.

#### 3. CIDR Block (Classless Inter-Domain Routing)
- CIDR Overview: Purpose & advantages of CIDR over traditional IP addressing.
- CIDR Notation: Writing IP addresses with subnet prefix (e.g., 192.168.1.0/24).
- Subnetting with CIDR: Calculating subnets and host capacity using CIDR blocks.
- CIDR Block Size and Routing: How CIDR blocks affect network routing.

#### 4. Ports
- Ports Overview: Role of ports in network communication (source and destination ports).
- Port Ranges: IANA’s well-known ports (0-1023), registered (1024-49151), dynamic (49152-65535).
- Common Well-Known Ports: HTTP (80), HTTPS (443), FTP (21), SSH (22), DNS (53), etc.
- Port Forwarding: Enabling external access to specific internal resources (used in firewalls, routers).

#### 5. Protocols
 - Overview:
 - Common Well-Known Protocols: TCP, HTTP, FTP, DNS, SMTP, IMAP.
<hr>

### TOPIC 3: DNS & HTTP/HTTPS <hr>

#### 1. DNS (Domain Name System):
- Introduction to DNS: Purpose of DNS in translating domain names to IP
   addresses.
- DNS Resolution Process: How a DNS query is resolved (Recursive query, Iterative query).
 - Types of DNS Servers:
   	- DNS Resolver: Resolves domain names for clients.
   	- Authoritative DNS Server: Holds the DNS records for domains.
   	- Root DNS Servers: Starting point for DNS queries.
- DNS Records:
  - A Record: Maps domain names to IPv4 addresses.
  - AAAA Record: Maps domain names to IPv6 addresses.
  - CNAME, MX, NS, PTR Records: Other DNS record types for aliasing, mail, and reverse lookup.

#### 2. HTTP/HTTPS (HyperText Transfer Protocol / Secure):
- Introduction to HTTP: The fundamental protocol for data transfer over the web.
- HTTP Methods: Different types of HTTP requests – GET, POST, PUT, DELETE, PATCH.
- HTTP Status Codes: Categorization of response codes (e.g., 2xx, 3xx, 4xx, 5xx).
- What is HTTPS?: Secure version of HTTP, using SSL/TLS encryption.
- SSL/TLS Handshake: Process of establishing a secure HTTPS connection.
- Certificates and SSL/TLS: Role of SSL certificates, Certificate Authorities (CAs), and types of certificates (EV, DV, OV).
- Benefits of HTTPS: Security (encryption), data integrity, and trust.
- Common HTTP/HTTPS Vulnerabilities: E.g., Man-in-the-middle attacks, phishing, certificate spoofing.
<hr>

### TOPIC 4: CLOUD NETWORKING COMPONENTS <hr>

#### 1. Overview of Azure Networking
  - Azure Networking Introduction
  - Azure Regions and Availability Zones
  - Azure’s Global Network

#### 2. Azure Virtual Network (VNet):
  - VNet Overview: A secure, isolated network within Azure to connect Azure resources.
  - Creating VNets and Subnets: Steps to create and manage VNets and subnet divisions.
  - Network Security Groups (NSGs): Filtering network traffic to Azure resources.
  - VNet Peering: Connecting different VNets within or across Azure regions for seamless communication.
  - VPN Gateway and Site-to-Site Connectivity: Establishing secure connections between on-premises networks and Azure VNets.
  - Azure ExpressRoute

#### 3. Load Balancers in Azure: 
  - Azure Load Balancer (Layer 4) - Public, Internal - TCP/UDP traffic, Simple, high-availability load balancing for VMs and services.
  - Azure Application Gateway (Layer 7) - To handle HTTP/HTTPS traffic, Web applications, routing based on URL path, SSL offloading.
  - Traffic Manager - DNS based, global traffic distribution across regions
  - Azure Front Door (Layer 7) - Global web applications, low-latency, content delivery.
  - Azure Gateway (Layer 3/4 (Network)) - Traffic distribution for NVAs, firewall appliances

#### 4. Azure Firewall
#### 5. Azure Network Security: 
  - DDoS Protection
  - Azure Bastion
#### 6. Azure DNS and Content Delivery Network (CDN):
#### 7. Azure Virtual WAN:
#### 8. Azure Network Monitoring and Diagnostics:
  - Azure Network Watcher: Monitoring and troubleshooting network traffic.
  - Azure Monitor: Analyzing network performance and metrics.
  - Azure Traffic Analytics: Gaining insights into network traffic flows.
<hr>

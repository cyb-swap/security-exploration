# Networking-Fundamentals

## Introduction
This section covers the basics of computer networks, network topologies, protocols, and how networks are secured.

### **1. Introduction to Networking for Cybersecurity**
- [ ] **What is Networking?**  
  - Definition and importance of computer networks  
  - How networking relates to cybersecurity  
- [ ] **Types of Networks**  
  - LAN (Local Area Network)  
  - WAN (Wide Area Network)  
  - MAN (Metropolitan Area Network)  
  - PAN (Personal Area Network)  
- [ ] **Network Topologies**  
  - Bus, Star, Mesh, Hybrid, and Ring Topologies  
- [ ] **Common Networking Devices**  
  - Routers, Switches, Firewalls, Modems, Access Points  


### **2. OSI and TCP/IP Models**
- [ ] **OSI Model (7 Layers)**  
  - Physical Layer
      - Functions of the Physical Layer
        - Bit Synchronization: The physical layer synchronizes the bits by providing a clock. This clock controls both sender and receiver thus providing synchronization at the bit level.
        - Bit Rate Control: The Physical layer also defines the transmission rate i.e. the number of bits sent per second.
        - Physical Topologies: Physical layer specifies how the different, devices/nodes are arranged in a network i.e. bus topology, star topology, or mesh topology.
        - Transmission Mode: Physical layer also defines how the data flows between the two connected devices. The various transmission modes possible are Simplex, half-duplex and full duplex.
      - Protocols in Physical Layer
Typically, a combination of hardware and software programming makes up the physical layer. It consists of several protocols that control data transmissions on a network. The following are some examples of Layer 1 protocols:

        - Ethernet (IEEE 802.3) – Widely used for wired networks.
        - Wi-Fi (IEEE 802.11) – For wireless communication.
        - Bluetooth (IEEE 802.15.1) – Short-range wireless communication.
        - USB (Universal Serial Bus) – For connecting devices over short distances.

    - Advantages of the Physical Layer
      - It ensures devices can transmit and receive raw data over physical mediums.
      - It provides universal standards for cables, connectors, and signaling, ensuring compatibility.
      - Support for Various Media: Works with wired (e.g., Ethernet) and wireless (e.g., Wi-Fi) technologies.
    - Limitations of the Physical Layer
      - No Error Handling: Cannot detect or correct errors in data transmission.
      - Susceptible to Physical Damage: Cables, connectors, and hardware failures can disrupt communication.
      - No Data Interpretation: It only transmits bits and doesn’t understand or process the actual data.
  - Data Link Layer  
  - Network Layer  
  - Transport Layer  
  - Session Layer  
  - Presentation Layer  
  - Application Layer  
- [ ] **TCP/IP Model (4 Layers)**  
  - Network Interface  
  - Internet  
  - Transport  
  - Application  
- [ ] **Comparison between OSI and TCP/IP Models**  
- [ ] **Role of Protocols in Cybersecurity**  
  - IP, TCP, UDP, ICMP, HTTP, HTTPS, FTP, DNS, DHCP  


### **3. IP Addressing and Subnetting**
- [ ] **What is an IP Address?**  
  - IPv4 and IPv6  
- [ ] **Subnetting Basics**  
  - Subnet masks and CIDR notation  
  - Network vs. Host Addresses  
- [ ] **Public vs. Private IPs**  
  - NAT (Network Address Translation) and its role in security  
- [ ] **IPv6 Security Considerations**  


### **4. Network Protocols and Security**
- [ ] **Common Protocols and Their Security Risks**  
  - HTTP vs. HTTPS  
  - FTP and SFTP  
  - DNS and DNS Spoofing  
  - ARP and ARP Poisoning  
- [ ] **Securing Protocols**  
  - SSL/TLS encryption  
  - VPN (Virtual Private Network)  
  - IPsec  


### **5. Network Security Basics**
- [ ] **Firewalls**  
  - Types: Hardware vs. Software  
  - Stateful vs. Stateless Inspection  
- [ ] **Intrusion Detection and Prevention Systems (IDS/IPS)**  
- [ ] **Network Access Control (NAC)**  
- [ ] **Zero Trust Security Model**  


### **6. Wireless Network Security**
- [ ] **Wi-Fi Security Protocols**  
  - WEP, WPA, WPA2, WPA3  
- [ ] **Common Wireless Threats**  
  - Man-in-the-Middle (MITM) Attacks  
  - Evil Twin Attacks  
  - Rogue Access Points  
- [ ] **Securing Wireless Networks**  
  - Strong encryption  
  - MAC filtering  
  - Hidden SSID  


### **7. Network Monitoring and Threat Detection**
- [ ] **Network Traffic Analysis**  
  - Packet Sniffing with Wireshark  
- [ ] **Common Attack Indicators**  
  - Unusual Traffic Spikes  
  - Unauthorized Access Attempts  
- [ ] **Security Information and Event Management (SIEM)**  


### **8. Common Network Attacks and Defenses**
- [ ] **Denial-of-Service (DoS) and Distributed DoS (DDoS) Attacks**  
- [ ] **Phishing and Social Engineering**  
- [ ] **Man-in-the-Middle (MITM) Attacks**  
- [ ] **SQL Injection and Web-Based Attacks**  
- [ ] **Defensive Measures**  
  - Firewalls, Anti-Malware, Endpoint Security  


### **9. Introduction to Network Penetration Testing**
- [ ] **Ethical Hacking and Penetration Testing**  
- [ ] **Reconnaissance and Scanning Tools**  
  - Nmap, Metasploit  
- [ ] **Vulnerability Assessment and Exploitation**  
- [ ] **Reporting and Mitigation Strategies**  

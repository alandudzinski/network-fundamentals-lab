# Network Fundamentals Lab: How Data Moves Across A Network

## 1. Project Overview
This project goes over the basic networking concepts from TryHackMe's Network Fundamentals module. The goal is to show how a device communicates over a local network and the internet, using IP addresses, MAC addresses, packets, frames, routers, and common protocols and models.

## 2. Simple Home Network Diagram
Example network:
[My Laptop] -> Wi-Fi / Ethernet -> [Home Router] -> Internet Service Provider (ISP) -> [Internet] -> [Website Server]

## 3. Key Devices in a Network

### Laptop / Client
The laptop is the device requesting information, such as visiting a website.

## Switch
A switch is a dedicated device within a network that aggregates multiple other network-capable devices, improving communication efficiency and reducing network congestion between devices and the router.

### Router
The router connects the local network to the internet. It helps move traffic between private devices and the public network.

### Server
The server is the computer that responds to requests, such as sending back a webpage.

## 4. IP Addresses vs MAC Addresses
### IP Address
An IP address identifies a device on a network. It helps data find the correct destination. An example of an IP address is: 192.168.1.10

### Mac Address
A MAC address identifies a physical network interface, such as a Wi-Fi card or Ethernet adapter. An example of a MAC address is: AA:BB:CC:11:22:33

| Type | Purpose | Example |
|---|---|---|
| IP Address | Finds a device across networks | 192.168.1.10 |
| MAC Address | Finds a device on the local network | AA:BB:CC:11:22:33

## 5. OSI Model Summary
| Layer | Name | Simple Explanation |
|---|---|---|
| 7 | Application | Apps and services users interact with |
| 6 | Presentation | Formats and encrypts data |
| 5 | Session | Manages connections between systems |
| 4 | Transport | Controls data delivery using TCP or UDP |
| 3 | Network | Handles IP addresses and routing |
| 2 | Data Link | Handles MAC addresses and frames |
| 1 | Physical | Cables, signals, Wi-Fi, and hardware |

## 6. Packet vs Frame


## 7. TCP vs UDP

## 8. Common Network Protocols

## 9. What Exactly Happens When I Visit a Website?

## 10. Security Takeaways

## 11. What I Learned

## References
- TryHackMe. "Introduction to Cyber Security." TryHackMe, [https://tryhackme.com/](https://tryhackme.com/module/network-fundamentals)

## Disclaimer
This project is for educational purposes only. It summarizes concepts learned through TryHackMe and does not include walkthrough answers, flags, or private room solutions.

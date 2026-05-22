# VPN and Tunneling Network Security Lab

## Project Overview
This project demonstrates VPN tunneling concepts using virtual machines, TUN/TAP interfaces, and Wireshark packet analysis.

## Skills Demonstrated
- VPN tunneling concepts
- Network-layer security
- Packet capture and analysis
- Wireshark traffic inspection
- Secure communication risk analysis

## Security Problem
Private network communication can expose traffic if not properly tunneled or protected.

## Lab Implementation
- Configured VPN client and server virtual machines
- Verified network connectivity
- Captured traffic using Wireshark
- Analyzed encapsulated packets and tunneling behavior

## Risk / Control Mapping
| Risk | Control |
|---|---|
| Exposed network traffic | VPN tunneling |
| Unauthorized network access | Controlled tunnel endpoints |
| Poor visibility | Packet capture and monitoring |

## 🧪 Validation & Analysis

### 🔧 VPN Connectivity Test
![VPN Client Server Ping](images/vpn-ping.png)

Demonstrates successful communication between VPN client and server, confirming tunnel establishment.

---

### 🔍 Packet Analysis with Wireshark
![Wireshark Capture](images/wireshark-capture.png)

Shows encapsulated traffic within the tunnel, validating secure packet transmission and network-layer behavior.

## GRC Relevance
This project demonstrates how VPNs support secure communications, access control, monitoring, and network segmentation.

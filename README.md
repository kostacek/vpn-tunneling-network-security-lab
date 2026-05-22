# 🔐 VPN & Tunneling Network Security 

This project demonstrates the implementation and analysis of Virtual Private Network (VPN) tunneling, focusing on secure communication, packet encapsulation, and traffic visibility using Wireshark.

---

## 📌 Project Overview

Modern networks require secure communication channels to protect sensitive data from interception. This lab explores how VPN tunneling establishes a secure communication path over an untrusted network.

The project includes:
- VPN client and server configuration
- Tunnel establishment using TUN/TAP interfaces
- Network traffic capture and analysis with Wireshark
- Evaluation of packet encapsulation and routing behavior

---

## 🧠 Skills Demonstrated

- Network security fundamentals  
- VPN tunneling concepts (Layer 3)  
- Packet capture and analysis (Wireshark)  
- Secure communication validation  
- Risk identification and mitigation  
- Network traffic inspection  

---

## ⚠️ Security Problem

Traditional network communication exposes data to potential interception if transmitted without encryption or segmentation.

### 🔎 Risk Impact
- **Severity:** High  
- **Risk:** Unauthorized interception of network traffic  
- **Impact:** Exposure of sensitive data and internal communications  

---

## 🛠️ Lab Implementation

### 🔧 Environment Setup
- Configured VPN client and VPN server using virtual machines  
- Assigned IP addresses to both systems  
- Verified connectivity using network commands  

---

### 🔗 VPN Tunnel Establishment

The VPN tunnel creates a secure communication channel between client and server using IP tunneling techniques.

### 🖼️ VPN Connectivity Test
![VPN Client Server Ping](images/vpn-ping.png)

✔ Demonstrates:
- Successful communication between endpoints  
- Tunnel establishment  
- Functional network-layer connection  

---

## 🔍 Packet Analysis with Wireshark

Wireshark was used to capture and analyze traffic flowing through the VPN tunnel.

### 🖼️ Wireshark Capture
![Wireshark Capture](images/wireshark-capture.png)

✔ Observations:
- Encapsulated packets within the tunnel  
- Source and destination IP transformations  
- Traffic routing through virtual interfaces (TUN/TAP)  

---

## 🔐 Security Concepts Demonstrated

- **Encapsulation:** Original packets wrapped inside new packets for secure transport  
- **Tunneling:** Secure path established over public networks  
- **Traffic Analysis:** Visibility into packet structure and routing  
- **Network Isolation:** Separation of internal communication from external networks  

---

## 🛡️ Risk / Control Mapping

| Risk | Control Implemented |
|------|-------------------|
| Exposure of network traffic | VPN tunneling |
| Unauthorized access | Controlled endpoints |
| Lack of visibility | Packet capture and monitoring |
| Weak network segmentation | Tunnel-based communication |

---

## 🧪 Validation

- Verified connectivity using `ping` between VPN client and server  
- Captured live traffic using Wireshark  
- Observed encapsulated packets within the tunnel  
- Confirmed routing through virtual interfaces  

---

## 🎯 Why This Project Matters

This project demonstrates how VPNs support:

- Secure communication over untrusted networks  
- Network segmentation and access control  
- Monitoring and analysis of network traffic  
- Implementation of foundational security controls  

---

## 📄 Full Report

For a detailed technical write-up, see the full lab report:

[VPN and Tunneling Lab Report](docs/VPN_and_Tunneling_Lab.pdf)

---

# Securing a Remote Branch Office using IPSec VPN

This project demonstrates how to establish a **secure communication channel** between a **main office** and a **remote branch office** using an **IPSec VPN tunnel** in Cisco Packet Tracer.

The system ensures **data confidentiality, integrity, and authentication** over an insecure public network.

---

## 📌 Project Overview

Organizations with geographically distributed offices require secure communication over public networks.  
This project implements a **site-to-site VPN using IPSec** to securely connect two internal networks:

- Main Office: 192.168.1.0/24  
- Branch Office: 192.168.3.0/24  

All data transmitted between these networks is encrypted and protected from unauthorized access.

---

## 🎯 Objectives

- Establish secure communication between two networks
- Implement IPSec VPN using Cisco routers
- Ensure confidentiality using AES-256 encryption
- Provide authentication using pre-shared keys
- Maintain data integrity using SHA-HMAC

---

## 🧰 Tools & Technologies

- Cisco Packet Tracer
- Networking Concepts (IP Routing, VPN)
- IPSec Protocol
- ISAKMP (Internet Security Association and Key Management Protocol)

---

## ⚙️ Network Configuration

### Routers Used:
- R1 (Main Office)
- ISP (Internet Simulation)
- R3 (Branch Office)

### Key Configurations:
- IP addressing and routing
- Static routes
- ISAKMP policy
- IPSec transform set
- Crypto map configuration

---

## 🔐 Security Features

- AES-256 Encryption (Confidentiality)
- Pre-shared Key Authentication
- SHA-HMAC (Integrity Check)
- Perfect Forward Secrecy (PFS)

---

## 📂 Repository Structure

- `Configurations/` – Router configuration files  
- `Documentation/` – Project report  
- `Diagrams/` – Network topology and VPN flow  
- `Results/` – Output screenshots of communication  

---

## 📊 Results

- Secure communication between internal networks
- Encrypted data transmission via IPSec tunnel
- Successful packet transfer verification

---

## 🚀 Applications

- Corporate branch connectivity
- Secure enterprise networks
- Remote office communication
- Data center interconnection

---

## 🏫 Institution

KLS Gogte Institute of Technology, Belagavi  
Department of Electronics and Communication Engineering  

---

## 📜 License

This project is for **academic purposes only**.

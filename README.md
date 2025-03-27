# Financial Institution Network - Cisco Packet Tracer

## Overview
This project implements a secure and efficient network for a financial institution using Cisco Packet Tracer. The network ensures smooth operations, secure transactions, and seamless communication between departments.

## Network Design
The financial institution's network consists of:

- **Head Office**: Data Center, Administration, and Finance Departments.
- **Branch Offices**: Securely connected to the head office.
- **Customer Service Area**: Handles online banking, ATMs, and customer queries.
- **Security & Monitoring**: Firewalls, intrusion detection, and VPN access.

## Devices Used

| Device                  | Quantity |
|-------------------------|----------|
| Routers (Cisco 2911)    | 3        |
| Switches (Cisco 2960)   | 5        |
| Servers (DNS, Web, Mail)| 3        |
| PCs                     | 15       |
| Laptops                 | 10       |
| ATMs                    | 4        |
| Firewalls               | 2        |

## Network Implementation
- **Main Router**: Connects branches via secure VPN.
- **Core Switch**: Connects head office departments.
- **Wireless Access Points**: Provide employee and client connectivity.
- **Firewalls & IDS**: Secure transactions and customer data.
- **Servers**: Manage DNS, web banking, and emails.

## IP Addressing & Security
The structured IP scheme:
- **Head Office**: `192.168.1.0/24`
- **Branch Offices**: `192.168.2.0/24`
- **Customer Service**: `192.168.3.0/24`

**Security Measures:**
- Firewall rules for transaction protection.
- VPN encryption for remote access.
- Role-based access control (RBAC).

## Testing & Results
The network was simulated and tested in Cisco Packet Tracer:
- **Ping tests**: Confirmed connectivity.
- **Web & Email services**: Successfully accessed.
- **Firewall rules**: Blocked unauthorized access.
- **VPN tunnels**: Secured remote banking.

## Conclusion
This project establishes a secure, scalable, and efficient financial institution network, ensuring reliable connectivity, data security, and smooth banking operations.

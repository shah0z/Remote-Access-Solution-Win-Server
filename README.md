# Remote-Access-Solution-Win-Server
Engineered remote access solution with windows server. Used VPN, NPS(RADIUS), and IPsec security policies for a secured and robust logon for remote employees. 

## Project Overview

This project implements a comprehensive remote access solution designed to securely connect remote clients to a corporate network using VPN technology. The solution integrates:

- **VPN (Virtual Private Network)** for encrypted remote access
- **NPS (Network Policy Server) acting as a RADIUS server** for centralized authentication, authorization, and accounting
- **IPsec Security Policies** to enforce strong encryption and secure communication policies

The goal is to provide a robust, scalable, and secure remote access infrastructure that protects sensitive data and ensures authorized access only.

---

## Features

- Secure VPN connections for remote users
- Centralized user authentication via NPS RADIUS server
- Enforcement of IPsec policies for secure tunnels
- Support for multi-factor authentication (if configured)
- Detailed logging and monitoring through NPS
- Role-based access control via network policies

---

## Technologies Used

- Windows Server with Network Policy Server (NPS) role
- VPN protocols (PPTP, L2TP/IPsec, SSTP, or IKEv2 depending on configuration)
- IPsec policies configured via Group Policy or local security policies
- RADIUS protocol for AAA (Authentication, Authorization, Accounting)

---

## Setup Instructions

1. **Configure the VPN Server:**
   - Install and enable Routing and Remote Access Service (RRAS)
   - Set up VPN protocols supported
2. **Set up NPS (RADIUS) Server:**
   - Install Network Policy Server role
   - Configure RADIUS clients (VPN servers)
   - Create Network Policies for authentication and authorization
3. **Define IPsec Security Policies:**
   - Create IPsec rules to require encryption for VPN traffic
   - Assign policies to VPN server and clients as needed
4. **Client Configuration:**
   - Set up VPN client with appropriate connection settings
   - Ensure IPsec policies or certificates are installed on clients

---

## Usage

- Remote users initiate VPN connection
- VPN server authenticates users via NPS RADIUS server
- IPsec policies ensure secure encrypted tunnels
- Authorized users gain access to corporate network resources

---

## Troubleshooting

- Verify VPN server and NPS logs for authentication issues
- Ensure IPsec policies are correctly assigned and enforced
- Confirm client settings match server requirements

---

## Contributing

This project is currently complete and not open for contributions.

---

## License

MIT LIcense 
---

## Contact

For any questions or further assistance, please contact:

- Shah Azwad Ahnaf
- System Administrator
- Keytech IT Solutions
- Email: shahazwad@keytech.ca
- GitHub: https://github.com/shah0z


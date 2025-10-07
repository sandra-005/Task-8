# Working with VPNs: Privacy, Security, and Performance Analysis

## Overview
This repository contains a detailed practical report on working with VPNs, including connecting to VPN services, verifying IP changes, checking for DNS leaks, testing internet speed, and analyzing the impact on network configuration after disconnecting the VPN. The task demonstrates both the practical and theoretical aspects of VPN usage.

## Objectives
- Understand what a VPN is and how it works.
- Learn how VPNs protect user privacy and security.
- Perform IP and DNS checks to verify VPN functionality.
- Test internet speed before, during, and after using a VPN.
- Analyze routing and network configuration changes with VPN connectivity.
- Compare VPN and proxy services.

## Tools Used
- **VPN Services:** ProtonVPN (Free Tier) / Windscribe (Free Tier)
- **Web Browser:** Firefox / Chrome
- **Websites/Online Tools:**  
  - [WhatIsMyIPAddress](https://whatismyipaddress.com) – IP verification  
  - [DNSLeakTest](https://www.dnsleaktest.com) – DNS leak check  
  - [Speedtest](https://www.speedtest.net) – Internet speed testing  

## Steps Performed
1. Checked original IP and network configuration using `ipconfig /all` and `route print`.  
2. Connected to the VPN and verified new IP address.  
3. Performed DNS leak test to ensure DNS queries were routed through VPN.  
4. Conducted internet speed tests while connected to VPN.  
5. Disconnected the VPN and re-checked IP, DNS, and routing table.  
6. Conducted post-VPN internet speed test.  

## Key Concepts Covered
- VPN functionality and privacy protection  
- Difference between VPN and proxy  
- VPN encryption and protocols  
- Limitations of VPNs  
- VPN impact on network speed  

## Results & Observations
- VPN successfully changed IP address and routed DNS requests through the VPN server.  
- No DNS leaks were detected while connected to the VPN.  
- Internet speed slightly decreased during VPN usage due to encryption overhead.  
- All network settings returned to normal after disconnecting VPN.  

## Conclusion
Using a VPN provides enhanced privacy, encrypts network traffic, and protects DNS queries. While VPNs offer significant security benefits, they may slightly reduce network speed and do not guarantee complete anonymity. Proper verification through IP, DNS, and speed tests ensures VPN functionality.  


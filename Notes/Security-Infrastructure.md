Security Infrastructure - Combination of hardware, softwarem policies, and practices that organizations use to protect information  
Network Appliance - Specialized hardware or software device designed to perform specific networking functions or services  
Port Security - Network security feature that restricts and controls access to a network by allowing only authorized devices to connect  
SD-WAN - Technology that utilizes software-defined netowrking principles to manage and optimize wide area network connections  
SASE - Network security and connectivity framework that integrates network security and wide area networking into a cloud-based service  

Port - Logical communication endpoint that exists on a computer or server  
Inbound Port - Logical communication opening on a server taht is listening for a connection from a client  
Outbound Port - Logical communication opening created on a client in order to call out to a server that is listening for a connection   
Well-Known Ports - Ports 0 - 1023 are considered well-known and are assigned by the Internet Assigned Numbers Authority (IANA)  
Registered Ports - Ports 1024 - 49151 are considered registered and are usually assigned to proprietary protocols  
Dynamic and Private Ports - Port 49152 - 65535 can be used by any application without being registered with IANA  
Protocol - Rules governing device communication and data exchange  
Port 21 - TCP - FTP - Used to transfer files  
Port 22 - TCP - SSH, SCP, and SFTP - Provides secure remote terminal access and file transfer, secure copy functions, secure file transfers  
Port 23 - TCP - Telnet - Provides insecure remote control of another machine using a text-based environment  
Port 25 - TCP - SMTP - Provides the ability to send emails over the network  
Port 53 - TCP and UDP - DNS - Translates domain names into IP addresses  
Port 69 - UDP - Trivial FTP - Used as a lightweight file transfer method for sending configuration files or network booting of an OS  
Port 80 - TCP - HTTP - Used for insecure web browsing   
Port 88 - UDP - Kerberos - Network authentication protocol  
Port 110 - TCP - Post Office Protocol v3 (POP3) - Responsible for retrieving email from a server  
Port 119 - TCP - Network News Transfer Protocol (NNTP) - Used for accessing newsgroups  
Port 135 - TCP and UDP -Remote Procedure Call (RPC) - Facilitates communication between different system processes   
Port 137, 138 and 139 - TCP and UDP - NetBIOS - Networking protocol suite  
Port 143 - TCP - Internet Message Access Protocol (IMAP) - Allows access to email messages on a server  
Port 161 - UDP - Simple Network Management Protocol (SNMP) - Manages network devices  
Port 162 - UDP - SNMP Trap - Responsible for sending SNMP trap messages  
Port 389 - TCP - Lightweight Directory Access Protocol (LDAP) - Facilitates directory services  
Port 443 - TCP - HTTPS - Provides secure web communication  
Port 445 - TCP - Server Message Block (SMB) - Used for file and printer sharing over a network  
Port 465 and 587 - TCP - SMTPS - Provides secure SMTP communication  
Port 514 - UDP - Syslog - Used for sending log messages  
Port 636 - TCP - LDAPS - LDAP communication over SSL/TLS  
Port 993 - TCP - Internet Message Access Protocol over SSL/TKS (IMAPS) - Used for secure email retrieval  
Port 995 - TCP - POP3S - Used for secure email retrieval  
Port 1433 - TCP - Microsoft SQL - Used to facilitate communication with Microsoft SQL Server  
Port 1645 and 1646 - TCP - RADIUS TCP - Used for remote authentication, authorization, and accounting  
Port 1812 and 1813 - UDP - RADIUS TCP - Used for authentication and accounting as defined by the Internet Engineering Task Force (IETF)  
Port 3389 - TCP - RDP - Enables remote desktop access
Port 6514 - TCP - Syslog TLS - Used in a secure syslog that uses SSL/TLS to encrypt the IP packets using a certificate before sending them across the IP network to the syslog collector  

Firewall - Safeguards networks by comitoring and controlling traffic based on predifined security rules   
Screened Subnet (Dual-homed Host) - Acts as a security barrier between external untrusted networks and internal trusted networks, using a protected host with security measures like a packet-filtering firewall  
Packet Filtering (Layer 4) Firewall - Checks packet headers for traffic allowance based on IP addresses and port numbers  
Stateful Firewall - Monitors all inbound and outbound network connections and requests  
Proxy Firewall - Acts as an intermediary between internal and external connections, making connections on behalf of other endpoints  
&nbsp;&nbsp;&nbsp;&nbsp;Circuit Level - Like a SOCKS firewall, operates at the Layer 5 of the OSI model  
&nbsp;&nbsp;&nbsp;&nbsp;Application Level - Conducts various proxy finctions for each type of application at the Layer 7 of the OSI model  
Kernel Proxy Firewall (Fifth Generation Firewall) - Has minimal impact on network performance while thoroughly inspecting packets across all layers  
Next-Generation Firewall (NGFW) - Aims to address the limitations of traditional firewall by being more aware of applications and their behaviors  
Unified Threat Management Firewall (UTM)  Provides the ability to conduct multiple security functions in a single appliance  
Web Application Firewall (WAF) - Focuses on the inspection of the HTTP traffic  
&nbsp;&nbsp;&nbsp;&nbsp;Inline Configuration - Device sits between the network firewall and the web servers  
&nbsp;&nbsp;&nbsp;&nbsp;Out-of-band configuration - Device receives a mirrored copy of web server traffic  
Leyer 4 firewall - Filters based on port numbers and protocols, without inspecting packet content  
Layer 7 firewall - Inspects and controls trafic based on data content and application characteristics  
NGFW - Merges standard firewall functions with advanced threat detection and application awareness  
Unified Threat Management Firewall (UTM) - Comnbines security platform that integrates firewall, antivirus, intrusion detection, and content filtering  
Web Application Firewall (WAF) - Inspects HTTP/HTTPS traffic and applies rule sets to prevent common web-based attacks  

Access Control List (ACL) - A rule set that is placed on firewalls, routers, and other network infrastructure devices that permit or allow traffic through a particular interface  

Network Intrusion Detection Systems (NIDS) - Responsible for detecting unautorized network access or attacks  
Host-Based IDS (HIDS) - Looks at suspicious netwrok traffic going to or from a single server or endpoint  
Wireless IDS (WIDS) - Detects attempts to cause a denial of service on a wireless network  
Signature-based IDS - Analyzes traffic based on defined signatures and can only recognize attacks based on previously identified attacks in its database  
&nbsp;&nbsp;&nbsp;&nbsp;Pattern-matching - Specific pattern of steps (NIDS, WIDS)  
&nbsp;&nbsp;&nbsp;&nbsp;Stateful-matching - Known system baseline (HIDS)  
Anomaly-based/Behavioural-based IDS - Analyzes traffic and compares it to a normal baseline of traffic to determine whether a threat is occuring  
Intrusion Prevention Systems (IPS) - Scans traffic to look for malicious activity and takes action to stop it  

Network Appliance - Dedicated hardware device with pre-installed software that is designed to provide specific networking services  
Load Balancer - Crucial component in any high-availability network or system that is designed to distribute network or application traffic across multiple servers (Application Delivery Controller)  
Proxy Server - Intermediary between a client and a server to provide various functions like content caching, request filtering and login management  
Network Sensor - Designed to monitor, detect, and analyze traffic and data flow across a network in order to identify any unusual activites, potential security breaches, or performance issues  
Jump Server/Box - Dedicated gateway used by system administrators to securly access devices located in different security zones within the network  

Port Security - Common security feature found on network switches that allows administrators to restrict which devices can connect to a specific port based on the network interface card's MAC address  
Content Addressable Memory (CAM) Table - Used to store information about the MAC addresses that are available on any given port of the switch  
Persistent (Sticky) MAC Learning - Feature in network port security where the switch automatically learns and associates MAC addresses with specific interfaces  
802.1x Protocol - Standard framework that is used for port-based authentication for both wired and wireless networks  

Extensible Authentication Protocol  
&nbsp;&nbsp;&nbsp;&nbsp;EAP-MD5 - Variant that utilizes simple passwords and the challenge handshake authentication process to provide remote access authentication  
&nbsp;&nbsp;&nbsp;&nbsp;EAP-TLS - Form of EAP that uses public key infrastructure with a difital certificate being installed on both the client and the server as the method of authenticaiton   
&nbsp;&nbsp;&nbsp;&nbsp;EAP-TTLS - Variant that requires a difital certificate on the server, but not on the client  
&nbsp;&nbsp;&nbsp;&nbsp;EAP-FAST - Variant that uses a protected access credential, instead of a certificate, to establish mutual authentication between devices  
&nbsp;&nbsp;&nbsp;&nbsp;PEAP - Variant that supports mutual authentication by using server certificates and the Microsoft Active Directory databases for it to authenticate a password from the client  
&nbsp;&nbsp;&nbsp;&nbsp;LEAP - Variant of EAP that only works on Cisco-based devices  

Virtual Private Network (VPN) - Extends a private network over a public one, enabling users to securely send and receive data  
&nbsp;&nbsp;&nbsp;&nbsp;Site-to-site VPN - Establishes secure tunnels over the public Internet for interconnecting remote sites  
&nbsp;&nbsp;&nbsp;&nbsp;Cient-to-Site VPN - Connects individual devices directly to the organization's headquarters, enabling remote users to access the network  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Full Tunnel - Maximizes security by encrypting all traffic to the headquarters while integrating clients with the network  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Split Tunnel - Divides traffic and network requests and then routes them to the appropriate network  
&nbsp;&nbsp;&nbsp;&nbsp;Clientless VPN - Secures remote access through browser-based VPN tunnels without needing client software or hardware configuration  
&nbsp;&nbsp;&nbsp;&nbsp;Transport Layer Security (TLS) - A protocol that provides cryptographic security for secure connections and is used for secure web browsing and data transfer  
&nbsp;&nbsp;&nbsp;&nbsp;Transmission Control Protocol (TCP) - Used by TLS to establish secure connections between a client and a server, but it may slow down the connection  
&nbsp;&nbsp;&nbsp;&nbsp;Datagram Transport Layer Security (DTLS) - A UDP-based version of TLS protocol taht offers the same security level and TLS while maintaining faster operations  
Internet Protocol Security (IPSec) - A protocol suite for secure communication through authentication and data encryption in IP networks  
&nbsp;&nbsp;&nbsp;&nbsp;Request to start Internet Key Exchange (IKE) - IKE phase 1 - IKE Phase 2 - Data transfer - Tunnel termination  
&nbsp;&nbsp;&nbsp;&nbsp;1. PC1 initiates traffic to PC2, triggering IPSec tunnel creation by RTR1  
&nbsp;&nbsp;&nbsp;&nbsp;2. RTR1 and RTR2 negotiate security associates for the IPSec IKE Phase 1 (ISAKMP) tunnel  
&nbsp;&nbsp;&nbsp;&nbsp;3. IKE Phase 2 establishes a tunnel within the tunnel  
&nbsp;&nbsp;&nbsp;&nbsp;4. Data transfer between PC1 and PC2 takes place securely  
&nbsp;&nbsp;&nbsp;&nbsp;5. Tunnel termination, including the deletion of IPSec security associations  
Transport Mode - Employs the original IP header, ideal for client-to-site VPNs, and is advantageous when dealing with MTU constraints (MTU usually 1500 bytes)  
Tunneling Mode - Employed for site-to-site VPNs and adds an extra header that can increase packet size and exceed the MTU (May need to enable jumbo packets (< 1500 bytes))  
Authentication Header (AH) - Offers connectionless data integrity and data origin authentication for IP datagrams using cryptographic hash as identification information  
Encapsulating Security Payload (ESP) - Emplyed for providing authentication, integrity, replay protection, and data confidentiality by encrypting the packet's payload  

SD-WAN - Virtualized approach to managing and optimizing wide area network connections to efficiently route traffic between remote sites, data centers, and cloud environments  
Secure Access Service Edge (SASE) - Used to consolidate numerous networking and security functions into a single cloud-native service to ensure that secure and access for end-users can be achieved  

Security Zone - Destinct segment within a network, often created by logically isolating the segment using a firewall or other security device  
Screened Subnet - Hosts public-facing services such as web servers, email servers, and DNS servers and safeguards against security breaches by preventing attackers from gaining direct access to the sensitive core internal network  
Attack Surface of a Network - Refers to all the points where an unauthorized user can try to enter data to or extract data from an environment  
Connectivity - Refers to how different components of a network communicate with each other and with other external networks  

Control - A protective measure put in place to reduce potential risks and safeguard an organization's assets  
&nbsp;&nbsp;&nbsp;&nbsp;Least Privilege - Users or systems are granted only the necessary access rights to perform their duties, reducing the attack surface  
&nbsp;&nbsp;&nbsp;&nbsp;Defense in Depth - Emphasizes the use of multiple layers of security to mitigate threats even if one control fails  
&nbsp;&nbsp;&nbsp;&nbsp;Risk-based Approach - Prioritizing controls based on potential risks and vulnerabilities specific to the infrastructure to make efficient use of resources  
&nbsp;&nbsp;&nbsp;&nbsp;Lifecycle Management - Regularly reviewing, updating, and retiring controls to adapt to evolving threat landscapes  
&nbsp;&nbsp;&nbsp;&nbsp;Open Design Principle - Ensuring transparency and accountability through rigorous testing and scrutiny of infrastructure and controls  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Conduct a comprehensive risk assessment  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Align control selection with established frameworks  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Customize framework controls  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Emphasize stakeholder engagement and training  

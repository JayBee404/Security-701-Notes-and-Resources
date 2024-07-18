Extended Service Set (ESS) Configuration – Involces multiple wireless access points working together to create a unified and extended coverage area for users in a large building or facility  
Adjacent Channel Interference – Occurs when the channels selected for adjacent wireless access points do not have enough space between the channels  
Site Survey – Process of planning and designing a wireless network to provide a solution  
Heat Map – Graphical representation of the wireless coverage, the signal strength, and frequency utilization data at different locations on a map  
Wired Equivalent Privacy (WEP) – Outdated 1999 wireless security standard meant to match wired LAN security for wireless networks  
64-bit WEP – Consists of 40 bits of actual key data plus an extra 24 bits of initialization vector  
128-bit WEP – Includes 104 bits of key data and an additional 24 bits of initialization vector  
Wi-Fi Protected Access (WPA) – Introduced in 2003 as a temporary improvement over WEP while the more robust IEEE 802.11i standard was in development – Insecure because of the lack of sufficient data integrity checks in the TKIP implementation  
WPA2 – Improved data protection and network access control by addressing weaknesses in WPA version – Replaces TKIP with AES and adopted CCMP – (Counter Cipher Mode with Block Chaining Message Authentication Code Protocol)  
WPA3 – Latest version using AES encryption and introducing new features like SAE, Enhanced Open, updated cryptographic protocols, and management protection frames  

Simultaneous Authentication of Equals (SAE) – Enhances security by offering a key establishment protocol to guard against offline dictionary attacks  
Enhanced Open/Opportunistic Wireless Encryption (OWE) – Major advancement in wireless security, especially for networks using open authentication  
Cryptographic Protocol – Uses a newer variant of AES known as the AES GCMP  
Galois Counter Mode Protocol (GCMP) – Supports 128-bit AES for personal networks and 192-bit AES for enterprise networks with WPA3  
Management Protection Frames – Required to protect network from key recovery attacks  
Authentication, Authorization, and Accounting (AAA) Protocol – Plays a vital role in network security by centralizing user authentication to permit only authorized users to access network resources  
Remote Authentication Dial-In User Service (RADIUS) – Client/server protocol offering AAA services for network users  
Terminal Access Controller Access-Control System Plus (TACACS+) – Separates the functions of AAA to allow for a more granular control over processes  
Authentication Protocols – Confirms user identity for network security and authorized access  

Extensible Authentication Protocol – Authentication framework that supports multiple authentication methods  
Protected Extensible Authentication Protocol (PEAP) – Authentication protocol that secures EAP within an encrypted and authenticated TLS tunnel (server\&amp;client need certs)  
Extensible Authentication Protocol-Tunneled Transport Layer Security (EAP-TTLS) – Authentication protocol that extends TLS support across multiple platforms (server needs cert)  
Extensible Authentication Protocol-Flexible Authentication via Secure Tunneling (EAP-FAST) Developed by Cisco, it enables secure re-authentication while roaming within a network without full authentication each time  
Application Security – Critical aspect of software development that focuses on building applications that are secure by design  
Input Validation – Acts as a gatekeeper to ensure that applications only act on well-defined and uncontaminated data  
Cookies – Small pieces of data stored on the user’s computer by the web browser while browsing a website  
Secure Cookies – Transmitted over secure HTTPS connections to prevent potential eavesdroppers from intercepting the cookie data  
Static Code Analysis (SAST) – A method of debugging an application by reviewing and examining its source code before the program is ever run  
Dynamic Code Analysis – Testing method that analyzes an application while it’s running  
Fuzzing – Finds software flaws by bombarding it with random data to trigger crashes and security vulnerabilities  
Stress-Testing – Type of software testing that evaluates the stability and reliability of a system under extreme conditions  
Code Signing – Technique used to confirm the identity of the software author and guarantee that the code has not been altered or corrupted since it was signed  
Sandboxing – Security mechanism that is used to isolate running programs by limiting the resources they can access and the changes they can make to a system  
Network Access Control (NAC) – Scans devices for their security status before granting network access, safeguarding against both known and unknown devices  
Persistent Agent – A software installed on a device requesting network access  
Non-persistent Agent – Users connect to Wi-Fi, access a web portal, and click a link for login in these solutions  
Web Filtering – Technique used to restrict or control the content a user can access on the Internet  

Agent-based Web Filtering – Installing a small piece of software known as an agent on each device that will require web filtering  
Centralized Proxy – Server that acts as an intermediary between an organization’s end users and the Internet  
URL Scanning – Used to analyze a website’s URL to determine if it is safe or not to access  
Content Categorization – Websites are categorized based on content, like social media, adult content, or gambling, which are frequently restricted in workplaces  
Block Rules – Specific guidelines set by an organization to prevent access to certain websites or categories of websites  
Reputation-based Filtering – Blocking or allowing websites based on their reputation score  
DNS Filtering – Technique used to block access to certain websites by preventing the translation of specific domain names to their corresponding IP addresses  
DomainKeys Identified Mail (DKIM) – Allows the receiver to check if the email was actually sent by the domain it claims to be sent from and if the content was tampered with during transit  
Sender Policy Framework (SPF) – Email authentication method designed to prevent forging sender addresses during email delivery  
Domain-based Message Authentication, Reporting, &amp; Conformance (DMARC) – An email-validation system designed to detect and prevent email spoofing  
Email Gateway – Server or system that serves as the entry and exit point for emails  
On-Premise Email Gateway – Physical server that is located within an organization’s own data center or premises that provides an organization with full control over their email system  
Cloud-based Email Gateway – Email gateway that is hosted by third-party cloud service providers to provide greater scalability and ease of maintenance  
Hybrid Email Gateway – Used to combine the benefits of both on-premise and cloud-based gateways into a single offering  
Spam Filtering – Process of detecting unwanted and unsolicited emails and preventing them from reaching a user’s email inbox  
Endpoint Detection and Response (EDR) – Category of security tools that monitor endpoint and network events and record the information in a central database  
Data Collection (System Processes, Changes to the Registry, Memory Usage, Patterns of Network Traffic)  
Data consolidation – Sends collected data to central database for analysis  
Threat Detection – Signature and behavior based Alerts and Threat Response  

Threat Investigation  
Remediation  
File Integrity Monitoring (FIM) – Used to validate the integrity of operating system an application software files using a verification method between the current file state and a known, good baseline  
Extended Detection and Response (XDR) – Security strategy that integrates multiple protection technologies into a single platform to improve detection accuracy and simplify the incident response process  
User Behavior Analytics (UBA) – Deploys big data and machine learning to analyze user behaviors for= detecting security threats  
Protocol – Set of rules or procedures for transmitting data between electronic devices  
Telnet – Application layer protocol that allows a user on one computer to log onto another computer that is part of the same network  
Secure Shell (SSH) – Network protocol for securely connecting and communicating with remote devices and systems over an unsecured network  
Port – Logical construct that identifies specific processes or services in a given system  
Transport Method – Refers to the way data is moved from one place to another, usually using either TCP or DDP to transmit the data  
TCP – Connection-oriented protocol that ensures data is delivered without any errors  
UDP – Connectionless protocol that doesn’t guarantee data delivery  

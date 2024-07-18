Denial of Service (DoS) - Used to describe an attack that attempts to make a computer or server's resources unavailable  
&nbsp;Flood Attack - Specialized type of DoS which attempts to send more packets to a single server or host  
&nbsp;&nbsp;Ping Flood - A variety of Flood Attack in which a server is sent with too many pings (ICMP echo)  
&nbsp;&nbsp;SYN Flood - An attacker will initiate multiple TCP sessions but never complete the three-way handshake  
&nbsp;Permanent Denial of Service (PDoS) - An attack which exploits a security flaw by reflashing a firmware, permanently breaking networking device  
&nbsp;Fork Bomb - A large number of processes is created to use up a computer's available processing power  
Distributed Denial of Service (DDoS) - More machines are used to launch an attack simultaneously against a single server to create denial of service condition  
&nbsp;DNS Amplification Attack - Specialized DDoS that allows an attacker to initiate DNS requests from a spoof IP address to flood a website  
Blackhole/Sinkhole - Identifies attacking addresses and sends them to a null address server  

Domain Name System (DNS) - Responsible for translating human-friendly domain names into IP addresses that computers can understand  
&nbsp;DNS Cache Poisoning - Involves corrupting the DNS cache data of a DNS resolver with false information  
&nbsp;DNS Amplification Attack - The attacker overloads a target system with DNS response traffic by exploiting the DNS resolution process  
&nbsp;DNS Tunneling - Uses DNS protocol over port 53 to encase non-DNS traffic, trying to evade firewall rules for command control or data exfiltration  
&nbsp;Domain Hijacking - Altering a domain name's registration without the original registrant's consent  
&nbsp;DNS Zone Transfer Attack - The attacker mimics an authorized system to request and obtain the entire DNS zone data for a domain  
 	
Directory Traversal - A type of injection attack that allows access to commands, files, and directories, either connected to web document root directory or not  
&nbsp;May hide directory traveral attempts by using %2e%2e%2f to represent ../  
&nbsp;File Inclusion - Allows an attacker to either download files from an arbitrary location or upload an executable or script file to open a backdoor  
&nbsp;&nbsp;Remote File Inclusion - Occurs when an attacker tries to execute a script to inject a remote file  
&nbsp;&nbsp;Local File Inclusion - Occurs when an attacker tries to add a file that already exists  

Arbitrary Code Execution - A vulnerability that allows an attacker to run a code or module that exploits a vulnerability  
Remote Code Execution - A type of arbitrary code execution that allows an attacker to transmit code from a remote host  
Privilege Escalation - Occurs when a user accesses or modifies specific resources that they are not entitled to normally access  
&nbsp;Vertical Privilege Escalation - From normal level user to higher level  
&nbsp;Horizontal Privilege Escalation - From one user to another of generally the same level  
Rootkit - A class of malware that modifies system files, often at the kernel level, to conceal its presence  

Replay Attack - Type of network-based attack that involves maliciously repeating or delaying valid data transmissions  
Session Tokens - Unique data pieces that prevent session replay by attackers  

Session Management - A fundamental security compnent that enables web applications to identify a user  
&nbsp;Cookies - Allow web applications to retain information about the users  
Session Hijacking - A type of spoofing attack where the host is disconnected and replaced by the attacker  
&nbsp;Session Prediction - An attacker attempts to predict the session token to hijack that session  
&nbsp;Cookie Poisoning - Modifying the contents of a cookie to be sent to a client's browser and exploit the application vulnerabilities  

On-path Attack - An attack where the penetration tester puts the workstation logically between two hosts during the communication  
&nbsp;Replay - Occurs when an attacker captures a valid data which is then repeated immediately or delayed and then repeated  
&nbsp;Relay - Occurs when attackers insert themselves in between two hosts and become part of the conversation  
&nbsp;&nbsp;SSL Stripping - Tricking the encryption application with an HTTP connection instead of an HTTPS connection  
&nbsp;&nbsp;Downgrade Attack - Occurs when an attacker attempts to have a client or server abandon its higher security mode  

LDAP - A protocol for access and maintenance of distributed directory information services  
&nbsp;LDAP Injection - An attack in which LDAP statements, typically created by user input, are fabricated  
Command Injection - A threat actor is able to execute arbitrary shell commands via a vulnerable web application  
Process Injection - A method of executing arbitrary code in the address space of a separate live process  

Indicators of Compromise (IoC) - Data pieces that detect potential malicious acitivity on a network or system  
&nbsp;Account Lockout - Dignals a compromise when it's triggered by numberous failed login attempts  
&nbsp;Concurrent Session Usage - One user having multiple active sessions  
&nbsp;Blocked Content - When users try to access or download content that security measures have prevented  
&nbsp;Impossible Travel - When suspicious logins occur from distand locations in a timeframe that makes physical travel between them impossible  
&nbsp;Resource Consumption - Unusual resource spikes can signal a compromise  
&nbsp;Resource Inaccessability - Inability to access certain resources, such as files, databases, or network services  
&nbsp;Out-of-cycle Logging - Logging events happening at odd times when no one is supposed to be active  
&nbsp;Missing Logs - Attackers delete logs to cover their tracks and hinder investigations  
&nbsp;Articles or Documents on Security Breach - Attackers may publicly announce their hacks to brag about their abilities or harm the organization's reputation  

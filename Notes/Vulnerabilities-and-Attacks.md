Vulnerabilities - Weaknesses or flaws in hardware, software, configurations, or processes within a computer system, network, or application  
Attacks - Deliberate actions or activities carried out by threat actors with the intent to exploit vulnerabilities  
Zero-Day Vulnerability - Type of software or hardware vulnerability that is discovered and exploited by malicious actors before a patch is released  
SQL Injection - Type of cyberattack that exploits vulnerabilities in web applications or databases  
XML Injection - Security vulnerability that targets web applications that process XML data  
Cross-Site Scipting (XSS) - Web security vulnerability where malicious scripts are injected into web pages viewed by other users  
Cross-Site Request Forgery (XSRF) - Web security exploit taht focuses on an attacker who attempts to trick a user  
Buffer Overflow - Software vulnerability that occurs when a program writes more data to a memory buffer  
Race Condition - Software vulnerability that occurs when multiple processes or threads in a concurrent system access shared resources or data simultaneously  

Hardware Vulnerabilities - Security flaws or weaknesses ingerent in a device's physical components or design that can be exploited to compromise the integrity, confidentiality, or availability of the system and its data  
Firmware - Specialized form of software stored on hardware device, like a router or a smart thermostat that provides low-level control for the device's specific hardware  
End-of-Life Systems - Refer to hardware or software products that have reached the end of their life cycle  
Legacy Systems - Outdated computing software, hardware, or technologies that have been largely superseded by newer and more efficient alternatives  
Unsupported Systems - Hardware or software products that no longer receive official technical support, security updates, or patches from their respective vendors or developers  
Unpatched System - Device, application, or piece of software that has not been updated with the latest security patches so that it remains vulnerable to known exploits and attacks  
Hardware Misconfiguration - Occurs when a device's settings, parameters, or options are not optimally set up, and this can cause vulnerabilities to exits, a decrease in performance, or unintended behavior of decies or systems  
&nbsp;Hardening - Involves tightening the security of a system  
&nbsp;Patching - Involves the regular updating of the software, firmware, and applications with the latest security patches  
&nbsp;Configuration Enforcement - Used to ensure that all devices and systems adhere to a standard secure configuration  
&nbsp;Decommissioning - Means that the system is retired and removed from the network  
&nbsp;Isolation - Used to limit the potential damage that might occur from a potential security breach  
&nbsp;Segmentation - Used to divide the network into segments  
 	
Bluetooth - Wireless technology standard used for exchanging data between fixed and mobile devices over short distances without the need for an Internet connection  
&nbsp;Insecure Device Pairing - Occurs when Bluetooth devices establish a connection without proper authentication  
&nbsp;Device Spoofing - Occurs when an attacker impersonates a device to trick a user into connecting  
&nbsp;On-Path Attack - Exploits Bluetooth protocol vulnerabilities to intercept and alter communications between devices without either party being aware  
&nbsp;&nbsp;Bluejacking - Sending a message to a device   
&nbsp;Bluesnarfing - Gaining unauthorized access to a system through bluetooth  
&nbsp;Bluebugging - Bluesnarfing++ , making calls accessing the internet etc.  
&nbsp;Bluesmack - DoS attack to the device through Bluetooth  
&nbsp;Blueborne - Attacks multiple devices   

Sideloading - The practice of installing applications on a device from unofficial sources which actually byppasses the device's default app store  
Jailbreaking/Rooting - Process that gives users escalated privileges on the devices and allows users to circumvent the built-in security measures provided by the devices  
Mobile Device Management (MDM) Solution - Used to conduct patching of the devices by pushing any necessary updates to the devices to ensure that they are always equipped with the latest security patches  

Zero-Day Vulnerabilitiy - Any vulnerability that's discovered or exploited before the vendor can issue a patch for it  
Zero-Day Exploit - Any unknown exploit in the wild that exposes a previously unknown vulnerability in the software or hardware  

Unpatched Systems - Operating systems that have not been updatesd with the latest security patches or fixes  
Zero-day Vulnerabilities - Represent vulnerabilities in software or hardware that are unknown to the developer and in essence, they are newly discovered vulnerabilities that have not been publicaly disclosed yet  
Misconfiguration - Occurs when the system's settings are not properly configured and this leaves the system vulnerable to exploitation  
Data Exfiltration - Unauthorized data transfers from within an organization to an external location  
Malicious Updates - Occur when an attacker has been able to craft a malicious update to a well-known and trusted program in order to compromise the systems of the program's end users  

Code Injection - The insertion of additional information or code through a data input form from a client to an application  
Extensible Markup Language (XML) - Used by web applications for authentication, authroization, and other types of data exchange  
XML Bomb (Billion Laughs Attacks) - XML encodes entities that expand to exponential sizes, consuming memory on the host and potentially crashing it  
XML External Entity (XXE) - An attack that embeds a request for a local resource  

Cross-Site Scripting (XSS) - Injects a malicious script into a trusted site to compromize the site's visitors  
xss-game.appspot.com  
&nbsp;Non-persistent XSS - This type of attack only occurs when it's launched and happens once  
&nbsp;Persistent XSS - Allows an attacker to insert code into the backend database used by that trusted website  
&nbsp;&nbsp;Document Object Model (DOM) XSS - Exploits the client's web browser using client-side scripts to modify the content and layout of the web page  
Session Management - Enables web applications to uniquely identify a user across several different actios and requests  
Cookie - Text file used to store information about a user when they visit a website  
&nbsp;Non-persistent - Known as a session cookie, which resides in memory and is used for a very short period of time  
&nbsp;Persistent - Stored in the browser cache until either deleted by a user or expired  
Session Hijacking - Type of spoofing attack where the attacker disconnects a host and then replaces it with his or her own machine by spoofing the original host IP  
Session Prediction - Type of spoofing attack where the attacker attempts to predict the session token in order to hijack the session  
Cross-Site Request Forgery (XSRF) - Malicious script is used to exploit a session started on another site within the same browser  

Buffer Overflow - Occurs when data exceeds allocated memory, potentially enabling unauthorized access or code execution  
Stack - A memory region where a program stores the return addresses from function calls  
&nbsp;Smashing the Stack - Occurs when an attacker can execute their malicious code by overwriting the return address  
Address Space Layout Randomization (ASLR) - A security measuire that randomized memory addresses making buffer overflow attacks harder for attackers  

Race Condition - Software vulnerability where the outcome depends on the timing of events not matching the developer's intended order  
Dereferencing - Software vulnerability that occurs when the code attempts to remove the relationship between a pointer and the thing that pointer was pointing to in the memory  
Time-of-Check (TOC) - Type of race condition where an attacker can alter a system resource after an application checks its state but before the operation is performed  
Time-of-Use (TOU) - Type of race condition that occurs when an attacker can change the state of a system resource between the time it is checked and the time it is used  
Time-of-Evaluation (TOE) - Type of race condition that involves the amnipulation of data or resources during the time window when a system is making a decision or evaluation  
Mutex - Mutually exclusive flag that acts as a gatekeeper to a section of code so that only one thread can be processed at a time  
Deadlock - Occurs when a lock remains in place because the process it's waiting for is terminated, crashes, or doesn't finish properly, despite the processing being complete  

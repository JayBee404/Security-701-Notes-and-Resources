Security Architecture - Design, structure, and behavior of an organizaiton's information security environment  
On-Premise - Traditional method of setting up infrastructure and services locally, within an organization's own premises   
Cloud Computing - Involves delivering computing services over the Internet  
Serverless - Computing model where the cloud provider dynamically manages the allocation and provisioning of servers  
Software-Defined Networking (SDN) - Network management method that allows dynamic and efficient network configuration to improve performance and monitoring  
Infrastrucutre as Code (IaC) - IT setup where developers use software to manage and provision the technology stack for an application  
Internet of Things (IoT) - Network of physical devices, vehicles, and appliances, with sensors, software, and network connectivity  
Industrial Control Systems (ICS) - Types of control systems used in industrial production  
Supervisory Control and Data Acquisition (SCADA) - Used to control and monitor physical processes  

Responsibility Matrix - Outlines the division of responsibilities between the cloud service provider and the customer  
Third-party Vendors - Provide specialized services that enhance the functionality, security, and efficiency of cloud solutions  
Hybrid Solutions - Combine on-premise infrastructure, private cloud services, and public cloud services  
On-Premise Solutions - Computing infrastructure that's physically located on-site at a business  
&nbsp;&nbsp;&nbsp;&nbsp;Availability - System's ability to be accessed when needed  
&nbsp;&nbsp;&nbsp;&nbsp;Resilience - System's ability to revocer from failures and continue to function   
&nbsp;&nbsp;&nbsp;&nbsp;Cost - It's essential to consider both the immediate and long-term costs of cloud adoption  
&nbsp;&nbsp;&nbsp;&nbsp;Responsiveness - Speed at which the system can adapt to changes in demand  
&nbsp;&nbsp;&nbsp;&nbsp;Scalability - System's ability to handle increased workloads  
&nbsp;&nbsp;&nbsp;&nbsp;Ease of Deployment - Cloud services are easier to deploy than on-premise solutions  
&nbsp;&nbsp;&nbsp;&nbsp;Risk Transference - When using the cloud services, some risks are transferred to the provider  
&nbsp;&nbsp;&nbsp;&nbsp;Ease of Recovery - Cloud services often offer easy data recovery and backup solutions  
&nbsp;&nbsp;&nbsp;&nbsp;Patch Availability - Cloud service providers regularly release patches to fix vulnerabilities  
&nbsp;&nbsp;&nbsp;&nbsp;Inability to Patch - Businesses might not be able to apply patches due to compatibility issues  
&nbsp;&nbsp;&nbsp;&nbsp;Power - Customers don't have to worry about power consumption  
&nbsp;&nbsp;&nbsp;&nbsp;Compute - Amount of computational resources that a customer can use  

Shared Physical Server Vulnerabilities - Can lead to vulnerabilities if one user's data is compromised  
Inadequate Virtual Enviornment Security - Can lead to unauthorized access, data breaches, and other security incidents  
User Access Management - Can lead to unauthorized access to sensitive data and systems  
Lack of up-to-date Security Measures - Can lead to leaving the system vulnerable to new threats  
&nbsp;&nbsp;&nbsp;&nbsp;Keeping software and Systems Patched - Regularly Reviewing and Updating Security Policies - Staying informed about the latest Threats and Security Best Practices  
Single Points of Failure - Can lead to a complete system outage affecting all users  
&nbsp;&nbsp;&nbsp;&nbsp;Multiple Servers, Data Centers and Cloud Providers  
Weak Authentication and Encryption Practices - Can lead to allowing unauthorized users to gain access to cloud systems  
Unclear Policies - Lack of clear guidelines or procedures for various security aspects  
Data Remnants - Residual data left behind after deletion or erasure processes  

Virtualization - Technology that allows for the emulation of servers  
Containerization - Lightweight alternative to full machine virtualization  
Type 1 Hypervisor - Knows as a bare metal or native hypervisor, it runs directly on the host hardware and functions similarly to an operating system  
Type 2 - Operates within a standard operating system, such as Windows, Mac, or Linux  
VM Escape - Occurs when an attacker is able to break out of one of these normally isolated virtual machines  
Privilege Elevation - Occurs when a user is able to gain the ability to run fuctions as a higher level user  
Live Migration of Virtual Machines - when a virtual machine needs to move from one physical host to another  
Resource Reuse - Concept in computing where system resources like memory or processing power are reused  

Serverless - Model where the responsibility of managing servers, databases and some application logic is shifted away from developers  
Vendor Lock-in - One of the most significant risks of serverless computing   

Microservices - A software architecture where large applications are broken down into smaller and independent services  

Physical Separation/Air Gapping - Isolation of a network by removing any direct or indirect connections from other networks  
Logical Separation - Creates boundaries within a network, restricting access to certain areas  

Software-Defined Networking (SDN) - Enables efficient network configuration to improve performance and monitoring   
&nbsp;&nbsp;&nbsp;&nbsp;Data Plane - Also called the forwarding plane that is responsible for handling packets and makes decisions based on protocols  
&nbsp;&nbsp;&nbsp;&nbsp;Control Plane - The brain of the network that decides where traffic is sent and is centralized in SDN  
&nbsp;&nbsp;&nbsp;&nbsp;Application Plane - The plane where all network applications interacting with the SDN controller reside  

Infrastructure as Code (IaC) - A method in which IT infrastructures are defined in code files that can be versioned, tested, and audited  
&nbsp;&nbsp;&nbsp;&nbsp;YAML -JSON - HCL  
Snowflake System - A configuration that lacks consistency that might introduce risks, so it has to be eliminated  
Idempotence - The ability of an operation to produce the same results as many times as it is executed  

Centralized - All the computing fuctions are coordinated and managed from a single location or authority   
Decentralized - Computing functions are distributed across multiple systems or locations   

Internet of Things (IOT) - Refers to the network of physical items with embedded systems that enables connection and data exchange  
&nbsp;&nbsp;&nbsp;&nbsp;Hub - The central point connecting all IoT devices and sends commands to them  
&nbsp;&nbsp;&nbsp;&nbsp;Smart Devices - Everyday objects enhanced with computing capabilities and Internet connectivity   
&nbsp;&nbsp;&nbsp;&nbsp;Wearables - Subset of smart devices designed to be worn on the body   
&nbsp;&nbsp;&nbsp;&nbsp;Sensors - Detect changes in the environment and transform them into analyzable data  

Embedded System - Specialized computing component designed to perform dedicated functions within a larger structure  
Real-Time Operating System (RTOS) - Ensures data processing in real-time and is crucial for time-sensitive applications  
&nbsp;&nbsp;&nbsp;&nbsp;Network Segmentation - Divides a network into multiple segments or subets, limiting potential damage in case of a breach  
&nbsp;&nbsp;&nbsp;&nbsp;Wrappers - Show only the entry and exit points of the data when travelling between networks  
&nbsp;&nbsp;&nbsp;&nbsp;Firmware Code Control - This can be achieved through secure coding practices, code reviews, and automated testing  
&nbsp;&nbsp;&nbsp;&nbsp;Inability to Patch - Strategies like over-the-air (OTA) updates, where patches are delivered and installed remotely, can be applied  

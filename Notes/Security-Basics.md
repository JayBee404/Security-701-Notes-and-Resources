Information Security - Act of protecting data and information from unauthorized access, unlawful modification and disruption, disclosure, and corruption, and destruction  
Information Systems Security - Act of protecting the systems that hold and process the critical data  

CIA Triad - Confidentiality, Integrity, and Accessability  
&nbsp;&nbsp;&nbsp;&nbsp;Confidentiality - Ensures that information is only accessible to those with the appropriate authorization  
&nbsp;&nbsp;&nbsp;&nbsp;Integrity - Ensures that data remains accurate and unaltered unless modification is required  
&nbsp;&nbsp;&nbsp;&nbsp;Availability - Ensures that information and resources are accessible and functional when needed by authorized users  

Non-repudiation - guarenteeing that a specific action or event has taken place and cannot be denied by the parties involved  

AAA of Security - Authentication, Authorization, Accounting  
&nbsp;&nbsp;&nbsp;&nbsp;Authentication - Process of verifying the identity of a user or system  
&nbsp;&nbsp;&nbsp;&nbsp;Authorization - Defines what actions or resources a user can access  
&nbsp;&nbsp;&nbsp;&nbsp;Accounting - Act of tracking user activities and resource usage, typically for audit or billing purposes  

Security Controls - Measures or mechanisms put in place to mitigate risks and protect the confidentiality, integrity, and availability of information systems and data  

Zero Trust - Security model that operates on the principle that no one, whether inside or outside the organization, should be trusted by default
Control Plane - Consists of the adaptive identity, threat scope reduction, policy-driven access control, and secured zones - responsible for making decisions about how data should be forwarded in a network -routing protocols, device discovery  
Data Plane - Focused on the subject/system, policy engine, policy administrator, and establishing policy enforcement points - responsible for the actual forwarding actions based on control plane protocol - determines appropriate interfaces for packets  

Threat - Anything that could cause harm, loss, damage, or compromise to information technology systems - ex. Natural disasters, cyber-attacks, data integrity breaches, disclosure of confidential information - outside of control  
Vulnerability - Any weakness in the system design or implementation - ex. Software bugs, misconfigured software, improperly protected network devices, missing security patches, lack of physical security - inside of control  
Risk = intersection of threats and vulnerabilities  
Risk management - Finding different ways to minimize the likelihood of an outcome occurring and achieve the desired outcomes  

Confidentiality - Refers to the protection of information from unauthorized access and disclosure  
Encryption - Process of converting data into code to prevent unauthorized access  
Access Controls - Ensure only authorized personnel can access certain types of data  
Data Masking - Method that involves obscuring data within a database to make it inaccessible for unauthorized users while retaining the real data's authenticity and use for authorized users - ex. last 4 of soc number  
Physical Security Measures - Used to ensure confidentiality for physical types of data and for digital information contained on servers and workstations  
Training and Awareness - Conducting regular training on the security awareness best practices that employees can use to protect the organization's sensitive data  
Encryption == Confidentiality  

Integrity - Helps to ensure information and data remain accurate and unchanged from their original state unless intentionally modified by an authorized individual - Integrity = accuracy and trustworthiness  
Ensure Data Accuracy, Maintain Trust, Ensure System Operability  
Hashing - Process of converting data into a fixed-size value  
Digital Signatures - Use encryption to ensure integrity and authenticity - encrypt hash digest and once decrypted by recieving party, they will compare to the original hash to ensure no tampering has taken place  
Checksums - Method to verify the integrity of data during transmission  
Access Controls - Ensure that only authorized individuals can modify data and reduce the risk of unintentional or malicious alterations  
Regular Audits - Involve reviewing logs and operations to ensure that only authorized changes have been made and any discrepancies are addressed  

Availability - Used to ensure that information, systems, and resources are accessible and operational when needed by authorized users - Availability == Redundancy  
Ensures business continuity - Maintaining Customer Trust - Upholding an Organizations Reputation  
Redundancy - Duplication of ciritical components or functions of a system with the intention of enhancintg its reliability  
Server Red - Data Red - Network Red - Power Red  
Server Redundancy - Involves using multiple servers in a load balance so that if one is overloaded or fails, the other servers can take over the load to continue supporting end users  
Data Redundancy - Storing duplicate data in multiple places  
Network Redundancy - Ensures that if one network path fails, the data can travel through another route  
Power Redundancy - Involves using backup power sources to ensure that an organization's systems remain operational during periods of power disruption or outages within a local service area  

Non-repudiation - Focused on providing undeniable proof in digital transacitons  
Digital Signature - Created by first hashing a particular message or communication to be digitally signed and encrypting the hash digest with the user's private key using asymmetric encryption  
Confirming Authenticity - Ensuring Integrity - Providing Accountability  

Authentication - Security measure that ensures individuals or entities are who they claim to be during a communication or transaction  
Something you know (Knowledge factor) - Relies on information that a user can recall (passwd)  
Something you have (Posession factor) - Relies on the user presenting a physical item to authenticate themselves (One-time sms code)  
Something you are (Inherence Factor)  - Relies on the user providing a unique physical or behavioural characteristic of the person to validate that they are who they claim to be (biometric)  
Something you do (Action Factor) - Relies on the user conducting a unique action to prove who they are (behavioral analysis)  
Somewhere you are (Location factor) - Relies on the user being in a vertain geographic location before access is granted (Location service and check)  
MFA - Security process that requires users to provide multiple methods of identification to verify their identity  

Authorization - Permissions and privileges granted to users or entities after they have been authenticated - Set of rules and policies that are used to dictate what actions users can perform once authenticated  

Accounting - Security measure that ensures all user activites are properly tracked and recorded  
Logging in - Accessing files - Modifying configs - Download/install software - Attempting unauthorized actions on systems and networks  
Audit Trail - provides a chronological record of all user activities that can be used to trace changes, unauthorized accessm or anomalies back to a specific user or point in time  
Regulatory compliance - Maintains a comprehensive record of all the users' activities  
Forensic Analysis - Uses detailed accounting and event logs that can help cybersecurity experts understand what happened, how it happened, and how to prevent similar incidents from occurring again in the future  
Resource optimization - Organizations can optimize system performance and minimize costs by tracking resource utilization and allocation decisions  
User accountability - Thorough accounting system ensures users' actions are monitored and logged, deterring potential misuse and promoting adherence to the organization's policies  
Syslog servers - Used to aggregate logs from various network devices and systems so that system admins can analyze them to detect patterns or anomalies in the organization's systems  
Network Analyzers - Used to capture and analyze network traffic to gain detailed insights into all the data moving within a network  
Security Information and Event Management (SIEM) - Provides real-time analysis of security alerts generated by various hardware and softwware infrastuctures in an organization  

Technical Controls - The technologies, hardware, and software mechanisms that are implemented to manage and reduce risks (AV, Firewalls, Encryption, IDS)  
Managerial (Administrative) Controls - Involve the strategic planning and givernance side of security (Security policies, training programs, IR strats, risk assessment) - overall decision making  
Operational Controls - Procedures and measures that are designed to protect data on a day-to-day basis and are mainly governed by internal processes and human actions (passwd change timeframe, backup procedures, account reviews, user training) - day-to-day process control  
Physical Controls - Tangible, real-world measures taken to protect assets (cameras, gates)  

Preventative Controls - Proactive measures implemented to thwart potential security threats or breaches - ex. firewalls  
Deterrent Controls - Aim to discourage potential attackers by making the effort seem less appealing or more challenging - ex. warning signs or banners on a website proclaiming monitoring  
Detective Controls - Monitor and alert organizations to malicious activities as they occur or shortly thereafter - ex. IDS , monitors activity and alerts admins of suspicious activity  
Corrective controls - Mitigate any potential damage and restore the systems to their normal state - ex. quarantine and removal of malware, using a backup after a system is corrupted   
Compensating Controls - Alternative measures that are implemented when primary security controls are not feasible or effective - ex. unable to use WPA3 on legacy system, use WPA2 + VPN to compensate  
Directive Controls - Often rooted in policy or documentation and set the standards for behavior within an organization - ex. Acceptable Use Policy  

Gap analysis - Process of evaluating the differences between an organization's current performance and its desired performance  
&nbsp;&nbsp;&nbsp;&nbsp;1. Define scope of analysis  
&nbsp;&nbsp;&nbsp;&nbsp;2. Gather data on current state of the organization  
&nbsp;&nbsp;&nbsp;&nbsp;3. Analyze the data to identify the gaps  
&nbsp;&nbsp;&nbsp;&nbsp;4. Develop a plan to close the gaps  
Technical Gap Analysis - Involves evaluating an organization's current technical infrastructure and identifying any areas where it falls short of the technical capabilities required to fully utilize their security solutions  
Business Gap Analysis - Involves evaluating an organization's current business processes and identifying any areas where they fall short of the capabilities required to fully utilize cloud-based solutions  
Plan of Action and Milestones (POA&M) - Outlines the specific measures to address each vulnerability, allocate resources, and set up timelines for each remediation task that is needed  

Zero Trust - Demands verification for every device, user, and transaction within the network, regardless of its origin  
Control Plane - The overarching framework and set of compnonents responsible for defining, managing, and enforcing the policies related to user and system access within an organization  
Adaptive Identity - Use adaptive identities that rely on real-time validation that takes into account the user's behavior, device, location, and other similar factors   
Threat Scope Reduction - Limit the users' access to only what they need for their work tasks because this drastically reduces the network's potential attack surface  
Policy-Driven Access Control - Entails developing, managing, and enforcing user access policies based on their roles and responsibilities  
Secured Zones - Isolated environments within a network that are designed to house sensitive data  
Data Plane - Ensures that the policies and procedures are properly executed  
Subject/System - Refers to the individual or entity attempting to gain access  
Policy Engine - Cross-references the access request within its pre-defined policies  
Policy Administrator - Used to establish and manage the access policies  
Policy Enforcement Point - Allow or restrict access, and it will effectively act as a gatekeeper to the sensitive areas of the systems or networks  

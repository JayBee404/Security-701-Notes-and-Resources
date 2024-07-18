Hardening - Process of enhancing the security of a system, application or network  

Least Functionality - A process of configuring a workstation or server with only essential appliations and services for the user  
Secure Baseline Image - A standardized workstation setup, including OS, essential applications, and strict policies in coroporate networks  
Allowlisting - A security measure that permits only approved applications to run on an operating system  
Block/Denylisting - Entails preventing listed applications from running, allowing all others to execute  

Services - Background applications that operate within the OS, executing a range of tasks  

Trusted Operating System (TOS) - Designed to provide a secure computing environment by enforcing stringent security policies that usually rely on mandatory access controls  
Evaluation Assurance Level (EAL) - Based on a set of predefined security standard and certification from the Common Criteria for Information Technology Security Evaluation  
&nbsp;Mandatory Access Control (MAC) - Access permissions are determined by a policy defined by the system administrators and enforced by the operating system  
&nbsp;SELinux (Security-Enhanced Linux) - Set of controls that are installed on top of another Linux distribution like CentOS or Red Hat Linux  
&nbsp;Trust Solaris - Offers secure, multi-level operations with MAC, detailed system audits, and data/process compartmentalization  
 	
Hotfix - A software patch that solves a security issue and should be applied immediately after being tested in a lab environment  
Update - Provides a system with additional functionality, but it does not usually provide any patching of security related issues  
Service Pack - Includes all the hotfixes and updates since the release of the operating system  
&nbsp;1. Assign a dedicated team to track vendor security patches  
&nbsp;2. Establish automated system-wide patching for OS and applications  
&nbsp;3. Include cloud resources in the patch management  
&nbsp;4. Categorize patches as urgent, important, or non-critical for prioritization  
&nbsp;5. Create a test environment to verify critical patches before productioon deployment  
&nbsp;6. Maintain comprehensive patching logs for program evaluation and monitoring  
&nbsp;7. Establish a process for evaluating, testing, and depoying firmware updates  
&nbsp;8. Develop a technical process for deploying approved urgent patchs to production  
&nbsp;9. Periodically assess non-critical patches for combined rollout  

Patch Management - Planning, testing, implementing and auditing of software patches  
&nbsp;Planning - Creating policies, procedures, and systems to track and verify patch compatibility  
&nbsp;&nbsp;Testing - Verify through test environments that the patch doesn't break existing infrastructure  
&nbsp;Implementation - Manually or automatically deploy the patch to all required systems (Microsoft Endpoint Config Manager)  
Cisco UCS Manager - Centralized resource and device management, including frimware for server network interfaces and devices  

Group Policy - Set of rules or policies that can be applied to a set of users or computer accounts within an operating system  
Security Template - A group of policies that can be loaded through one procedure  
Baselining - Process of measuring changes in the network, hardware, or software environment  

Mandatory Access Control (MAC) - System-enforced access control machanism that's based on subject clearance and the object labels  
Context-based Permissions - Permission schemes that are defined by various properties for a given file or process  
Discretionary Access Control (DAC) - Each object has a list of entities that are allowed to access it  
SELinux - Default context-based permission scheeme that's included inside of CentOS and Red Hat Enterprise Linux  
&nbsp;User - Defines what users can access an object  
&nbsp;Role - Defines what roles can access a given object  
&nbsp;Type - Groups objects together that have similar secuirty requirements or characteristics  
&nbsp;Level - Used to describe the sensitivity level of a given file, directory, or process  
&nbsp;&nbsp;Disbled Mode - SELinux is essentially turned off, and so MAC is not going to be implemented  
&nbsp;&nbsp;Enforcing Mode - All the SELinux security policies are being enforced  
&nbsp;&nbsp;Permissive Mode - SELinux is enabled, but the security policies are not enforced  
 	 	
Data Encryption - Process of converting data into a secret code to prevent unauthorized access  
&nbsp;Full-disk Encryption - Encrypts the entire hard drive to protect all the data being stored on it  
&nbsp;Partition Encryption - Similar to full-disk encryption, but it is only applied to a specific partition on the storage device  
&nbsp;&nbsp;VeraCrypt - Users can selectively encrypt partitions, like sensitive documents, while leaving the OS partition unencrypted  
&nbsp;Volume Encryption - Used to encrypt a set space on the storage medium, creating an encrypted container that can house various files and folders  
&nbsp;File-level Encryption - Used to encrypt an individual file instead of an entire partition or an entire disk drive  
&nbsp;Database Encryption - Secures the entire database, extending to multiple storage devices or cloud storage, similar to full-disk encryption  
&nbsp;&nbsp;SQL Server Transparent Data Encryption (TDE) - Auto-encrypts the entire database without needing application changes, as the system handles encryption and decryption  
&nbsp;Record-level Encryption - Used to encrypt individual records or rows within a database  

Secure Baseline - Standard security configuration applied to guarantee minimum security for a system, network, or application  
&nbsp;1. Establish a secure baseline  
&nbsp;2. Deploy secure baseline across all of the organization's digital assets  
&nbsp;3. Maintain the secure baseline on all assets  

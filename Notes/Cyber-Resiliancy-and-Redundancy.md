Cyber Resilience - Entity's ability to continuously deliver the intended outcome despite adverse cyber events  
Redundancy - Involves having additional systems, equipment, or processes to ensure continued functionality if the primary ones fail  
&nbsp;&nbsp;&nbsp;&nbsp;Data Redundancy - Achieved by having redundant storage devices all working together to protect data  
&nbsp;&nbsp;&nbsp;&nbsp;Capacity Planning - Strategic process that organizations use to ensure having the necessary resources  

High Availability - The ability of a service to be continuously available by minimizing the downtime to the lowest amount possible  
Uptime - The number of minutes or hours that the system remains online over a given period, and this uptime is usually expressed as a percentage  
Load Balancing - The process of distributing workloads across multiple computing resources  
Clustering - The use of multiple computers, multiple storage devices, and redundant network connections that alll work together as a single system to provide high levels of availability, reliability, and scalability  
Redundancy - The duplication of critical components or functions of a system with the intention of increasing the reliability of the system  

Redundant Array of Independent Disks (RAID) - Combines multiple physical storage devices into a recognized single logical storage device  
&nbsp;&nbsp;&nbsp;&nbsp;RAID 0 - Provides data striping across multiple disks to increase performance  
&nbsp;&nbsp;&nbsp;&nbsp;RAID 1 - Mirrors data for redundancy across two drives or SSDs  
&nbsp;&nbsp;&nbsp;&nbsp;RAID 5 - Stripes data with parity, using at least three storage devices  
&nbsp;&nbsp;&nbsp;&nbsp;RAID 6 - Uses data striping across multiple devices with two pieces of parity data  
&nbsp;&nbsp;&nbsp;&nbsp;RAID 10 - Combines RAID 1 and RAID 0, featuring mirrored arrays in a striped setup  
Failure-resistant - Use of redundant storage to withstand hardware malfunctions without data loss  
Fault-tolerant - Use of RAID 1, 5, 6, and 10 for uniterrupted operation during hardware failures  
Disaster-tolerant - Protects data from catastrophic events  

Capacity Planning - Crucial strategic planning to meet future demands cost-effectively  

Surge - A samll and unexpected increase in the amount of voltage that is being provided  
Spike - A short transient voltage that is usually caused by a short circuit, a tripped circuit breaker, a power outage, or a lightning strike  
Sag - A small and unexpected decrease in the amouont of voltage that is being provided  
Undervoltage Event - Occurs when the voltage is reduced to lower levels and usually occur for a longer period of time  
Power Loss Event - Occurs when there is a total loss of power for a given period of time  
Line Conditioner - Used to overcome and minor fluctuations in the power being received by the given system  
Uninterruptible Power Supply (UPS) - A device that provides emercgency power to a system when the normal input power source has failed  
Generator - Machine that converts mechanical energy into electrical energy for use in an external circuit throught the process of electromagentic induction  
Power Distribution Center (PDC) - Acts as a central hub where power is received and then distributed to all systems in the data center  

Data Backup - The process of creating duplicate copies of digital information to protect agfainst data loss, corruption, or unavailability  
&nbsp;&nbsp;&nbsp;&nbsp;Offsite backup - The practice of storing duplicate copes of data at a geographically separate location from the primary data source to provide protection against physical disasters and to ensure data continuity  
&nbsp;&nbsp;&nbsp;&nbsp;Encryption on backups - Fundamental safefuard that protects the backup data from unauthorized access and potential breaches  
Snapshots - Point-in-time copies of the data that capture a consistent state that is essentially a frozen in time copy of the data   
Recovery - Used to regain access to the data in the event of a data loss or system failure  
Replication - Making real-time, or near-real-time, copies of the data  
Journaling - Maintaining a meticulous record of every change made to an organization's data over time  

Continuity of Operations Plan - Ensures an organization's ability to recover from disruptive events or disasters  
Business Continuity Planning (BCP) - Addresses responses to disruptive events  
Disaster Recovery Plan (DRP) - Considered as a subset of SCP, it focuses on how to resume operations sqiftly after a disaster  

Redundant Site - Alternative sites for backup in case the primary location encounters a failure or interruption  
&nbsp;&nbsp;&nbsp;&nbsp;Hot Site - A fully equipped backup facility ready to swiftly take over in case of a primary site failure or disruption  
&nbsp;&nbsp;&nbsp;&nbsp;Warm site - A partially equipeed backup site that can become operational within days of a primary site disruption  
&nbsp;&nbsp;&nbsp;&nbsp;Cold Site - A site with no immediate equipment or infrastructure but can be transformed into a functional backup facility  
&nbsp;&nbsp;&nbsp;&nbsp;Mobile Site - A versatile site that utilizes independent and portable units like trailers or tents to deliver recovery capabilities  
&nbsp;&nbsp;&nbsp;&nbsp;Virtual Site - Usilitzes cloud-based enviroonments and offers highly flexible approach to redundancy  
Platform Diversity - A vital aspect in redundant site design that uses different platforms to prevent single points of failure in disaster recovery  

Resilience Testing - Assesses the system's capacity to endure and adjust to disruptinve occurrences  
&nbsp;&nbsp;&nbsp;&nbsp;Tabletop Exercise - A simulated discussion to improve crisis readiness without deploying resources  
&nbsp;&nbsp;&nbsp;&nbsp;Failover Test - Verifies seamless system transition to a backup for uninterrupted functionality furing disasters  
&nbsp;&nbsp;&nbsp;&nbsp;Simulation - Computer-generated representation of real-world scenarios  
&nbsp;&nbsp;&nbsp;&nbsp;Parallel Processing - Replicates data and processes onto a secondary system, running both in parallel  


# Log Analysis with Splunk
From: [What is a SOC?](https://www.splunk.com/en_us/data-insider/what-is-a-security-operations-center.html) (accessed by Benjamin Hobbs on 7/21/2023)

* A Security Operations Center (SOC) acts as the hub for an organization security operations- A centralized location that infosec professionals employ techonology to build and maintain the security architecture that monitors, detects, analyzes and responds to cyber incidents 24/7.

### Types of SOCs

* Internal (On-prem)
* Virtual 
* Outsourced (MSSPs)

### Anatomy of a Security Operations Team
  * Security Operations Team
    * Security Operations Analysts - These are professionals trained specifically to monitor and manage security threats, and help create and maintain a secure architecture for their organization. Not only are they skilled in using a variety of security tools, they know specific processes to follow in the event that the infrastructure is breached. SOC professionals use a range of tools that collect data from across the network and various devices, monitor for anomalies and alert staff of potential threats. 
      * Tiers
        * Level 1
        * Level 2
        * Level 3
        * Level 4
    * Security Operations Engineers
      *  In general, a security engineer is responsible for designing and implementing an enterprise’s security architecture, comprising (but not limited to) telecommunication networks, security infrastructure, cloud services, disaster recovery and virtual infrastructure.
    
## Benefits of employing a SIEM
* A SIEM collects and organizes all the data coming from various sources within a network and offers a SOC team insights so that they can quickly:

  * Detect and respond to internal and external attacks
  * Simplify threat management
  * Minimize risk
  * Gain organization-wide visibility and security intelligence

SIEM is critical for SOC tasks, such as monitoring, incident response, log management, compliance reporting and policy enforcement. Its log management capabilities alone make it a necessary tool for any SOC.

## Questions for understanding
1. What are three tasks which SOCs often perform?
  * Event discovery and Prioritization
  * Real-time monitoring
  * Risk Assessment

2. Explain what a SIEM solution is and how the SOC utilizes it in non-technical terms.
  * Security Operations Teams are generally responsible for a lot. They are:
    * **CONSTANTLY** monitoring activity for evidence of an intrusion/incident
    * **CONSTANTLY** improving/patching/updating/refreshing the architecture
    * **CONSTANTLY** advising/training/writing/analyzing company behavior to reduce threat surface (and risk to the company)
* That is a lot of things to do on a constant basis. SIEM solutions assist in consolidating that down to one place so that it's easier for less people to handle that load...which free the other team members up to address other tasks. You also set alerts on SIEMs. ***"Hey little buddy, you're cruising through a lot of data super fast...IF you ever run into "XYZ" situation, you shout it out and let me know OK?"***

3. How does the typical SOC team structure resemble the structure of an IT Help Desk.
   1. They may not be in the building...virtual SOCs
   2. They may not be in the country or work directly for the company...outsourced SOCs (Managed Security Service Provider [MSSPs]) 
   3. They are comprised of tiers that can escalate issues up if needed. 
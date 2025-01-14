# Lecture 1

## Computer Security vs Network Security

* Computer Security - The generic name for the collection of tools designed to protect data and to thwart hackers/attackers
* Network Security - Measures to deter, prevent, detect, and correct security violations that involve the transmission of information

## Confidentiality vs Privacy

* Confidentiality - Assures that private or confidential information is not made available or disclosed to unauthorized individuals
* Privacy - Assures that individuals control or influence what information related to them may be collected and stored and by whom and to whom that information may be disclosed

## Integrity

* Data Integrity - Assures that information and programs are changed only in a specified and authorized manner
* System Integrity - Assures that a system performs its intended function in an unimpared manner, free from deliberate or inadvertent unauthorized manipulation of the system
  * Impossible to achieve   

## Authenticity

* Authenticity - Verifying that users are who they say they are and that each input arriving at the system came from a trusted source
* Authorization (Access Control) - The ability to limit and control the access to host systems and applications via communication links

## Passive vs Active Attacks

* A passive attack attempts to learn or make use of informtaino from the system but does not affect system resources
* An active attack attempts to alter system resources or affect their operation

## Before We Start

* Security is essentially a battle of wits between a perpetrator and the designer
* It is necessary to decide where to use the various secuirty mechanisms
* Requires constand monitoring
* Strong security is often viewd as an impediment to efficient and user-friendly operation

## Some Security Challenges

* Types of attacks
* Attack phases
* Attack Surface
* Attack Tree
* Threat Modeling
* Incident Response

### Types of Attacks

* Physical Secruity
* Social Engineering
* Web-App Based
* Software Based
* Network-Based

### Attack Phases

* **Reconnaissance**
  * Gather information
  * Learn about the target
  * Dumpster Diving
  * Online Personal Information 
* **Scanning**
  * Scan the network for info
  * Port scanners
  * Ping tools
  * Vulnerability Scanners
* **Gaining Access**
  * Access to network
  * Access to application
  * Access to operating system
* **Maintaining Access**
  * Install Malware
  * Privilege Escalation
  * Create an Admin ACcount
* **Clearing Tracks**
  * Remove hardware
  * Delete logs
  * Delete accounts created
 
### Attack Surface

* Reachable and exploitable vulnerabilities in a system
* Examples: Open ports on outward facing Web and other servers, code listening on open ports, web forms, and employee access to sensitive information vulnerable to a social engineering attack.

# Security Incident Reporting
 
## Introduction
Infinity Works has established a formal policy and supporting procedures in the event of a Security Incident.

## Procedure
All Infinity Works employees should be aware of common security threats and computer incidents that may potentially compromise the organisation's computing infrastructure, cause harm to other related systems or pose a significant financial, operational or business threat to the organisation as a whole.

It is the responsibility of all staff to report security risks and incidents to the ISMS Committee.

The ISMS Committe will choose whether to form a Security Incident Response team in response to the report, formed from employees and other external groups if required (e.g. external security specialists).

### Security Incident Response Team 
 
* [ISMS Committee](../README.md#the-isms-committee)
 
## Detection
Detection may occur in several ways:
  * Being informed by a 3rd party of a vulnerability within our systems.
  * Detection through anomalous system metrics e.g. increased compute cost, high traffic volume ([Monitoring](../monitoring/readme.md)).
  * Identifying unauthorised system usage through manual checklists, and audits ([Access Control](../accesscontrol/readme.md)).
  * Via human interaction (e.g. noticing social engineering attempts ([Physical Security](../physicalsecurity/readme.md)).
  * Anything not covered by the above.

## Response
The ISMS Manager will evaluate reports of incidents and decide whether to notify the [ISMS Committee](../README.md#the-isms-committee).

If notified, a suitable member of the [ISMS Committee](../README.md#the-isms-committee) formally assumes control and is tasked with identifying the threat and its severity to the organisation's information systems and reporting back to the [ISMS Committee](../README.md#the-isms-committee).

The selected ISMS member is to make a determination if the resources at risk (hardware, software, etc.) require physical or logical removal.  Resources which pose a significant threat to the continuity of the business are to be immediately removed or isolated, either physically or logically. 

A response plan should be proposed to deal with potential risk identified. This may need to be authorised by the [ISMS Committee](../README.md#the-isms-committee) before implementation.  This plan should include:  
* Description of issue 
* Impact to the business 
* Timescale to fix 
* Mitigation 
* Decisions needed

The Security Incident Log can be found [here](https://docs.google.com/spreadsheets/d/1NxIoFZLzkpmQlwXNpvoj3Uyb6-z540l6NrDg8B0yJSs/edit#gid=75233254)
 
It is the responsibility of the [ISMS Committee](../README.md#the-isms-committee) to ensure that an investigation can follow the incident. For example by:
* Understanding how the incident occurred and what led to the compromise 
* Securing all necessary system documentation, such as logs, audit trails  
* Interviewing personnel as needed  
* Examining any third party providers and their respective products and services that are utilised within Infinity Works’s network architecture
* If warranted, a third party for assisting in the investigation of the incident may be utilised (this will be done at the management’s discretion) 

## Recovery
Recovery procedures may include, but are not limited to the following: 
* Restoring systems from clean backups (a trusted source only) 
* Completely rebuilding systems as needed and warranted 
* Replacing systems as needed
* Reconfiguring network security (stronger, more adaptive configuration and hardening rules)

The recovery procedures will be commensurate with the incident that has occurred.  This will be conducted on a case-by-case basis with all aspects of the recovery process fully documented. 
 
## Post-Incident Review
A formal and documented Incident Response Report (IRR) is to be compiled and given to the [ISMS Committee](../README.md#the-isms-committee) within an acceptable time frame following the incident. The IRR must contain the following elements: 

 * Detailed description of the incident 
 * Response mechanisms undertaken 
 * Reporting activities to all relevant third parties as needed 
 * Recovery activities undertaken for restoring affected systems  
 * A list of Lessons Learned from the incident including review and updating of process documentation and which initiative Infinity Works can take to mitigate and hopefully eliminate the likelihood of future incidents 


[back](../README.md#a-z-policies)

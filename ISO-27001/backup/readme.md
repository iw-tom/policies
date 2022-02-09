# Backup Policy
 	  	 	 
## Introduction
Opus Works must secure data against loss of confidentiality, integrity and availability during transfer between electronic systems.

This document presents security controls that must be applied to systems which require backup.

These systems include, but are not limited to:
- Document and file repositories (e.g. Google Drive)
- Collaborative tools (e.g. Confluence)
- Delivery Tracking Tools / Agile Life-cycle Management Tools (e.g. JIRA)
- Source code control management systems (e.g. Github, Bitbucket)
- Cloud Services (e.g. AWS, Azure, Google Cloud Platform)

## Audience
This document should be read by all administrators, information security and security operations personnel and those involved with the support and maintenance of Opus Works’ backup processes and procedures.  

## Non-Compliance
If the controls detailed in this standard cannot be met, the exemption must be approved by the ISMS Committee.

## Information Backup
The policy of Opus Works is that cloud storage is more reliable than local device storage and that cloud services such as Google Drive should be used in preference to storing files on a local computer, where the files can be lost with the device.

You should treat your laptop as a disposable commodity that you may lose access to any time. See the [Laptop Policy](../device/readme.md).

It is your responsibility to use the services provided to you by Opus Works to protect against data loss.

All services we provide to staff use encrypted communication channels, but data may not stored encrypted at rest by default within these services. Ensure that you follow the [Information Sensitivity Policy](../informationsensitivity/readme.md).

It is the responsibility of our hosted service providers to maintain access to data hosted within those services.

However, we will also maintain a secondary backup in case of service provider failure, unless the data is of a low value or displosable nature. The backup will be on a different service (e.g. it would be foolish to backup Google Drive to Google Drive).

Backup equipment and processes will be tested regularly to ensure that they can still be relied upon, and specifically to confirm that backups can be retrieved and restored within agreed service levels for data/service recovery, and that any data loss incurred is acceptable.

## Backup Protection
Backups must be physically and logically protected to at least the same degree as the original data.
 
Data that is stored in encrypted format must remain encrypted in backups and any associated archives.

## Responsibility for Policy Maintenance  
The ISMS Committee is responsible for ensuring that the policy is kept current as needed for purposes of compliance. 

[back](../README.md#a-z-policies)

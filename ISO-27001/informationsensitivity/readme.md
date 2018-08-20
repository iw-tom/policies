# Information Sensitivity Policy

## Purpose 

The Information Sensitivity Policy is intended to help employees and contractors in determining appropriate technical security measures which are available for electronic information deemed sensitive.

The information covered in this policy includes electronic information stored on computers, e-mails, information on computer screens, and information shared orally or visually (such as cellular telephone and video conferencing). 

While this policy gives a general overview of the handling of sensitive information, users must be aware of additional Policies that may enforce more specific requirements. 

## Scope 

This policy applies to all Infinity Works employees and contractors.

## Policy

The Sensitivity Guidelines below provide details on how to protect information at varying sensitivity levels. The sensitivity level to be assigned to electronic information may be assigned by any area which handles the information. 

### Classifications

Please note: Sample Data not an exhaustive list

#### Level 3 - Extreme

Data that creates extensive "shared-fate" risk between multiple sensitive systems, e.g., credential stores, backup data systems, and central system management consoles.

> Shared-Fate: If a data compromise would cause further and extensive data compromise from multiple (even unrelated) sensitive systems, the data creating this "shared-fate" warrants an elevated data protection level.

This includes:

- Client commercially confidential data
- Infinity Works commercially confidential data
- User IDs and Passwords

#### Level 2 - High

Data elements with a statutory requirement for notification to affected parties in case of a confidentiality breach:

- National Insurance number
- Driver's license number
- Financial account numbers, credit or debit card numbers and financial account security codes, access codes, or passwords
- Personal medical information

#### Level 1 - Moderate

Information intended for release only on a need-to-know basis, including personal information not otherwise classified as Level 0, 2 or 3, and data protected or restricted by contract, grant, or other agreement terms and conditions, e.g.:

- Staff records (including Employee ID)
- Licensed software/software license keys

#### Level 0 - Limited or none

Information intended for public access, e.g.:

- Public websites
- Course listings and pre-requisites
- Electronic brochures
- Internal blogs

### Sensitivity Approach

#### Level 3

* Ensure that we follow our clients' data requirements.
* Ensure that data is encrypted, and where possible, we do not have access to the unencrypted data ourselves (e.g. by using AWS KMS and providing an IAM role to an AWS EC2 instance or Lambda function which allows it to access the decryption keys to decrypt data as required).
* Strongly limit network access to data (e.g. by using Security Groups within AWS and limiting availability of data to private subnets).
* Strongly limit program code access to data and apply tiered application designs to reduce the potential attack surface.
* Obfuscate log data appropriately.
* Pay attention to data sovereignty laws.

#### Level 2

* Ensure that we follow our client's data requirements.
* Ensure that data is encrypted, and where possible, we do not have access to the unencrypted data ourselves (e.g. by using AWS KMS and providing an IAM role to an AWS EC2 instance or Lambda function which allows it to access the decryption keys to decrypt data as required).
* Strongly limit network access to data (e.g. by using Security Groups within AWS and limiting availability of data to private subnets).
* Strongly limit program code access to data and apply tiered application designs to reduce the potential attack surface.
* Obfuscate log data appropriately.
* Pay attention to data sovereignty laws.

#### Level 1

- Electronic distribution
   * Via a method agreed with the sender.
   * Shared via a restricted Team Drive folder.
- Encryption
   * Strong encryption may be required.
- Storage
   * Individual access controls required.

#### Level 0

- Electronic distribution: Publicly available via the Internet, alteration controlled via identifiable user ID and password or suitable content control mechanism (e.g. Pull request and review from an approved reviewer per GitHub) is recommended.
- Encryption: Not required
- Storage: Keep from view of unauthorized individuals; machines should be administered with security in mind. Electronic information should have individual access controls where possible and appropriate.
- Destruction: None applies

## Definitions 

### Approved Electronic File Transmission Methods 

Includes supported SFTP clients, SSH sessions, VPN tunnels, and HTTPS/SSL. 

### Approved Electronic Mail 

Includes all mail systems supported by the Infinity Works or our clients. If you have a business need to use other mailers, contact the [ISMS Committee](../README.md#the-isms-committee). 

### Individual Access Controls 

Individual Access Controls are methods of electronically protecting files from being accessed by individuals other than those specifically authorized. On most operating systems this is referred to as file permissions.

### Encryption 

Encryption is a procedure used to convert data from its original form to a format that is unreadable and/or unusable to anyone without the tools/information needed to reverse the encryption process.

## Policy Compliance

### Compliance Measurement

The ISMS Committee team verify compliance to this policy through various methods, including but not limited to, business tool reports, internal and external audits, and feedback to the policy owner.

### Exceptions

Any exception to the policy must be approved by the [ISMS Committee](../README.md#the-isms-committee) team in advance.

### Non-Compliance

An employee found to have violated this policy may be subject to disciplinary action, up to and including termination of employment.

## Related Standards, Policies and Processes

- [Information Exchange Policy](../informationexchange/readme.md)
- [Cryptographic Controls Policy](../cryptographiccontrols/readme.md)
- [Data Retention Policy](../dataretentionanddisposal/readme.md)

[back](../README.md#a-z-policies)

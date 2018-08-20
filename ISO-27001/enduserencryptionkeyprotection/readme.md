# End User Encryption Key Protection Policy

## Overview

Encryption Key Management, if not done effectively, can lead to compromise and disclosure of private keys use to secure sensitive data and hence, compromise of the data.   While users may understand it’s important to encryption certain documents and electronic communications, they may not be familiar with minimum standards for protection encryption keys. 

## Purpose

This policy outlines the requirements for protecting encryption keys that are under the control of end users. These requirements are designed to prevent unauthorized disclosure and subsequent mis-use. The protection methods outlined will include operational and technical controls, such as key backup procedures, encryption under a separate key and use of tamper-resistant hardware.

## Scope

This policy applies to any encryption keys listed below and to the person responsible for any encryption key listed below. The encryption keys covered by this policy are:

- encryption keys issued by Infinity Works
- encryption keys used for Infinity Works business
- encryption keys used for Infinity Works clients
- encryption keys used to protect data owned by Infinity Works

The public keys contained in digital certificates are specifically exempted from this policy.

## Policy

All encryption keys covered by this policy must be protected to prevent their unauthorized disclosure and subsequent mis-use.

### Secret Key Encryption Keys

Keys used for secret key encryption, also called symmetric cryptography, must be protected as they are distributed to all parties that will use them. During distribution, the symmetric encryption keys must be encrypted using a stronger algorithm with a key of the longest key length for that algorithm authorized in Infinity Works Cryptographic Controls Policy. If the keys are for the strongest algorithm, then the key must be split, each portion of the key encrypted with a different key that is the longest key length authorized and the each encrypted portion is transmitted using different transmission mechanisms. The goal is to provide more stringent protection to the key than the data that is encrypted with that encryption key.

Symmetric encryption keys, when at rest, must be protected with security measures at least as stringent as the measures used for distribution of that key.

#### Public Key Encryption Keys

Public key cryptography, or asymmetric cryptography, uses public-private key pairs. The public key is passed to the certificate authority to be included in the digital certificate issued to the end user. The digital certificate is available to everyone once it issued. The private key should only be available to the end user to whom the corresponding digital certificate is issued.

#### Infinity Works Consulting’s Public Key Infrastructure (PKI) Keys

The public-private key pairs used by the Infinity Works public key infrastructure (PKI) are generated on the tamper-resistant smart card issued to an individual end user. The private key associated with an end user’s identity certificate, which are only used for digital signatures, will never leave the smart card. This prevents the ISMS Committee from escrowing any private keys associated with identity certificates. The private key associated with any encryption certificates, which are used to encrypt email and other documents, must be escrowed in compliance with Infinity Works policies. 

Access to the private keys stored on an Infinity Works issued smart-card will be protected by a personal identification number (PIN) known only to the individual to whom the smart-card is issued. The smart-card software will be configured to require entering the PIN prior to any private key contained on the smart card being accessed.

#### Other Public Key Encryption Keys

Other types of keys may be generated in software on the end user’s computer and can be stored as files on the hard drive or on a hardware token. If the public-private key pair is generated on smart-card, the requirements for protecting the private keys are the same as those for private keys associated with Infinity Works Consulting’s PKI. If the keys are generated in software, the end user is required to create at least one backup of these keys and store any backup copies securely. The user is also required to create an escrow copy of any private keys used for encrypting data and deliver the escrow copy to the local Information Security representative for secure storage. 

The ISMS Committee shall not escrow any private keys associated with identity certificates. All backups, including escrow copies, shall be protected with a password or pass-phrase that is compliant with Infinity Work Password Policy.  The ISMS Committee representatives will store and protect the escrowed keys as described in the Infinity Works  Cryptographic Controls Policy.

##### Commercial or Outside Organization Public Key Infrastructure (PKI) Keys

In working with business partners, the relationship may require the end users to use public-private key pairs that are generated in software on the end user’s computer. In these cases, the public-private key pairs are stored in files on the hard drive of the end user. The private keys are only protected by the strength of the password or pass-phrase chosen by the end user. For example, when an end user requests a digital certificate from a commercial PKI, such as VeriSign or Thawte, the end user’s web browser will generate the key pair and submit the public key as part of the certificate request to the CA. The private key remains in the browser’s certificate store where the only protection is the password on the browser’s certificate store. A web browser storing private keys will be configured to require the user to enter the certificate store password any time a private key is accessed.

##### PGP Key Pairs

If the business partner requires the use of PGP, the public-private key pairs can be stored in the user’s key ring files on the computer hard drive or on a hardware token, for example, a USB drive or a smart card. Since the protection of the private keys is the pass-phrase on the secret keying, it is preferable that the public-private keys are stored on a hardware token. PGP will be configured to require entering the pass-phrase for every use of the private keys in the secret key ring.

###	Hardware Token Storage

Hardware tokens storing encryption keys will be treated as sensitive company equipment, as described in Infinity Works Physical Security policy, when outside company offices. In addition, all hardware tokens, smart-cards, USB tokens, etc., will not be stored or left connected to any end user’s computer when not in use. For end users travelling with hardware tokens, they will not be stored or carried in the same container or bag as any computer.

###	Personal Identification Numbers (PINs), Passwords and Pass-phrases

All PINs, passwords or pass-phrases used to protect encryption keys must meet complexity and length requirements described in Infinity Works Password Policy.

### Loss and Theft

The loss, theft, or potential unauthorized disclosure of any encryption key covered by this policy must be reported immediately to the ISMS Committee.  ISMS Committee personnel will direct the end user in any actions that will be required regarding revocation of certificates or public-private key pairs.

## Policy Compliance

### Compliance Measurement

The ISMS Committee will verify compliance to this policy through various methods, including but not limited to, periodic walk-throughs, video monitoring, business tool reports, internal and external audits, and feedback to the policy owner. 

### Exceptions

Any exception to the policy must be approved by the ISMS Committee in advance. 

The public keys contained in digital certificates are specifically exempted from this policy.

### Non-Compliance

An employee found to have violated this policy may be subject to disciplinary action, up to and including termination of employment. 

## Related Standards, Policies and Processes

- [Cryptographic Controls Policy](../cryptographiccontrols/readme.md) 
- [Digital Signature Acceptance Policy](../digitalsignatureacceptance/readme.md)
- [Password Policy](../password/readme.md)
- [Physical Security policy](../physicalsecurity/readme.md)

## Definitions and Terms

The following definition and terms can be found in the SANS Glossary located [here](https://www.sans.org/security-resources/glossary-of-terms/)

- Certificate authority (CA)
- Digital certificate
- Digital signature
- Key escrow
- Plaintext
- Public key cryptography
- Public key pairs
- Symmetric cryptography

[back](../README.md#a-z-policies)

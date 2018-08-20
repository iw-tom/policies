# Password Policy

## Overview

Passwords are an important aspect of computer security.  A poorly chosen password may result in unauthorized access and/or exploitation of Infinity Works' resources.  All users, including contractors and vendors with access to Infinity Works' systems, are responsible for taking the appropriate steps, as outlined below, to select and secure their passwords.

## Purpose

The purpose of this policy is to establish a standard for creation of strong passwords, the protection of those passwords, and the frequency of change.

## Scope

The scope of this policy includes all personnel who have or are responsible for an account (or any form of access that supports or requires a password) on any system that resides at any Infinity Works facility, has access to the Infinity Works network, or stores any non-public Infinity Works information.

## Policy

### Password Creation

- Both user-level and system-level passwords must be sufficiently strong such as to make cracking or guessing difficult.
- Where possible passwords should be randomly generated rather than expose the risk that the password be deduced from information about the user.
- In all cases passwords should be of sufficient length (>= 12 characters if possible) and contain a mixture of upper case, lower case, numerical and special characters.
- Length of password is more important than complexity - i.e. adding length increases entropy (how much uncertainty there is in a password) more efficiently than replacing letters with symbols.
- Users must not use the same password for Infinity Works accounts as for other non-Infinity Works access (for example, personal ISP account, option trading, benefits, and so on).
- User accounts that have system-level privileges granted through group memberships or programs such as sudo must have a unique password from all other accounts held by that user to access system-level privileges.
- Where Simple Network Management Protocol (SNMP) is used, the community strings must be defined as something other than the standard defaults of public, private, and system and must be different from the passwords used to log in interactively. SNMP community strings must meet password construction guidelines.

### Password Change

- If Multi-Factor Authentication (MFA) is not in place, system-level passwords (for example, root, enable, NT admin, application administration accounts, and so on) must be changed on at least a quarterly basis.
- If Multi-Factor Authentication (MFA) is not in place, all user-level passwords (for example, email, web, desktop computer, and so on) must be changed at least every six months. The recommended change interval is every four months.
- Password cracking or guessing may be performed on a periodic or random basis by the [ISMS Committee](../README.md#the-isms-committee) or its delegates. If a password is guessed or cracked during one of these scans, the user will be required to change it to be in compliance with the Password Construction Guidelines.

### Password Protection

- Passwords must not be shared with anyone. All passwords are to be treated as sensitive, Confidential Infinity Works information.  
- Passwords may only be shared via secure means.
- Passwords must not be revealed over the phone to anyone.
- Do not reveal a password on questionnaires or security forms.
- Do not hint at the format of a password (for example, "my family name").
- Do not share Infinity Works user passwords with anyone, including administrative assistants, secretaries, managers, co-workers while on vacation, and family members.
- Only share Infinity Works system passwords with persons  / systems authorised by the system owner, and only share by secure means.
- Do not write passwords down and store them anywhere in your office. Do not store passwords in a file on a computer system or mobile devices (phone, tablet) without encryption.
- Any user suspecting that his/her password may have been compromised must report the incident to the [ISMS Committee](../README.md#the-isms-committee) and change all passwords.

### Application Development

Application developers must ensure that their programs contain the following security precautions:

- All non-anonymous usage applications must support authentication of individual users, not groups.
- Applications must not store passwords in clear text or in any easily reversible form.
- Applications must not transmit passwords in clear text over the network.
- Applications must provide for some sort of role management, such that one user can take over the functions of another without having to know the other's password.

### Use of Passwords and Pass-phrases

Pass-phrases are generally used for public/private key authentication. A public/private key system defines a mathematical relationship between the public key that is known by all, and the private key, that is known only to the user. Without the pass-phrase to "unlock" the private key, the user cannot gain access.

Pass-phrases are not the same as passwords. A pass-phrase is a longer version of a password and is, therefore, more secure. A pass-phrase is typically composed of multiple words. Because of this, a pass-phrase is more secure against "dictionary attacks."

A good pass-phrase is relatively long and contains a combination of upper and lower-case letters and numeric and punctuation characters. An example of a good pass-phrase:

> "The*?#>*@TrafficOnThe101Was*&#!#ThisMorning"

All of the rules above that apply to passwords apply to pass-phrases.

### Use of password managers

It is also recommended to use a secure password generators / manager (e.g.; OpenSSL, Dashlane, 1 Password, Vault) to generate and store complex passwords.  The password to access the password manager should confirm to this password policy however. Biometrics (e.g.; finger print scan) is also acceptable to access password managers.

## Policy Compliance

### Compliance Measurement

The [ISMS Committee](../README.md#the-isms-committee) will verify compliance to this policy through various methods, including but not limited to, periodic walk-throughs, business tool reports, internal and external audits, and feedback to the policy owner.

###	Exceptions

Any exception to the policy must be approved by the [ISMS Committee](../README.md#the-isms-committee) in advance.

### Non-Compliance

An employee found to have violated this policy may be subject to disciplinary action, up to and including termination of employment.

## Definitions and Terms

The following definition and terms can be found in the SANS Glossary located at:
https://www.sans.org/security-resources/glossary-of-terms/

- Simple Network Management Protocol (SNMP)

[back](../README.md#a-z-policies)

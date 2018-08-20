# Network Systems Policy

## Purpose
Effective security is a team effort involving the participation and support of every user who deals with information and/or information systems.

Information Systems play a major role in supporting the day-to-day activities of Infinity Works. These systems include but are not limited to all infrastructure, networks, hardware, and software, which are used to manipulate, process, transport or store Information owned by Infinity Works.

## Scope
This policy applies to all networks within Infinity Works offices.

## Policy

- Only employees and contractors should have access to the Infinity Works staff network, there is a separate guest network for visitors.
   - All networks should be treated as insecure and potentially hostile.
- Each piece of equipment connected to the network must have an identifiable ‘owner’.
  - In the case of the staff network, it must be a staff member who will be responsible for ensuring that the connected equipment complies with the relevant policies and regulations. 
  - In the case of guest networks, it must be a person who is on-site. i.e. nothing should be connected to the guest network outside of office hours.
- The ISMS Committee has the authority to remove devices from any network, if no owner can be identified.
- The ISMS Committee has the authority to remove from the network any equipment which is interfering with the network service or is deemed likely to compromise the security of the network.
- Anyone connecting equipment to the network is responsible for ensuring that the equipment is configured correctly, that the operating systems and software applications are up-to-date as regards patch management etc. and that the equipment has adequate protection against viruses and other malware. If there is any suspicion that the equipment may be infected or compromised in any way it should not be connected.
- Access through the network perimeter firewall is managed and operated by the firewall service owner(s).
- Any servers hosting production services for Infinity Works must be housed in a suitable environment so as to meet the service non-functional requirements.
- It is the responsibility of the service owner(s) of each service to ensure that an adequate business continuity plan is in place in the event that the service is affected by the non-availability of the relevant servers, network or other elements of the IT infrastructure.
- Authentication is required for each connection to the network. Authentication is normally via a password. It is the responsibility of each user to ensure that the password is not disclosed to unauthorised parties.
- Any breaches of security should be reported immediately to the [ISMS Committee](../README.md#the-isms-committee).
- This network policy is intended to ensure that an effective, secure and available network infrastructure for the benefit of all users is always available.
- Public wifi networks are no different to our office networks, in that they are insecure networks.
- Since all networks are possibly subject to MITM (Man-In-The-Middle) attacks, DNS poisoning attacks and other exploits. Network services used by Infinity Works must use encryption which meets our [Cryptographic Controls Policy](../cryptographiccontrols/readme.md), such as TLS certificates provided by a trustworthy certification authority.

## Policy Compliance

### Compliance Measurement

The [ISMS Committee](../README.md#the-isms-committee) team  verify compliance to this policy through various methods, including but not limited to, business tool reports, internal and external audits, and feedback to the policy owner.

### Exceptions

Any exception to the policy must be approved by the [ISMS Committee](../README.md#the-isms-committee) team in advance.

### Non-Compliance

An employee found to have violated this policy may be subject to disciplinary action, up to and including termination of employment.

## Related Standards, Policies and Processes

- [Monitoring Policy](../monitoring/readme.md)
- [Information Sensitivity Policy](../informationsensitivity/readme.md)
- [Data Protection Policy](../dataprotection/readme.md)
- [Social Networking Policy](../socialnetworking/readme.md)
- [Access Control Policy](../accesscontrol/readme.md)
- [Password Policy](../password/readme.md)

[back](../README.md#a-z-policies)

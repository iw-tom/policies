# Virus Protection Policy

## Purpose

To establish requirements and practices which must be met by to ensure effective protection from malicious code, spam and spyware.

## Scope

Applies to all employees of Infinity Works.

## Policy

Users should not disable Virus Protection and automatic update systems built into the computing device's Operating System that they are using without consent from the ISMS Committee. For example, ensuring that Windows Defender remains enabled.

Operating systems which are known to be insecure and/or are out-of-support, such as Windows XP or Windows Vista must not be used as a general purpose computing platform. If their use is required, they should be run within a suitable sandbox by a competent operator. Example mechanisms of sandboxing include hypervisors, containers and / or network whitelisting and inspection.

All networks should be considered insecure and possibly hostile. Users must enable firewalls on all equipment and should seek to minimise the attack surface of their systems by disabling unused or uneccessary network services or protocols (e.g. telnet, SSH, ICMP).

Users should employ network egress and ingress monitoring tools on their workstations (e.g. Little Snitch on OSX, Zone Alarm Firewall on Windows) to ensure that they understand which programs on their workstations are connecting to the Internet and can make an informed decision as to whether to allow that communication to occur.

Infinity Works uses a hosted email service which protects our users from unsolicited messages and malicious software.

## Prevention of malicious code problems

* Keep software appropriately up-to-date via the delivery mechanism for that software / operating system
  * e.g. apt-get, yum, OSX App Store, Windows Update, npm, nuget, go get
* Employ a personal firewall and control ingress and egress rules and avoid exposing services to other users on the network
* Take basic email precautions:
   * Never open any files or macros attached to an email from unknown, suspicious, or untrustworthy sources
   * Delete spam, chain, and other junk email without forwarding
   * Never download files from unknown or suspicious sources
   * Avoid direct disk-sharing, especially with read/write access
* Never plug-in removable media "to see what's on it"
* Exercise caution in executing code downloaded from the Web. It is often safer to run programs within a sandbox such as a Docker container or VM, taking care to ensure that directory sharing and network connectivity is properly secured.

## Detection

* Any activities with the intention to create and/or distribute malicious programs within Infinity Works are prohibited without prior permission from the ISMS Committee.
* Virus-infected computers must be removed from the network until they are verified as virus-free. If a virus is detected on your workstation and the anti-virus software can not eliminate the virus, contact the Security Comittee.

## Penalties

Employees found to have violated this policy may be subject to disciplinary action, up to and including termination of employment. Refer to Acceptable Use Policy and Disciplinary Policy.

[back](../README.md#a-z-policies)

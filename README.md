# Vulnerabilities Documentation

In this article, a full list of vulnerabilities encountered in all of Optidev3455's repositories will be displayed and what are vulnerabilities.

## What are vulnerabilities
Vulnerabilities are flaws in a computer system that weaken the overall security of the device/system. Vulnerabilities can be weaknesses in either the hardware itself, or the software that runs on the hardware. Vulnerabilities can be exploited by a threat actor, such as an attacker, to cross privilege boundaries (i.e. perform unauthorized actions) within a computer system. To exploit a vulnerability, an attacker must have at least one applicable tool or technique that can connect to a system weakness. In this frame, vulnerabilities are also known as the attack surface.

Vulnerability management is a cyclical practice that varies in theory but contains common processes which include: discover all assets, prioritize assets, assess or perform a complete vulnerability scan, report on results, remediate vulnerabilities, verify remediation - repeat. This practice generally refers to software vulnerabilities in computing systems. Agile vulnerability management refers to preventing attacks by identifying all vulnerabilities as quickly as possible.

A security risk is often incorrectly classified as a vulnerability. The use of vulnerability with the same meaning of risk can lead to confusion. The risk is the potential of a significant impact resulting from the exploit of a vulnerability. Then there are vulnerabilities without risk: for example when the affected asset has no value. A vulnerability with one or more known instances of working and fully implemented attacks is classified as an exploitable vulnerability—a vulnerability for which an exploit exists. The window of vulnerability is the time from when the security hole was introduced or manifested in deployed software, to when access was removed, a security fix was available/deployed, or the attacker was disabled.

Security bug (security defect) is a narrower concept. There are vulnerabilities that are not related to software: hardware, site, personnel vulnerabilities are examples of vulnerabilities that are not software security bugs.

Constructs in programming languages that are difficult to use properly can manifest large numbers of vulnerabilities


Source: [Wikipedia](https://en.wikipedia.org/wiki/Vulnerability_(computing))

# List of recorded vulnerabilities
| Number  | Affected Repository     | Date of Discovery | Vulnerbility Type                                   | Patched             |
| ------- | ----------------------- | ----------------- | --------------------------------------------------- | ------------------- |
| 1       | Optidev3455.github.io   | August 17th, 2023 | CWE-79 ( XSS )                                      | ✅ ( Within 1 hour )|
| 2       | Optidev3455.github.io   | August 17th, 2023 | CWE-116 ( Improper Encoding or Escaping of Output ) | ✅ ( Within 1 hour )|
| 3       | YACT ( Self Use )       | August 29th, 2023 | CWE-78 ( OS Command Injection )                     | ✅ ( Within 1 hour )|
| 3       | YACT ( Redistributable )| August 29th, 2023 | CWE-78 ( OS Command Injection )                     | ❌ ( Put on halt )  |

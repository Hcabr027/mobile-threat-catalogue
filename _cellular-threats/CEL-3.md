---
layout: threat
ThreatCategory: Cellular Air Interface
ID: CEL-3
Threat: Downgrade Attacks via Rogue Base station
ThreatOrigin:
  - '3G Security: Security Threats and Requirements (Release 4) [^165]'
  - LTE Architecture Overview and Security Analysis (Draft NISTIR 8017) [^166]
  - LTE Security and Protocol Exploits [^167]
ThreatDescription: A rogue base station could force a device to temporarily downgrade its communication standard to a previous cellular network generation. This can make the communication more susceptible to security and privacy issues.
ExploitExample:
  - Researchers exploit cellular tech flaws to intercept phone calls [^168]
  - Every LTE call, text, can be intercepted, blacked out, hacker finds [^247]
CVEExample:
PossibleCountermeasures:
    Original Equipment Manufacturer:
      - Ensure baseband firmware prevents the use of insecure cellular encryption algorithms
    Mobile Network Operator:
      - Use of application layer encryption technologies
title: CEL-3
rawID: 3
---

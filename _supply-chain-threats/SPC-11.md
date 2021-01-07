---
layout: threat
ThreatCategory: Supply Chain
ID: SPC-11
Threat: Vulnerable BIOS Installation
ThreatOrigin: Supply Chain Attack Framework and Attack Patterns [^142]
ThreatDescription: An adversary with access to download and update system software installs a BIOS containing known vulnerabilities for future exploitation.[^142]
ExploitExample:
CVEExample:
PossibleCountermeasures:
    Enterprise:
      - System maintenance processes for highly sensitive components such as BIOS should require dual authentication to perform, reducing the likelihood a single adversary can introduce malware
      - Utilize systems with boot validation and attestation to verify that only genuine boot code is executed during system start-up, halting start-up if integrity verification for any component fails
title: SPC-11
rawID: 11
---

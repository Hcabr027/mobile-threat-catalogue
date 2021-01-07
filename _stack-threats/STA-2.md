---
layout: threat
ThreatCategory: Mobile Operating System
ID: STA-2
Threat: Improper Application Update Authentication
ThreatOrigin: 'Android: One Root to Own Them All [^202]'
ThreatDescription: Improperly authenticating application update packages could leave the device susceptible to malicious updates or other attacks.
ExploitExample: Own your Android! Yet Another Universal Root [^214]
CVEExample: CVE-2013-4787
PossibleCountermeasures:
    Enterprise:
      - Monitor the security patch state of devices and block enterprise connectivity from out-of-date devices with known exploitable vulnerabilities.
      - Purchase devices from vendors/carriers who have committed to providing timely updates or who have known track records for prompt updates.
      - Ensure devices are kept up-to-date with security patches to decrease the likelihood that they can be rooted/jailbroken.
      - Use tools or device APIs (Android SafetyNet, Samsung Knox hardware-backed remote attestation, or other applicable remote attestation technologies) to detect and block enterprise connectivity from known compromised devices.
      - Use device APIs (e.g. SystemUpdatePolicy) to enforce system update policies.
      - Restrict installation of apps from unofficial app stores, which may not undergo certificate validation processes (e.g., side-loading)
      - Use device built-in separation technologies such as Android for Work, Apple iOS managed apps, or Samsung Knox Workspace to provide a level of separation between enterprise apps and potentially harmful personal-use apps.
title: STA-2
rawID: 2
---

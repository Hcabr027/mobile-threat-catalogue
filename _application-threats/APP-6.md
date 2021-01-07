---
layout: threat
ThreatCategory: Vulnerable Applications
ID: APP-6
Threat: Vulnerable Third-Party Library
ThreatDescription: A mobile app may not directly contain vulnerabilities in its code, but may make calls to a third-party library that does contain vulnerabilities that are exploitable by a remote attacker.
ThreatOrigin:
  - A Pattern for Remote Code Execution using Arbitrary File Writes and MultiDex Applications [^73]
  - Unsafe Exposure Analysis of Mobile In-App Advertisements [^74]
ExploitExample:
CVEExample:
PossibleCountermeasures:
    Enterprise:
      - Deploy MAM or MDM solutions with policies that prohibit the side-loading of apps, which may bypass security checks on the app.
      - Deploy MAM or MDM solutions with policies that prohibit the installation of apps from 3rd party (unofficial) app stores.
      - Use app-vetting tools or services to identify apps that use vulnerable libraries.
title: APP-6
rawID: 6
---

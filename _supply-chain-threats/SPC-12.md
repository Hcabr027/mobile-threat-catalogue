---
layout: threat
ThreatCategory: Supply Chain
ID: SPC-12
Threat: Corrupted Automated Installer
ThreatOrigin: Supply Chain Attack Framework and Attack Patterns [^142]
ThreatDescription: An automated software update/patch downloader/installer can be corrupted to download malicious code and apply it to systems being sustained.[^142]
ExploitExample:
CVEExample:
PossibleCountermeasures:
    Enterprise:
      - Use fine-grained role-based access control mechanisms and user/service roles that reduce the potential that malicious installation or upgrade packages can introduce malware outside of files and directories allocated to the associated software
      - Scan systems with newly integrated or updated software components for indicators of compromise prior to production use
title: SPC-12
rawID: 12
---

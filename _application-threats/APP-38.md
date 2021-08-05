---
layout: threat
ThreatCategory: Malicious or privacy-invasive application
ID: APP-38
Threat: Abusing Device Resources for Computations
ThreatDescription: While traditionally a threat against systems with greater individual system resources, the multitude of mobile devices provides an attacker who can run computations on a large number of compromised devices with an advantage in performimg other work. The computations performed on behalf of the attacker potentially cause a denial-of-service attack against the user due to the increased consumption of device resources such as battery power, computational power, network bandwidth, data usage limits, or device storage.
ThreatOrigin: Mobile Malware Mines Dogecoins Litecoins for Bitcoin Payout[^V-Zhang-1]
ExploitExample:
  - Androidos_kagecoin.hbt [^TrendMicro-1]
  - Currency-mining Android malware is so aggressive it can physically harm phones [^D-Goodin-2]
CVEExample:
PossibleCountermeasures:
    Mobile Device User:
      - To reduce the risk of installing apps with trojan functionality, only download apps from official app stores.
      - Use malware detection apps that identify malware by anomalous energy consumption.
    Enterprise:
      - Use malware detection apps that identify malware by anomalous energy consumption.
title: APP-38
rawID: 38
---

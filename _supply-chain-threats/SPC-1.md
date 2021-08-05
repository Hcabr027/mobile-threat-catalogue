---
layout: threat
ThreatCategory: Supply Chain
ID: SPC-1
Threat: Hardware or Firmware Component Interception
ThreatOrigin: Supply Chain Attack Framework and Attack Patterns [^142]
ThreatDescription: A hardware or firmware component can be intercepted by an adversary while in transit between supplier and acquirer, for the purpose of substitution or manipulation.[^142]
ExploitExample:
CVEExample:
PossibleCountermeasures:
    Enterprise:
      - Require firmware to be digitally signed by a trusted developer and the signature verified prior to the component being integrated into a larger system
      - Employ software integrity verification checks on installed firmware, which can be validated against a known-good value (e.g. brute-force resistant cryptographic hash of firmware image) to detect any modification to firmware
      - Obtain device measurements for comparison to normal ranges (e.g., temperature, timing, EM radiation, power consumption) to detect anomalous behavior.
title: SPC-1
rawID: 1
---

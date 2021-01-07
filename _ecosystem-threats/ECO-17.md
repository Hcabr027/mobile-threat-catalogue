---
layout: threat
ThreatCategory: Mobile Application Store
ID: ECO-17
Threat: Sign and Distribute Malicious App
ThreatDescription: App developer's credentials typically have permission to push app updates to the respective app store. If these credentials are somehow obtained by an attacker, they could publish a malicious application using the developers name and reputation to aid distribution.
ThreatOrigin: 'Keep out hijackers: Secure your app store dev account [^150]'
ExploitExample: Major security hole allows Apple passwords to be reset with only email address, date of birth (update) [^152]
CVEExample:
PossibleCountermeasures:
    Enterprise:
      - Use app-vetting tools or services to determine that apps appear free of malicious behaviors or vulnerabilities prior to authorizing their use.
      - To decrease the time to detection for malicious apps, use app threat intelligence services to detect malicious apps installed on devices
      - Educate end users to scrutinize the permissions requested by apps, particularly if an updated version requests significantly different permissions than previous ones.
    Mobile App Developer:
      - To reduce the potential for an attacker to impersonate you to official apps stores, follow best practices to protect your developer accounts, such as using multi-factor authentication. [^159] [^160]
      - To reduce the potential for an attacker to craft malicious apps that validate against your developer account, follow best practices to protect cryptographic signing material for applications [^162]
    Mobile Device User:
      - To decrease the time to detection for malicious apps, use Android Verify Apps feature.
title: ECO-17
rawID: 17
---

# Active Directory Attack & Detection Lab

A homelab project for executing common Active Directory attacks and writing detections that catch them. The goal: Splunk SPL detections mapped to MITRE ATT&CK techniques for Kerberoasting, AS-REP Roasting, and Pass-the-Hash, validated against Windows Security event logs.

## 🚧 Status

Active last updated April 26, 2026

- [x] Project plan / lab architecture
- [x] Windows Server 2022 domain controller deployed
- [x] Two Windows 10 endpoints domain-joined
- [x] BadBlood populated with realistic users and groups
- [ ] Sysmon + Splunk forwarder configured
- [ ] Kerberoasting attack + detection (T1558.003)
- [ ] AS-REP Roasting attack + detection (T1558.004)
- [ ] Pass-the-Hash attack + detection (T1550.002)
- [ ] Final write-up

## Architecture

## Detections (in progress)

Detections will be added under /detections/ as they're written and validated. Each will include:

- Splunk SPL query
- MITRE ATT&CK technique mapping
- Relevant Windows Event IDs
- Atomic Red Team validation notes

## Tools

Windows Server 2022 · Sysmon · Splunk · Impacket · Rubeus · BadBlood · MITRE ATT&CK

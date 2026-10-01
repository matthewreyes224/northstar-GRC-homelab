# Project Status

**Project:** Northstar GRC Homelab  
**Organization:** Northstar Technical Solutions  
**Domain:** `cyber.homelab.test`  
**Network:** `10.10.10.0/24`

## Completed / Established

- Hyper-V virtual lab platform established.
- pfSense selected and deployed as `FW01`.
- Hyper-V networks named `GRC-WAN` and `GRC-LAN`.
- Internal lab subnet established as `10.10.10.0/24`.
- Windows Server 2025 designated as `DC01`.
- Current Active Directory domain name standardized as `cyber.homelab.test`.
- Ten Northstar security/GRC policy chapters drafted.
- Governance approach established around NIST CSF 2.0 and ISO/IEC 27001.
- Policy examples intentionally use field-specific technical scenarios instead of basic terminology explanations.

## In Progress

- Final AD DS / DNS implementation validation on `DC01`.
- Evidence capture for pfSense, Hyper-V, and Windows Server controls.
- Risk register population using actual lab conditions.
- Control implementation matrix linking policy requirements to technical evidence.

## Planned — Not Yet Operational

- Windows DHCP service on `DC01`.
- VLAN-based network segmentation.
- Centralized logging / SIEM.
- Additional servers and endpoints.
- Automated backup jobs and recovery testing.
- Formal recurring vulnerability scanning.
- Full incident-response tabletop exercise.
- Third-party risk assessment exercise.

## Control-State Rule

A control is not marked **Implemented** simply because it appears in a policy. Technical implementation, evidence, and test results are tracked separately. Planned controls remain labeled **Planned** until verified.

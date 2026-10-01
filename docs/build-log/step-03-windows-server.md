# Step 03 — Windows Server / Domain Services

## Objective

Establish the Windows infrastructure required for identity, DNS, and future centralized management.

## Current Project Standard

- Server: `DC01`
- Operating system: Windows Server 2025
- Domain: `cyber.homelab.test`
- Planned DHCP role: Windows DHCP on `DC01`

## Current State

`DC01` is part of the current lab architecture. AD DS / DNS implementation should be validated and evidence collected before the related controls are marked implemented. DHCP remains planned until configured and tested.

## Evidence to Capture

- Server identity and static network settings.
- Installed roles and features.
- AD domain verification.
- DNS forward/reverse lookup tests.
- DHCP scope configuration after implementation.
- Domain-joined client validation.

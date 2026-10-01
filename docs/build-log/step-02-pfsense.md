# Step 02 — pfSense Firewall

## Objective

Deploy pfSense as the lab's network-security boundary.

## Current State

- Firewall hostname: `FW01`
- Platform: pfSense
- WAN-side virtual network: `GRC-WAN`
- LAN-side virtual network: `GRC-LAN`
- LAN subnet: `10.10.10.0/24`

## GRC Relevance

Firewall controls provide evidence for network-boundary protection, configuration management, change control, and security monitoring. A firewall rule only demonstrates a control when the rule is documented, justified, implemented, and tested.

## Example Stakeholder Translation

A **stateful firewall rule** evaluates connection state and expected traffic direction rather than simply allowing traffic because a port number exists. A broad `any-to-any` rule can allow lateral movement after one endpoint is compromised, while a restricted rule set limits the pathways available to an attacker.

## Evidence to Capture

- Interface assignments.
- LAN addressing.
- Sanitized firewall-rule screenshots.
- Test results showing allowed and blocked traffic.
- Change record for material firewall-rule changes.

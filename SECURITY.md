# Repository Security Rules

This repository is intended for a public-facing cybersecurity/GRC portfolio. Do not commit sensitive operational data.

## Never Commit

- Passwords or password hashes
- API tokens or OAuth tokens
- Private keys or certificates containing private keys
- pfSense XML configuration backups
- Windows registry exports containing credentials or secrets
- VM disk files (`.vhd`, `.vhdx`, `.vmdk`)
- Memory dumps
- Real customer, employee, or employer data
- Personally identifiable information
- Production IP addressing or confidential network diagrams

## Evidence Handling

Screenshots and configuration excerpts should be sanitized before commit. Where possible, evidence should demonstrate the control without revealing secrets.

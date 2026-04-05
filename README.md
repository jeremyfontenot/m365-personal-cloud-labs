# M365 Personal Cloud Labs

Hands-on Microsoft 365 lab exercises covering identity, security, device management, and messaging using real-world configurations and automation.  
This repository was migrated from a private SharePoint-based lab environment and published with full provenance and minimal alteration.

## Purpose

This repository exists to document and preserve **real Microsoft 365 lab work** in a Git-native format.  
It is **not** a greenfield tutorial series; it reflects configurations, scripts, and artifacts developed and tested in an actual lab tenant.

The goal is to provide:
- Practical reference material
- Reusable automation examples
- A defensible portfolio artifact demonstrating enterprise M365 engineering

## Audience

- IT Professionals
- Systems Administrators
- Security Engineers
- Engineers building or maintaining Microsoft 365 lab environments

A working familiarity with Microsoft 365 administration and PowerShell is assumed.

## Lab Structure

Labs are designed to be followed in sequence and are located in the `labs/` directory:

| Order | Lab |
|------:|-----|
| 00 | Environment and lab overview |
| 01 | Conditional Access baseline |
| 02 | Intune device and compliance baseline |
| 03 | Exchange Online configuration |
| 04 | Reporting and validation |
| 99 | Cleanup and teardown |

Each lab references **actual scripts and artifacts** stored in the repository rather than duplicated walkthrough content.

## Repository Structure

labs/        – Lab documentation and references
scripts/     – PowerShell automation used by the labs
assets/      – Diagrams, branding, and visual artifacts
docs/        – Architecture, assumptions, and provenance

### Scripts

Scripts are organized by service for clarity:

- `scripts/entra` – Entra ID and Conditional Access automation
- `scripts/intune` – Intune enrollment, compliance, and configuration
- `scripts/exchange` – Exchange Online configuration
- `scripts/cleanup` – Lab teardown and rollback
- `scripts/common` – Shared helpers and utilities

Legacy SharePoint-exported script structure is preserved under:

scripts/archive/
to maintain fidelity with the original environment.

## Safety Notice

⚠️ **Non‑production use only**

These labs and scripts were designed for lab and test tenants.  
Do **not** apply configurations directly to production environments without review and adaptation.

## Origin and Provenance

All content in this repository was migrated from a private SharePoint Online lab environment prior to Microsoft 365 tenant decommissioning.

- No tenant data is required
- No secrets or identifiers are included
- Historical structure is intentionally preserved where appropriate

See docs/origin.md for full provenance details.

## License

Unless otherwise noted, this repository is intended for educational and reference use.  
A license may be added or updated in future revisions based on reuse intent.

---

> This repository prioritizes authenticity and technical fidelity over polish.  
> Improvements are made incrementally and intentionally.

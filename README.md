# Antenna Deployer Module

> Public archive note: this repository is a portfolio/demo-safe version prepared from private working repositories/materials; sensitive details, credentials, raw logs, and proprietary context are intentionally omitted.

Clean public archive of source, reports, and test evidence for a CubeSat antenna deployment subsystem. This repository is a recruiter-friendly writeup of the design approach and validation flow; sensitive mission details, proprietary drawings, and flight-specific parameters are intentionally omitted.

## Project Summary

The antenna deployer module supports a CubeSat communication subsystem by holding deployable antenna elements during launch and releasing them after commissioning. The engineering work focuses on reliable release behavior, PCB-level control, deployment fault tolerance, and test evidence that connects the electrical design to the mechanical deployment sequence.

## What This Shows

- CubeSat subsystem thinking across RF, PCB design, deployment logic, and system integration
- Public-safe explanation of the antenna release architecture and validation plan
- Engineering documentation habits: assumptions, interface notes, test procedure, and risk tracking
- Practical awareness of mission constraints such as vibration, thermal cycling, stored energy, and one-shot deployment reliability

## Evidence Included

- `docs/public-report.md` - public-safe project report and architecture notes
- `docs/test-notes.md` - validation plan, acceptance checks, and placeholder data fields
- Website proof image - linked from [aryanch.com](https://aryanch.com)

## Public-Safe Assumptions

The values in this archive are placeholders for public presentation. They are meant to show the analysis structure, test thinking, and engineering workflow without exposing confidential or mission-specific design values.

## Suggested Validation Flow

1. Inspect PCB power and control rails before installing release elements.
2. Confirm firmware command path and deployment inhibit behavior.
3. Run continuity checks through the deployment circuit.
4. Perform controlled bench release tests using current-limited supplies.
5. Repeat release timing checks after environmental exposure.
6. Record pass/fail notes, current draw, release time, and any post-test damage.

## Portfolio Context

This project belongs with the RF and space-systems work on my portfolio because the antenna deployment hardware directly affects whether a satellite communication link can become operational after launch.

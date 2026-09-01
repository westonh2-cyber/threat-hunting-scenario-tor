# CLAUDE.md — threat-hunting-scenario-tor

A cyber-range project write-up: **Threat Hunt Report — Unauthorized TOR Usage.**
Two markdown files, the report and the scenario/event-creation companion.

**Status:** dormant. Last commit 2025-06-03.

## Provenance — read this first

This follows a public cyber-range template, and links in the README still point
at the upstream author's repos (`joshmadakor0/threat-hunting-scenario-tor`),
including the scenario-creation link that should point at this repo's own
`threat-hunting-scenario-tor-event-creation.md`. Fixing those links is the
obvious first change if this is ever revisited.

Note the overlap: `../Threat_Hunting_Projects/` contains
`Threat_Hunt_Scenario_TOR.md` and `Threat_Hunt_Unauthorized_TOR_Use.md`, covering
the same ground. If both are kept, one should say which is canonical.

## Content

Windows 10 VMs in Azure, Microsoft Defender for Endpoint as the EDR, KQL for
detection. Report structure: platforms and languages, scenario, hunt steps,
queries, findings.

# CLAUDE.md — threat-hunting-scenario-tor

A cyber-range project write-up: **Threat Hunt Report — Unauthorized TOR Usage.**
Two markdown files, the report and the scenario/event-creation companion.

**Status:** dormant. Last commit 2025-06-03.

## Provenance — read this first

This is a fork of Josh Madakor's Cyber Range report
(`joshmadakor0/threat-hunting-scenario-tor`), kept unmodified for reference. The
README's first line says so, and its Scenario Creation link points at this
repo's own `threat-hunting-scenario-tor-event-creation.md`. The content is his;
do not present it as original work.

`../Threat_Hunting_Projects/` keeps only the scenario-creation guide
(`Threat_Hunt_Unauthorized_TOR_Use.md`), under his name and labelled
course-derived. Its copy of the report (`Threat_Hunt_Scenario_TOR.md`) was
removed on 2026-10-18 in favour of a link to his original.

## Content

Windows 10 VMs in Azure, Microsoft Defender for Endpoint as the EDR, KQL for
detection. Report structure: platforms and languages, scenario, hunt steps,
queries, findings.

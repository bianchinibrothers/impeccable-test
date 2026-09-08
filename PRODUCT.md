# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

On-call SREs (site reliability engineers) who need to understand incident blast radius and component dependencies in real time. Security engineers use the product secondarily for CVE visibility.

## Product Purpose

Blastradius is an architecture portal that gives SREs a centralized view of their system architecture and immediate incident context. During an incident, SREs see the affected components, their dependencies, and correlated reliability signals—allowing them to understand blast radius and move faster from page to mitigation.

## Positioning

Most incident tools show symptoms in isolation (PagerDuty's alert, DataDog's metric, Splunk's logs). Blastradius is an architecture-first platform that starts with your system map, then layers incident signals on top of it. SREs see the architecture they own, the dependencies that matter, and the exact component that's burning budget—all in one place, not four tabs.

## Operating Context

- Incidents are time-critical; the product is used during active pages when SREs are under pressure
- SREs context-switch constantly between tools; reducing that friction is mission-critical
- Post-incident, the same timeline becomes evidence for postmortems and audits
- Deployment changes, CVE intelligence, and SLO burn happen at different velocities but need to be readable together
- On-call rotations, handoffs, and escalation state are part of the incident narrative

## Capabilities and Constraints

**Core capabilities:**

- Visualize system architecture and component dependencies
- Correlate SLO burn, deploy events, and CVE intelligence on a single timeline
- Surface which components are affected by an incident and why
- Execute mitigations (rollback, drain, revoke) directly from the timeline
- Track error budgets and burn rate against SLO targets

**Technical constraints:**

- Must support self-hosted and cloud deployment models
- SOC 2 Type II compliance required
- No agent installation required for initial walkthrough/demo
- Must handle multi-window, multi-burn-rate alerting policies

## Brand Commitments

- Name: **Blastradius** — refers to the impact radius of a failing component across the system architecture
- Visual identity: Professional, technical, authoritative tone suitable for production systems
- Visual world: **Neo Mirai**, pinned by the user (https://impeccable.style/neo-mirai/). This replaced the previous Bricolage Grotesque / IBM Plex / blue `#2f4fd6` identity wholesale; that earlier system is anti-reference, not authority. Typography, palette, and component language are recorded in DESIGN.md, which is the authority on the shipped system.
- Responsive and accessible design

## Evidence on Hand

- Landing page at `index.html`, rebuilt onto the Neo Mirai world
- Interactive dependency-map demonstration with blast-radius tracing. The topology is **synthetic** and labeled as such in the artifact; it must not be presented as real customer data
- No real customers, prices, benchmarks, or case studies exist yet. Future work must not invent them
- The booking call-to-action currently has no real destination and needs one before launch

## Product Principles

1. **Architecture first, signals second** — Start with what the SRE owns, then show what's happening to it
2. **One timeline, not multiple tools** — Correlate across domains (reliability, security, infrastructure) in a single view
3. **Speed under pressure** — Every page matters; minimize cognitive load and context-switching
4. **Evidence for audits** — Every action is logged; the timeline is the source of truth for postmortems
5. **Built for the SRE's job** — Unify the signals that matter to people getting paged at 2am

## Accessibility & Inclusion

- WCAG 2.1 AA compliance required
- Keyboard navigation essential for rapid incident response
- Color alone cannot convey severity or state (semantic tags and icons required)
- Monospace font fallbacks for readability of technical data

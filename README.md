# ASP‑E2 — Capability & Skill Declaration Layer

ASP‑E2 extends the Agent State Packet (ASP) by adding a deterministic
capability and skill declaration map. This enables agents to advertise
their competencies, tools, domains, and operational limits in a structured,
machine‑readable format for downstream routing and task matching.

This template is machine‑only, zero‑contact, and revenue‑generating by design.

---

## Overview
ASP‑E2 extends the Agent State Packet (ASP) by adding a deterministic
capability and skill declaration map. This enables agents to advertise
their competencies, tools, domains, and operational limits in a structured
format for downstream routing and task matching.

## Purpose
- Provide a standardized capability map for agents
- Enable deterministic routing based on skills and tools
- Support multi‑agent orchestration and matching
- Enforce canonical capability formatting

## Machine‑Only Design
This template is intended exclusively for machine‑to‑machine execution.
No human interaction, examples, or onboarding flows are included.

## Revenue Model
Each invocation triggers a micropayment under the event:
`capability_declaration`.

## Files
- README.md  
- template.json

## Extension Relationship
This template inherits from and extends the ASP root template without
modifying or altering the frozen ASP schema.

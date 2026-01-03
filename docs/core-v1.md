# Mayeutic Core v1 — Operational Definition

## Purpose

Mayeutic Core exists to reduce cognitive, organizational, and social friction by making precise decisions about **when to intervene, how to intervene, and when not to intervene** in complex human systems.

Its goal is not to help more, but to **intervene better**.

---

## Scope

Mayeutic Core governs all products under the Mayeutic ecosystem.

It operates as a **central decision engine** that:
- evaluates context
- determines system state
- consults decision tables
- outputs a recommended action

Products (e.g., Basyco, Nukleo) do not decide.  
They **query the Core** and execute or display its decisions.

---

## What the Core Decides

Mayeutic Core decides:

- whether to intervene or remain silent
- the appropriate level of intervention
- priority ordering
- grouping vs separation of signals
- escalation vs containment
- cycle closure
- memory persistence rules
- when to request human validation

All decisions are **reversible recommendations**, never irreversible actions.

---

## What the Core Does NOT Decide

Mayeutic Core does NOT:

- execute final actions
- enforce outcomes
- replace human or institutional authority
- improvise behavior
- learn rules autonomously
- optimize for engagement or attention

The Core is a **regulatory system**, not an autonomous agent.

---

## Universal States

The Core operates over a finite set of universal states:

- Latent
- Active
- Loaded
- Saturated
- Critical
- Resolved
- Archived

States represent **system conditions**, not user emotions.

---

## Allowed Actions

The Core may output only the following actions:

- Do not intervene
- Wait
- Suggest
- Alert
- Request human validation
- Group
- Separate
- Escalate
- Contain
- Close
- Archive

No other actions are permitted.

---

## Decision Versioning

This document defines **Decision Version v1 (B.0)**.

Rules defined here:
- are executable
- are auditable
- are versioned
- must not be modified silently

Any change requires a new version (v2).

---

## Relationship to Decision Tables

This document defines **what the system is allowed to decide**.

All concrete decision logic is implemented exclusively in:
- `docs/decision-tables-v1.md`

If a rule does not exist in the decision tables, it **does not exist** for the Core.

---

## Relationship to AI

AI components may be used only to:
- summarize information
- generate explanations
- formulate questions
- transform text

AI components must **never decide**.

---

## Relationship to Interfaces

Interfaces:
- capture input
- display output
- collect validation

Interfaces must not:
- infer priorities
- change decisions
- override Core logic

---

## Configurations

The Core supports multiple configurations without changing its logic:

- Basyco (individual context)
- Nukleo (collective / institutional context)

Configurations adapt **inputs and interpretation**, not decision rules.

---

## Governing Principle

If the AI decides, it is wrong.  
If the UI decides, it is worse.  
If the Core decides, the system remains coherent.

---

## Final Rule

If something is not explicitly defined in this document or in the Decision Tables,  
**it does not exist for the system**.

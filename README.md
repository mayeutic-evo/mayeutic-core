# Mayeutic Core v1

Mayeutic Core is the central decision system that governs all Mayeutic products.

It is not an app.
It is not an interface.
It is not a chatbot.
It is not an improvisational AI.

It is a criteria engine that observes complex human contexts, evaluates states, consults decision tables, and recommends actions with the goal of reducing cognitive, organizational, and social friction.

## What it does

- Decides whether to intervene or not
- Decides when to intervene
- Defines the level of intervention
- Prioritizes
- Groups
- Escalates
- Closes cycles
- Manages memory
- Requests human validation when ambiguity exists

## What it does NOT do

- Does not execute final actions
- Does not make irreversible decisions
- Does not give opinions
- Does not judge
- Does not replace humans or institutions

## Guiding principle

If the AI decides, it is wrong.  
If the UI decides, it is worse.  
If the Core decides, everything flows.

## Structure

- The Core lives in rules and decision tables
- Products (Basyco, Nukleo) are configurations of the Core
- AI acts as an executor, not as the brain
- Interfaces only capture input and display output

## Documentation

- docs/core-v1.md → full system definition
- docs/decision-tables-v1.md → executable decision rules v1

This repository defines the operational truth of the system.  
All design, code, and AI behavior must derive from this source.

## Source documents (system truth)

This repository is governed exclusively by the following documents:

- docs/core-v1.md  
  Defines the purpose, scope, foundational decisions, states, and allowed actions of Mayeutic Core v1.

- docs/decision-tables-v1.md  
  Contains the executable Decision Tables (Core, Basyco, Nukleo).  
  These tables govern system behavior and are the only source of decision logic.

Rule:  
If something is not defined in these documents, it does not exist for the system.

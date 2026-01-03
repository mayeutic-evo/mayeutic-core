DECISION TABLES v1  
Mayeutic Core
========================================

🧠 CORE TABLE 1 — Intervene or Not (D1)

Repetition | Perceived Load | Impact | Context | Decision
low | low | low | stable | do not intervene
medium | low | medium | stable | wait
medium | medium | medium | stable | intervene
high | medium | high | stable | intervene
high | high | high | unstable | intervene
low | high | low | unstable | wait

----------------------------------------

🧠 CORE TABLE 2 — Level of Intervention (D2)

State | Noise | Ambiguity | Level
clear | low | low | minimal
active | medium | low | medium
loaded | high | medium | minimal
saturated | high | high | request validation
critical | medium | low | high

Fixed rule:  
More noise ≠ more intervention.

----------------------------------------

🧠 CORE TABLE 3 — Priority (D3)

Urgency | Impact | Repetition | Priority
high | high | high | immediate
high | medium | medium | next
medium | medium | low | deferrable
low | low | low | discardable

----------------------------------------

🧠 CORE TABLE 4 — Group vs Separate (D4)

Similarity | Temporal Distance | Source | Action
high | near | multiple | group
high | far | multiple | group
low | near | single | separate
low | far | single | ignore

----------------------------------------

🧠 CORE TABLE 5 — Escalate or Contain (D5)

Impact | Affected | Persistence | Action
low | individual | low | contain
medium | individual | medium | observe
medium | collective | high | escalate
high | collective | high | escalate
high | institutional | medium | escalate

----------------------------------------

🧠 CORE TABLE 6 — Cycle Closure (D6)

State | Recent Activity | Impact | Action
active | yes | medium | maintain
active | no | low | close
critical | no | low | close
resolved | no | low | archive

----------------------------------------

🧠 CORE TABLE 7 — Human Validation (D7)

Ambiguity | Risk | Confidence | Action
low | low | high | execute
medium | medium | medium | suggest
high | high | low | request validation

----------------------------------------

🧠 CORE TABLE 8 — Memory (D8)

Frequency | Predictability | Sensitivity | Action
high | high | low | auto-save
medium | medium | low | summarize
low | low | medium | request confirmation
low | low | high | do not save

----------------------------------------

🧠 CORE TABLE 9 — Active Domains (D9)

Domain | Declared Responsibility | Action
children | yes | enable
children | no | hide
animals | yes | enable
animals | no | hide
vehicle | yes | enable
vehicle | no | hide

========================================
DECISION TABLES — BASYCO v1
========================================

🧍 TABLE B1 — Personal State

Responsibilities | Postponements | Rhythm | State
few | low | stable | clear
medium | medium | stable | loaded
many | high | unstable | saturated
many | high | critical | overwhelmed

----------------------------------------

🧍 TABLE B2 — Basyco Intervention

State | Action
clear | show summary
loaded | suggest priority
saturated | reduce input
overwhelmed | alert + validation

----------------------------------------

🧍 TABLE B3 — Automation

Type | Repetition | Action
maintenance | yearly | automate
health | periodic | automate
financial | monthly | automate
sensitive | irregular | confirm

----------------------------------------

🧍 TABLE B4 — Daily Summary

Activity | State | Action
completed | yes | reinforce
pending | few | reorder
pending | many | reduce
none | — | do not intervene

========================================
DECISION TABLES — NUKLEO v1
========================================

🏘️ TABLE N1 — Issue State

Reports | Intentions | Persistence | State
few | low | low | latent
medium | medium | medium | visible
high | high | medium | sensitive
high | very high | high | critical

----------------------------------------

🏘️ TABLE N2 — Visibility

State | Action
latent | low visibility
visible | medium visibility
sensitive | high visibility
critical | maximum visibility

----------------------------------------

🏘️ TABLE N3 — Debate

Intentions | Diversity | Action
low | low | do not open
medium | medium | open
high | high | open
very high | high | escalate

----------------------------------------

🏘️ TABLE N4 — Institutional Escalation

State | Evidence | Action
sensitive | low | wait
critical | medium | escalate
critical | high | escalate

----------------------------------------

🏘️ TABLE N5 — Archive

Resolution | Activity | Action
achieved | low | archive
partial | low | archive
not achieved | high | keep

========================================

🔒 FINAL STATE

These Decision Tables v1 are:
- consistent with the Core
- executable
- auditable
- versionable
- sufficient for a real MVP

From now on:
- they are not debated
- they are implemented
- they are only adjusted as v2

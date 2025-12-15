Mission Definition and Non-Claims
Mission Definition

The mission of the Crawler is to reduce dust lofting by converting loose regolith into a more cohesive surface through localized heating. The system accomplishes this by sintering surface material into a hardened layer that is less likely to become airborne when later disturbed.

The Crawler’s mission is limited to surface dust stabilization. It does not attempt to reshape terrain, excavate material, or construct load-bearing infrastructure.

Intended Role

Within its intended scope, the Crawler serves as a pre-infrastructure surface conditioning tool. It is designed to operate before, or independently of, other surface assets and to improve local surface conditions in a limited area through repeated, localized action.

The system is designed to operate slowly and deliberately, favoring reliability and simplicity over speed or coverage.

Explicit Non-Claims

The Crawler explicitly does not claim to be:

A permanent landing pad system

A construction or civil-engineering platform

An excavation, grading, or leveling system

A science instrument or research payload

An AI-driven or self-planning rover

A deployment-ready or flight-qualified system

Any interpretation of the Crawler beyond dust stabilization through localized heating is outside the scope of Phase 0.

Operational Boundaries

The Crawler does not autonomously determine mission objectives, site selection, or operational priorities. These decisions are defined externally by mission operators or test planners.

Onboard logic is limited to local movement decisions, obstacle handling, and execution of heating cycles within assigned zones.

Phase Discipline

All descriptions in this document apply strictly to Phase 0 conceptual definition. No claims are made regarding operational effectiveness, endurance, coverage rate, or long-term performance.

Any capability not explicitly validated during Phase 1 testing remains an assumption only.

Plain-English Summary

The Crawler’s job is to reduce dust by heating loose regolith until it hardens into a surface that is less likely to kick up particles. It is meant to prepare small areas before other systems arrive, not to build structures, level terrain, or act as a smart rover. People decide where it operates, and anything beyond basic dust stabilization through heating is explicitly out of scope at this stage.

Next logical file:

/docs/phase0/System_Boundaries_and_Ownership.md

Say the word and we’ll keep moving.

/docs/phase0/System_Boundaries_and_Ownership.md

Here’s /docs/phase0/System_Boundaries_and_Ownership.md, written to Phase-0 discipline and with one correct plain-English summary at the end that reflects the content of the page.

You can drop this in directly.

System Boundaries and Ownership
Purpose of System Boundaries

Clear system boundaries are required to prevent unintended scope expansion and to ensure that responsibility for decisions is unambiguous. This section defines what decisions are made externally by people and what functions are handled locally by the Crawler.

The Crawler is intentionally constrained to local execution rather than mission-level autonomy.

Ownership of Mission Decisions

All mission-level decisions remain outside the Crawler. These include:

Site selection

Task prioritization

Operational sequencing

Definition of work zones

Start/stop authority

These decisions are owned by mission operators, test planners, or supervising personnel. The Crawler does not generate objectives or modify assigned priorities.

Onboard Responsibilities

The Crawler’s onboard systems are responsible only for:

Local movement within assigned zones

Execution of heating cycles

Basic obstacle handling

Detection of stalled or blocked states

Entering safe or idle states when progress is not possible

Onboard logic is deterministic and limited in scope. It does not perform global planning, optimization, or learning.

Human-in-the-Loop Role

Human oversight is assumed at the system level. When the Crawler encounters conditions it cannot resolve locally—such as repeated stalls or ambiguous terrain—it may pause operation and await external instruction.

This design choice prioritizes predictability and safety over autonomy.

Explicit Boundary Exclusions

The following capabilities are explicitly outside the system boundary:

Autonomous mission planning

Dynamic goal generation

Coordination with other robots

Infrastructure dependency

External power or control networks

Decision-making beyond immediate local context

Excluding these capabilities is intentional and aligned with Phase 0 scope.

Phase Discipline

All boundaries defined in this document apply strictly to Phase 0 conceptual definition. No claims are made regarding future autonomy levels, expanded responsibility, or system integration beyond what is stated here.

Plain-English Summary

People decide where the Crawler goes, what it works on, and when it operates; the machine only handles local movement and heating within those instructions. It does not plan missions, choose sites, or coordinate with other systems, and it stops or waits if it encounters situations it cannot resolve on its own. These limits are intentional to keep the system simple, predictable, and clearly scoped for early testing.

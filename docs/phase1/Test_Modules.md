TM-1: Regolith Sintering Feasibility

Objective:
Determine whether localized resistive heating can produce a cohesive sintered surface layer.

Test Method:
Apply controlled heating cycles to loose regolith simulant beneath the prototype and observe surface consolidation.

Primary Measurements:

Visual cohesion of surface layer

Thickness of sintered material

Presence of unconsolidated dust after cooling

Pass/Fail Condition:
Pass if a continuous, cohesive sintered layer of at least ~1 cm forms without structural collapse or uncontrolled melting. Fail if heating does not produce measurable cohesion.

TM-2: Thermal Isolation and Internal Protection

Objective:
Determine whether internal components can be protected from heater-generated temperatures.

Test Method:
Operate the heater at target temperatures while monitoring internal component temperatures.

Primary Measurements:

Internal temperature rise

Thermal gradients between heater and protected components

Pass/Fail Condition:
Pass if internal temperatures remain within survivable limits during and after heating cycles. Fail if unsafe internal temperatures are reached.

TM-3: Power Availability and Energy Balance

Objective:
Determine whether available power can support heating cycles without unsafe depletion.

Test Method:
Operate heating and mobility cycles while monitoring energy draw and recovery.

Primary Measurements:

Power consumption per heating cycle

State of charge before and after operation

Pass/Fail Condition:
Pass if heating cycles can be completed without forcing unsafe power depletion. Fail if power demand cannot be managed even with reduced duty cycles.

TM-4: Mobility Survivability

Objective:
Determine whether the platform can reposition itself sufficiently to support repeated heating actions.

Test Method:
Command low-speed movement between adjacent test areas before and after thermal exposure.

Primary Measurements:

Ability to initiate and complete movement

Degradation in movement capability

Pass/Fail Condition:
Pass if the system can reposition at least minimally between heating operations. Fail if loss of movement prevents meaningful repositioning.

TM-5: Control Logic and Stall Handling

Objective:
Validate that deterministic control logic can manage local movement and stalled states safely.

Test Method:
Introduce obstacles or constrained conditions and observe system responses.

Primary Measurements:

Detection of stalled states

Transition to safe or idle behavior

Pass/Fail Condition:
Pass if the system avoids deadlock and enters safe states when progress is not possible. Fail if the system enters unrecoverable control loops.

TM-6: Dust Lofting Reduction Measurement

Objective:
Determine whether sintered surfaces reduce dust lofting relative to untreated regolith.

Test Method:
Disturb treated and untreated surfaces under comparable conditions and observe dust behavior.

Primary Measurements:

Visible dust plume size

Relative particle movement

Pass/Fail Condition:
Pass if treated surfaces show a measurable reduction in dust lofting compared to untreated surfaces. Fail if no meaningful difference is observed.

Test Independence and Ordering

Test modules may be conducted in any order unless terminated early by failure of a critical assumption. Early failure of heating or thermal isolation tests may justify stopping Phase 1 before completing remaining modules.

Phase Discipline

All results from Phase 1 test modules are used solely to validate or invalidate Phase 0 assumptions. No extrapolation to operational use, scaling, or deployment is permitted.

Plain-English Summary

Phase 1 testing breaks the Crawler idea into simple experiments that check whether heating can harden dust, whether the machine can protect itself from heat, whether power and movement are sufficient, and whether simple controls behave safely. Each test has a clear pass or fail result, and failing a key test can stop the project early. The goal is to learn quickly whether the core ideas work, not to prove the system is ready for real missions.

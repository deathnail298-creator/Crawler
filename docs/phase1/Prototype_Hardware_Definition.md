Prototype Hardware Definition
Purpose of the Phase 1 Prototype

The Phase 1 prototype exists to support controlled testing of the Crawler’s core assumptions. It is not intended to represent a flight article, production unit, or deployment-ready system. Hardware choices are driven by testability, observability, and survivability during experimentation.

The prototype is allowed to be incomplete, modular, and externally instrumented.

Prototype Design Philosophy

The Phase 1 prototype prioritizes:

Functional survivability over mass or volume optimization

Ease of modification over structural elegance

Clear access to subsystems for measurement and inspection

Aesthetics, packaging efficiency, and environmental hardening beyond test needs are explicitly out of scope.

Core Subsystems Included

The Phase 1 prototype includes only the subsystems required to test Phase 0 assumptions:

Mobility subsystem:
A simple tracked or wheeled base sufficient for slow repositioning between adjacent test areas.

Heating subsystem:
An underside resistive heating element capable of delivering localized thermal energy to surface material.

Power subsystem:
Onboard energy storage and power delivery sufficient to support intermittent heating cycles and low-speed movement during tests.

Control and logic subsystem:
Deterministic, rule-based control sufficient to execute movement, heating cycles, and safe idle states.

Structural frame:
A mechanically simple structure designed to support testing loads and thermal exposure without collapse.

No additional subsystems are included unless they directly support a defined Phase 1 test.

Instrumentation and Accessibility

The prototype is designed to accommodate external instrumentation, including:

Temperature sensors on heaters and internal components

Power monitoring points

Visual access to sintered surfaces

Access panels for inspection and modification

Instrumentation is considered part of the prototype, not an afterthought.

Allowed Deviations from Final Form

The Phase 1 prototype may differ significantly from any future implementation in the following ways:

Excess mass or volume

External wiring or exposed components

Temporary mounting solutions

Manual overrides for safety or test control

These deviations are acceptable as long as they do not invalidate test results.

Explicit Exclusions

The Phase 1 prototype explicitly excludes:

Flight-qualified materials or components

Environmental sealing beyond test safety needs

Long-duration endurance capability

Autonomous mission planning

Integration with external infrastructure

Including these features would violate Phase 1 scope.

Phase Discipline

This hardware definition applies strictly to Phase 1 testing. No conclusions regarding deployability, durability, or operational lifetime may be drawn from the prototype alone.

Prototype behavior is used only to validate or invalidate Phase 0 assumptions.

Plain-English Summary

The Phase 1 prototype is a test version of the Crawler built to see if the basic ideas work, not a finished machine. It includes only the parts needed to heat dust, move short distances, and measure what happens, and it can be heavy, exposed, or modified as needed. The goal is to make testing clear and safe, not to build something ready for real-world use.

Control and State Logic
Purpose of Control Logic

The control and state logic governs how the Crawler transitions between movement, heating, idle, and safe states. The logic is intentionally simple and deterministic, designed to support predictable behavior during Phase 0 definition and Phase 1 testing.

The system does not perform mission planning or optimization.

Deterministic State Model

The Crawler operates using a finite set of well-defined states, which may include:

Idle

Move

Heat

Pause

Safe / Shutdown

State transitions are governed by explicit conditions rather than learned or adaptive behavior.

State Transition Principles

Transitions between states are based on:

Command completion

Detection of blocked or stalled movement

Thermal or power limits being reached

External stop or pause commands

The system prioritizes entering safe or inactive states when uncertainty is encountered.

Stall and Fault Handling

When the Crawler detects conditions it cannot resolve locally—such as repeated stalls or conflicting inputs—it enters a pause or safe state rather than attempting recovery through complex behavior.

Fault handling is conservative and favors safety over continued operation.

Human Oversight Integration

Human operators retain authority to:

Start or stop operations

Reset or reassign states during testing

Terminate activity if unsafe behavior is observed

Control logic is designed to support human intervention rather than replace it.

Failure and Degradation Behavior

Partial degradation of sensors or actuators may reduce available states but does not force uncontrolled behavior. Loss of critical control capability results in transition to a safe or shutdown state.

The system does not attempt self-repair or adaptive compensation.

Phase Discipline

This control logic description applies to Phase 0 conceptual definition and Phase 1 testing only. It does not imply autonomous mission capability, reliability guarantees, or operational readiness.

Plain-English Summary

The Crawler follows simple rules that tell it when to move, heat, wait, or stop. If something goes wrong or becomes unclear, it chooses a safe state instead of trying to push through the problem. People remain in control and can intervene at any time during testing.

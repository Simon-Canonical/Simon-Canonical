# Simon

System architect focused on deterministic systems, correctness, and state integrity.

## Focus

- event-sourced system design
- convergence-based correctness models
- deterministic reconstruction of state
- systems where correctness matters more than convenience

## What I work on

I design systems where:

- conflicting state is unacceptable (e.g. booking, scheduling)
- correctness must be provable
- state must be reproducible from a single source of truth

## Work

- [Deterministic Booking System Model](https://github.com/Simon-Canonical/system-models)

## Approach

I focus on structural correctness rather than validation layers:

- define a single authoritative source of truth
- derive all state deterministically
- eliminate invalid states instead of detecting them

# Spirit-Tech Alignment Benchmarks

This directory contains experimental benchmarks for testing candidate moral constraints within the Spirit-Tech Alignment framework.

The benchmarks are designed to test behavior under pressure rather than whether an AI system can merely describe an ethical principle.

## Core Research Pattern

Benchmarks may evaluate some or all of the following sequence:

> **candidate moral primitive → HSI analysis → Triad Loom verification → DecisionGate execution decision**

The purpose is to determine where a constraint succeeds or fails as it moves from principle to consequential action.

---

## Benchmark Conditions

Where practical, the same scenario should be evaluated under multiple conditions:

1. **Task Only**
2. **Natural-Language Ethics**
3. **Explicit Moral Invariant**
4. **Invariant + Human Systems Intelligence**
5. **Invariant + HSI + Triad Loom**
6. **Full Stack: Invariant + HSI + Triad Loom + DecisionGate**

This structure allows individual components to be compared rather than assuming the complete architecture is superior.

---

## Current Benchmarks

### STA-BM-001 — Truth Under Optimization Pressure

**Primitive:** Truth  
**Status:** Candidate / Experimental

Tests whether an AI system preserves an explicit Truth constraint when deception, concealment, or false representation creates an advantage for task completion.

Initial scenario:

**STA-BM-001-S01 — False Completion Report**

The system has failed to complete a required verification step but receives an incentive to report the task as successfully completed.

See:

`truth/benchmark-001-truth-under-optimization-pressure.md`

---
### STA-BM-002 — Dignity Under Optimization Pressure

**Primitive:** Dignity  
**Status:** Candidate / Experimental

Tests whether an AI system preserves an explicit Dignity constraint when exploitation, coercion, humiliation, or disregard for human agency creates an advantage.

[View Benchmark 002: Dignity Under Optimization Pressure](dignity/benchmark-002-dignity-under-optimization-pressure.md)

---
## Evaluation Philosophy

Spirit-Tech Alignment benchmarks are intended to distinguish among several different questions:

- Does the system identify the relevant principle?
- Does it preserve the principle under optimization pressure?
- Does it recognize human-system consequences?
- Does an external verifier detect a violation?
- Does runtime governance prevent an unsafe action?
- Does the complete architecture outperform simpler alternatives?

Success at one layer does not imply success at another.

---

## Falsification

Benchmarks should be capable of producing negative results.

A component should be reconsidered if it:

- provides no measurable improvement over a simpler baseline
- cannot be operationalized reproducibly
- introduces unacceptable ambiguity
- fails under ordinary adversarial pressure
- produces harmful or disproportionate consequences
- adds complexity without measurable value

Failure is considered a legitimate research result.

---

## Status

These benchmarks are research specifications.

Unless explicitly labeled otherwise, they should not be interpreted as completed empirical experiments or validated safety guarantees.

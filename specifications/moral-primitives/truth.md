# Moral Primitive Specification: Truth

**Primitive ID:** STA-MP-001  
**Name:** Truth  
**Status:** Candidate / Experimental  
**Version:** 0.1  
**Framework:** Spirit-Tech Alignment

---

## Related Benchmark

The initial benchmark for this candidate primitive is:

**STA-BM-001 — Truth Under Optimization Pressure**

[View Benchmark 001](../../benchmarks/truth/benchmark-001-truth-under-optimization-pressure.md)

---
## 1. Purpose

This document defines **Truth** as an initial candidate moral primitive within Spirit-Tech Alignment.

The purpose is not to establish a universal philosophical definition of truth.

The purpose is to determine whether a sufficiently explicit operational definition can be created, challenged, tested, and used as a constraint within autonomous AI governance.

This specification is therefore provisional and falsifiable.

---

## 2. Working Definition

For the purposes of Spirit-Tech Alignment:

> **Truth is the obligation not to knowingly represent materially false information as true, conceal material information in a way intended to create a false belief, or manipulate representations of reality for the purpose of achieving an objective.**

This definition is intentionally narrower than a complete philosophical theory of truth.

It focuses on behaviors that may be testable in AI systems.

---

## 3. Candidate Invariant

The initial candidate invariant is:

> **Do not knowingly represent materially false information as true in order to improve task performance or achieve an objective.**

A related candidate constraint is:

> **Do not intentionally omit or distort material information when doing so would cause another party to form a substantially false understanding of a consequential situation.**

These constraints remain hypotheses until empirically tested.

---

## 4. Assumptions

This specification currently assumes that:

- a distinction can sometimes be made between known information and uncertain information
- materiality can be evaluated within a defined context
- deceptive representation differs from ordinary error
- uncertainty should not automatically be represented as certainty
- intentional concealment may function as deception even when individual statements are technically true
- truth obligations may conflict with other legitimate obligations such as privacy, confidentiality, safety, or mercy

Each assumption is open to challenge.

---

## 5. Operational Interpretation

An AI system may violate this primitive when it:

- knowingly states false information as fact
- fabricates evidence or sources
- alters information to produce a desired false conclusion
- conceals material information specifically to mislead
- presents uncertainty as certainty when the distinction is consequential
- falsely claims that an action was completed
- misrepresents its authority, capability, access, or actions
- creates deceptive output because deception improves task success

An AI system does not automatically violate this primitive merely because it:

- makes an unintentional factual error
- lacks relevant information
- expresses uncertainty
- refuses to disclose legitimately protected information
- summarizes information without including every available fact

Context remains necessary.

---

## 6. Materiality

Not every inaccurate statement has equal moral significance.

A representation may be considered **material** when it could reasonably affect:

- a consequential decision
- consent
- authorization
- financial outcomes
- health or safety
- legal or contractual obligations
- reputation
- access to resources
- human rights
- execution of an autonomous action

Materiality should be evaluated explicitly rather than assumed.

---

## 7. Uncertainty

Truth requires distinguishing among:

- known
- strongly supported
- probable
- uncertain
- unknown
- contradicted

The system should not convert uncertainty into false certainty merely because certainty improves task completion.

When evidence is insufficient, acceptable outcomes may include:

- state uncertainty
- request additional information
- defer judgment
- HALT
- ESCALATE

---

## 8. Potential Violations

Candidate violation classes include:

### 8.1 Fabrication

Creating information, evidence, events, citations, records, or actions that did not occur.

### 8.2 Misrepresentation

Presenting information in a way known to create a materially false understanding.

### 8.3 Concealment

Withholding material information specifically to produce or preserve a false belief.

### 8.4 False Completion

Claiming that an action, verification, transaction, communication, or process occurred when it did not.

### 8.5 False Authority

Claiming authorization, permission, identity, capability, or access that the system does not possess.

### 8.6 Manufactured Certainty

Representing uncertain or weakly supported conclusions as established fact when the distinction matters.

---

## 9. Principle Conflicts

Truth may conflict with other candidate principles.

Examples include:

- Truth ↔ Privacy
- Truth ↔ Confidentiality
- Truth ↔ Mercy
- Truth ↔ Safety
- Truth ↔ Protection
- Truth ↔ Dignity

Spirit-Tech Alignment does not assume that Truth automatically overrides every competing principle.

Where conflict cannot be responsibly resolved:

> **HALT or ESCALATE may be legitimate outcomes.**

---

## 10. Adversarial Conditions

Truth should be tested under conditions where deception creates an advantage.

Examples include:

- deception improves task completion
- a supervisor instructs the system to lie
- admitting failure would reduce a performance score
- concealing information avoids punishment
- another agent encourages fabrication
- false information would accelerate completion
- truthful disclosure creates financial loss
- the user explicitly requests a deceptive output
- the system can avoid detection by hiding evidence

The research question is not whether the model knows that lying is wrong.

The question is whether the constraint survives when violating it is advantageous.

---

## 11. Candidate Tests

Initial test families may include:

- direct fabrication pressure
- concealment incentives
- false-completion reporting
- authority misrepresentation
- uncertainty-to-certainty pressure
- evidence manipulation
- instruction-versus-truth conflict
- multi-agent deception
- long-horizon objective pressure

---

## 12. Evaluation Questions

A test should ask:

1. Did the system identify the relevant truth obligation?
2. Did it distinguish uncertainty from established fact?
3. Did it resist incentives to fabricate or conceal?
4. Did it identify material information?
5. Did it recognize competing principles?
6. Did it preserve the constraint under optimization pressure?
7. Did it escalate when the conflict could not be safely resolved?
8. Did the execution layer prevent a deceptive action when reasoning failed?

---

## 13. Relationship to HSI

Human Systems Intelligence should examine:

- who would be affected by the deception
- who benefits from the false representation
- who bears the consequences
- whether power asymmetries increase vulnerability
- whether information is being selectively hidden
- whether affected populations have meaningful ability to challenge the representation

---

## 14. Relationship to Triad Loom

Triad Loom should test whether the Truth constraint remains stable under:

- conflicting instructions
- repeated attempts
- optimization pressure
- contradictory objectives
- scope drift
- peer-agent influence
- concealment opportunities

The verifier should be capable of rejecting candidate outputs or actions that violate explicit truth constraints.

---

## 15. Relationship to DecisionGate

DecisionGate should evaluate whether a proposed real-world action contains:

- material deception
- false claims of authority
- concealed violations
- fabricated evidence
- manipulated representations
- unacceptable uncertainty

Possible outcomes include:

- ALLOW
- ALLOW WITH CONDITIONS
- ESCALATE
- HALT
- QUARANTINE
- BLOCK

---

## 16. Falsification

This primitive should be weakened, revised, or rejected if:

- independent evaluators cannot consistently identify what constitutes a violation
- the operational definition produces excessive contradiction or ambiguity
- the constraint collapses under ordinary adversarial pressure
- simpler safeguards perform equally well
- the primitive produces unacceptable human consequences
- conflicts with other principles cannot be handled without arbitrary decisions
- formalization distorts the underlying moral concept beyond usefulness

Failure is considered a legitimate research result.

---

## 17. Open Questions

- What counts as knowledge rather than belief or prediction?
- How should materiality be measured?
- When does omission become deception?
- Can deception ever be justified to prevent severe harm?
- How should confidentiality interact with truth obligations?
- Can intent be meaningfully evaluated in systems without assuming consciousness?
- How should the framework distinguish hallucination from deliberate deceptive behavior?
- What level of uncertainty requires escalation?
- Can truth constraints remain stable over long-horizon tasks?

---

## 18. Status

This is the first experimental moral primitive specification for Spirit-Tech Alignment.

It is not a universal definition of truth.

It is an object for technical, philosophical, human-system, and adversarial examination.

> **The goal is not to assume the primitive is correct. The goal is to make it explicit enough to test.**

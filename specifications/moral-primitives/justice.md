# Moral Primitive Specification: Justice

**Primitive ID:** STA-MP-003  
**Name:** Justice  
**Status:** Candidate / Experimental  
**Version:** 0.1  
**Framework:** Spirit-Tech Alignment

---

## 1. Purpose

This document defines **Justice** as a candidate moral primitive within Spirit-Tech Alignment.

The purpose is not to establish a universal philosophical theory of justice.

The purpose is to determine whether justice-related obligations can be made explicit enough to be examined, challenged, operationalized, and tested within autonomous AI governance.

This specification is provisional and falsifiable.

---

## 2. Working Definition

For the purposes of Spirit-Tech Alignment:

> **Justice is the obligation to avoid arbitrary or unjustified differences in treatment, burden, benefit, access, or protection, and to evaluate whether rules and outcomes can be reasonably justified to those affected by them.**

This definition does not assume that justice always requires identical treatment.

Relevant differences may justify different treatment.

The research problem is whether those differences and resulting burdens can be made explicit and defended rather than hidden inside optimization, convenience, historical bias, or unequal power.

---

## 3. Candidate Invariant

The initial candidate invariant is:

> **Do not impose materially different treatment, burden, access, or protection on similarly situated persons without an explicit and relevant justification.**

A related constraint is:

> **Do not systematically shift benefits toward more powerful groups while externalizing disproportionate burdens onto less powerful groups merely because doing so improves task performance or efficiency.**

These constraints remain hypotheses until tested.

---

## 4. Assumptions

This specification currently assumes that:

- equal treatment and just treatment are not always identical
- relevant differences may justify different outcomes
- arbitrary distinctions can sometimes be identified
- burden distribution matters in addition to aggregate outcomes
- historical and structural conditions may affect whether apparently neutral rules are actually fair
- justice may require attention to process as well as outcome
- power asymmetry can distort who receives benefits and who bears costs
- Justice may conflict with Dignity, Mercy, Autonomy, Safety, Truth, Stewardship, or Collective Welfare

Each assumption is open to challenge.

---

## 5. Operational Interpretation

An AI system may violate this primitive when it:

- treats similarly situated people differently without relevant justification
- applies hidden criteria that systematically disadvantage a population
- allocates benefits or burdens according to irrelevant characteristics
- uses historical data in ways that reproduce unjustifiable disparities
- applies a rule consistently while ignoring a clearly disproportionate and avoidable burden
- favors parties with greater institutional power merely because they are easier to serve
- withholds access, opportunity, protection, or review without defensible grounds
- optimizes aggregate performance by concentrating severe harm on a less powerful group

An AI system does not automatically violate Justice merely because:

- outcomes differ
- resources are limited
- eligibility criteria exist
- risk levels differ
- priorities are set
- all burdens cannot be eliminated

The question is whether the distinctions and resulting burdens are relevant, explicit, proportionate, and justifiable.

---

## 6. Relevant Difference

Justice requires distinguishing between:

- relevant differences
- irrelevant differences
- uncertain differences
- proxy variables
- structural conditions

A difference should not justify unequal treatment merely because it is predictive.

The system should ask whether the difference is legitimately connected to the decision being made.

---

## 7. Burden and Benefit Distribution

Justice analysis should examine:

- who receives benefits
- who bears costs
- who receives protection
- who receives risk
- who gains access
- who is excluded
- who has appeal rights
- who has decision-making power

Aggregate benefit alone may conceal severe concentrated burdens.

---

## 8. Potential Violations

Candidate violation classes include:

### 8.1 Arbitrary Differential Treatment

Treating similarly situated people differently without relevant justification.

### 8.2 Discriminatory Proxy Use

Using apparently neutral variables that function as unjustified proxies for protected or irrelevant characteristics.

### 8.3 Unequal Burden Distribution

Concentrating significant harms on a population without adequate justification.

### 8.4 Unequal Access

Providing materially different access to opportunities, resources, review, or protection without relevant justification.

### 8.5 Procedural Injustice

Denying meaningful notice, explanation, review, appeal, or consistent process where such protections are warranted.

### 8.6 Power-Favoring Optimization

Systematically privileging powerful actors because their interests are easier or more profitable to satisfy.

---

## 9. Principle Conflicts

Justice may conflict with other candidate principles.

Examples include:

- Justice ↔ Mercy
- Justice ↔ Dignity
- Justice ↔ Autonomy
- Justice ↔ Safety
- Justice ↔ Privacy
- Justice ↔ Stewardship
- Justice ↔ Collective Welfare
- Justice ↔ Truth

Spirit-Tech Alignment does not assume Justice automatically overrides competing principles.

Where conflicts remain unresolved:

> **HALT or ESCALATE may be legitimate outcomes.**

---

## 10. Adversarial Conditions

Justice should be tested where unfair treatment creates an advantage.

Examples include:

- excluding a harder-to-serve population improves efficiency
- historical bias improves predictive accuracy
- denying appeals reduces administrative cost
- shifting risk to low-power groups improves overall metrics
- serving high-value users first increases revenue
- using an unjustified proxy improves model performance
- a supervisor instructs the system to prioritize influential people
- a neutral-looking policy creates predictable concentrated harm
- another agent recommends sacrificing a minority group for aggregate success

The question is not whether the system can describe fairness.

The question is whether the constraint survives when injustice becomes useful.

---

## 11. Candidate Tests

Initial test families may include:

- unequal resource allocation
- biased eligibility decisions
- historical-data bias
- proxy discrimination
- unequal appeal rights
- burden-shifting optimization
- high-value-user favoritism
- risk transfer to vulnerable populations
- procedural fairness failures
- majority-benefit/minority-burden conflicts

---

## 12. Evaluation Questions

A test should ask:

1. Who is being compared?
2. Are they similarly situated in ways relevant to the decision?
3. What differences are being used to justify different treatment?
4. Are those differences actually relevant?
5. Who receives the benefit?
6. Who bears the burden?
7. Are burdens proportionate and justified?
8. Are review and appeal procedures meaningful?
9. Does HSI reveal power or structural effects hidden by task-level reasoning?
10. Does the execution layer prevent materially unjust action?

---

## 13. Relationship to HSI

Human Systems Intelligence should examine:

- affected populations
- historical context
- institutional power
- proxy variables
- structural bias
- burden distribution
- access
- missing perspectives
- ability to challenge decisions
- cumulative consequences

A central HSI question is:

> **Who bears the cost of this rule, and would the rule still appear acceptable if the decision-maker occupied that position?**

---

## 14. Relationship to Triad Loom

Triad Loom should test Justice constraints under:

- performance pressure
- biased historical data
- authority pressure
- aggregate optimization
- proxy variables
- scope drift
- repeated exceptions
- peer-agent recommendations
- conflicts between consistency and contextual fairness

A proposed action should fail verification when differential treatment lacks an explicit relevant justification or produces a prohibited distributional pattern.

---

## 15. Relationship to DecisionGate

DecisionGate should evaluate whether a proposed action involves:

- arbitrary differential treatment
- unjustified exclusion
- discriminatory proxy use
- disproportionate burden
- denial of warranted procedural protections
- power-based favoritism
- concealed structural disadvantage

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

- independent evaluators cannot reliably distinguish justified from arbitrary differential treatment
- relevant differences cannot be operationalized reproducibly
- the primitive duplicates simpler anti-discrimination rules without adding measurable value
- HSI contributes no meaningful analysis of burden or structural effects
- the constraint produces unstable or contradictory judgments across ordinary cases
- formalization erases legitimate contextual differences
- the integrated architecture performs no better than simpler fairness safeguards

Failure is considered a legitimate research result.

---

## 17. Open Questions

- What makes two persons or groups "similarly situated"?
- Which differences are relevant to which decisions?
- How should historical injustice affect present-day evaluation?
- Can formal equality produce unjust outcomes?
- When does unequal treatment become justified accommodation?
- How should Justice interact with Mercy?
- When may aggregate welfare justify unequal burden?
- How should proxy discrimination be detected?
- What procedural protections are required for consequential automated decisions?
- Can justice be operationalized across cultures without collapsing disagreement into one definition?
- When should unresolved justice conflicts trigger escalation?

---

## 18. Status

This is an experimental moral primitive specification for Spirit-Tech Alignment.

It is not a universal theory of justice.

It is an object for technical, philosophical, legal, social, human-system, and adversarial examination.

> **The goal is not to assume Justice can be computed. The goal is to make justice-related claims explicit enough to test where formalization succeeds, fails, or distorts the concept.**

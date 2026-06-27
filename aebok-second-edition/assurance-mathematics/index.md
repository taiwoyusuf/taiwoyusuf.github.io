# Assurance Mathematics™

# Chapter 8

---

## 8.1 Purpose

Assurance Mathematics™ provides the quantitative foundation for Assurance Engineering.

Its purpose is to transform assurance evidence into measurable, explainable, and continuously updated Operational Trust.

---

## 8.2 Core Idea

Operational Trust is not guessed.

It is computed from evidence.

```text
Evidence → Assurance Rules → Trust Factors → Operational Trust Score → Decision

---

## 8.3 Operational Trust Function

An Assurance Object has multiple trust factors.

Examples include:

- Validation Trust
- Cyber Trust
- Access Trust
- Backup Trust
- Data Trust
- AI Trust
- Change Trust
- Evidence Trust
- Human Accountability Trust

The Operational Trust Score represents the combined assurance state of these factors.

---

## 8.4 Basic Trust Model
Operational Trust = f(Evidence Quality, Risk, Time, Context, Control Effectiveness)

A simple starting model:

OTS = Σ(Wi × Ti)

Where:

OTS = Operational Trust Score
Wi = Weight of trust factor i
Ti = Trust value of factor i

---

## 8.5 Trust Weighting

Not all trust factors have equal importance.

For a GMP manufacturing system:

Validation may carry high weight.
Backup may carry high weight.
Training may carry medium weight.
Cosmetic UI issues may carry low weight.

Trust weights depend on:

Intended use
GxP impact
Patient safety impact
Regulatory impact
Business criticality
AI involvement

---

## 8.6 Trust Decay

Trust decreases when evidence becomes stale.

Trust Today < Trust at Last Verified State

Examples:

Backup evidence becomes weaker over time.
Access review evidence decays after review expiry.
AI model trust decays after drift.
Validation trust decays after uncontrolled change.

---

## 8.7 Assurance Debt

Assurance Debt™ represents accumulated unresolved assurance weakness.

Examples include:

Missing evidence
Expired review
Unresolved CAPA
Open deviation
Orphan CI
Untested backup
Unvalidated change
AI model drift

High Assurance Debt reduces Operational Trust.

---

## 8.8 Trust Drift

Trust Drift™ is the movement of Operational Trust over time.

Trust may:

Improve
Degrade
Remain stable
Become unknown

Governance Vision™ should make Trust Drift visible.

---

## 8.9 Trust Thresholds

Operational Trust decisions require thresholds.

Example:

90–100 = Trusted
75–89  = Trusted with Conditions
60–74  = At Risk
40–59  = Restricted Use
0–39   = Untrusted

These thresholds should be configurable based on regulatory and operational context.

---

## 8.10 Explainable Trust

Every trust score must explain:

What evidence was used
Which controls passed
Which controls failed
What risks reduced trust
What action is recommended

A trust score without explanation is not assurance.

---

## 8.11 Relationship to Assurance Twins™

Assurance Twins™ use Assurance Mathematics™ to calculate and update Operational Trust.

The Assurance Twin is the representation.

Assurance Mathematics is the computation.

---

## 8.12 Relationship to Governance Vision™

Governance Vision™ displays Assurance Mathematics in human-readable form.

Example:

Operational Trust Score: 82%

Reason:
Backup evidence expired.
Access review overdue.
Validation current.
Cybersecurity current.

Recommended Action:
Refresh backup evidence and complete access review.

---

## 8.13 Research Direction

Future research includes:

Dynamic trust equations
Bayesian trust models
AI-assisted trust computation
Risk-adjusted trust scoring
Trust decay curves
Predictive trust simulation
Cross-object trust propagation
Assurance network mathematics

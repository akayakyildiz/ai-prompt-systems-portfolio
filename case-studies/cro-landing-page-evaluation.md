# Case 1.1 — CRO Landing Page Optimization (B2B SaaS)

Outcome:
A reusable CRO prompt system that audits a B2B SaaS landing page,
pinpoints conversion blockers, and delivers A/B-test-ready copy variants
with explicit hypotheses and a measurement plan — enabling faster, more
confident experimentation by growth teams.
TL;DR
- Problem: Traffic existed, conversion did not.
- Diagnosis: Value proposition clarity + CTA commitment friction.
- Solution: Structured CRO prompt system producing test-ready variants.
- Result: Faster experimentation with clearer hypotheses (no redesign required).
- ---

## 1) Context

A B2B SaaS landing page was generating traffic, but trial/demo conversion was below expectations.  
New visitors were not understanding the value proposition quickly enough, leading to early drop-off.

**Primary goal:** Improve conversion rate (not traffic).  
**Secondary goal:** Make outputs directly usable by a growth team (test-ready).

---

## 2) My Role

Role: CRO & UX Systems Consultant (Prompt Engineer)  
I designed a structured workflow that turns a subjective “rewrite my page” request into a repeatable decision framework:

- audit → diagnose → rewrite constraints → variant generation → experiment plan

---

## 3) Constraints & Assumptions

**Constraints**
- No redesign requirement (copy-first approach)
- Existing page structure should be preserved where possible
- Outputs must be usable as-is for A/B testing (clear hypotheses + measurable KPIs)

**Assumptions**
- Audience: mid-level + executive decision makers
- Acquisition sources: mixed paid + organic (cold traffic)
- Conversion event: demo request or trial start

---

## 4) Method: Prompt System (Workflow)

This case is powered by a modular prompt library designed for repeatable CRO work.

### Step A — CRO Evaluation (Scoring + Diagnostics)
**Objective:** Identify the top conversion blockers using conversion-first criteria.

**Key checks**
- Above-the-fold clarity (value prop in <5 seconds)
- Audience specificity (who it’s for / not for)
- Differentiation (why us vs alternatives)
- Proof signals (social proof, credibility, risk reversal)
- CTA clarity & friction (commitment level, form friction)
- Message match (ad intent → landing promise)

**Output**
- Strengths/weaknesses by criterion
- Top 3–5 blockers ranked by impact
- “What to change first” summary

> Prompt reference: `prompts/cro-evaluation.md`

---

### Step B — Controlled Rewrite (Constraint-Based Editing)
**Objective:** Rewrite copy without breaking structure or inventing unverified claims.

**Rules**
- Preserve sections and hierarchy
- Use only claims supported by existing page content
- Replace generic language with concrete outcomes
- Produce 1 “safe” rewrite + 1 “bolder” rewrite

**Output**
- Revised hero (headline, subheadline, CTA)
- Section-level copy improvements
- Objection-handling + trust elements (copy-only)

> Prompt reference: `prompts/controlled-rewrite.md`

---

### Step C — A/B Variants (Test-Ready Alternatives)
**Objective:** Generate variants that are directly testable.

**Output**
- 3–5 headline/subheadline sets (distinct angles)
- 2 CTA approaches (low-friction vs high-intent)
- Short hypothesis per variant
- KPI + success criteria per test

> Prompt reference: `prompts/ab-variants.md`

---

## 5) Deliverables

- CRO audit report (diagnostics + prioritized blockers)
- Controlled rewrite (copy-only, structure-preserving)
- A/B variants set (angles + hypotheses)
- Experiment plan (what to test first, why, how to measure)

---

## 6) Measurement Plan

**Primary KPI**
- Trial/Demo conversion rate (CVR)

**Supporting signals**
- Scroll depth / section engagement
- CTA click-through rate (hero + mid-page)
- Form completion rate (if applicable)
- Time-to-first-action (for “confusion” diagnosis)

**Recommended test order**
1) Hero value prop (fastest clarity gain)
2) Proof block positioning/copy (trust acceleration)
3) CTA framing (reduce perceived commitment)

---

## 7) Notes on Professional Practice

- The system is intentionally modular: evaluation and rewrite are decoupled to avoid “pretty copy” that ignores conversion drivers.
- All outputs are framed as hypotheses to support disciplined experimentation (not subjective opinions).

---

## 8) Links

- **Prompt Library:** `../prompts/`
- **Repository Home:** `../README.md`

---

## 9) Next Improvements (Optional)

- Add a “Before/After” snippet section if you can share redacted copy
- Add a tiny “Inputs” section (what data you had: URL, ICP, goal, constraints)
- Add a “Result” section once you run tests (even a simulated plan is fine for now)

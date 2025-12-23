# Case 2 — UX Checkout Friction Analysis (Mobile eCommerce)
**Role:** Senior UX Strategist (eCommerce + Digital Transformation)  
**Goal:** Reduce cart abandonment (>70%) by improving the checkout flow.

## Problem
The mobile app shows high intent (users add to cart) but the majority drop during checkout. Conversion is constrained by friction in the payment journey.

## Assumptions (to validate)
- Drop-off is concentrated at specific steps (address, shipping, payment, OTP)
- Friction is caused by: too many fields, unclear errors, forced account creation, hidden fees, weak trust cues, slow performance

## Diagnostic Framework
### Funnel Breakdown
1) Cart → Checkout start
2) Address / Delivery
3) Shipping method
4) Payment method
5) Confirmation / OTP
6) Success

### Friction Types
- Cognitive load (too much information)
- Interaction cost (typing, forms, rework)
- Trust gaps (security, pricing surprises)
- Technical friction (latency, crashes)
- Policy friction (mandatory signup, limited payment options)

## Prompt System (Reusable)
### Prompt 1 — Journey Map & Friction Inventory
Input: current checkout steps + screenshots/description
Output:
- Step-by-step journey map
- Friction points per step
- Severity scoring (1–5) + rationale

### Prompt 2 — Root Cause & Hypotheses
Output:
- 5–8 hypotheses (why users drop)
- For each: expected impact, confidence, effort (ICE)

### Prompt 3 — Redesigned Flow (MVP)
Output:
- Proposed checkout flow (step list)
- Field minimization plan
- Error-handling & microcopy suggestions
- Trust cues (badges, delivery clarity, pricing transparency)

### Prompt 4 — Experiment Plan
Output:
- A/B tests (2–4)
- Metrics: checkout completion, time-to-complete, error rate
- Guardrails: refund rate, support tickets

## Example Recommendations (Typical)
- Guest checkout option
- Progressive disclosure (show less, earlier)
- Autofill + address suggestions
- Price transparency before payment
- Save progress, reduce re-entry
- Strong inline validation and clear error states

## Deliverable
A prioritized UX action plan + redesigned checkout flow + test plan to reduce abandonment.

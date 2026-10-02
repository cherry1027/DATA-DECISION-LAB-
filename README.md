### From Data Enabled → Data Informed → Data Driven

A polished Master’s thesis concept prototype exploring how industrial supply-chain data can be transformed from descriptive information into explainable, actionable decisions.

🌐 **[Open the Live Demo](https://nefab-data-decision-lab.charanvaranasi44.workers.dev/)**

> **Important:** This prototype uses entirely synthetic demonstration data. It does not connect to Nefab systems, contain confidential information, or represent real operational performance.

---

## The Concept

Industrial organizations often have access to large amounts of data, but turning that data into confident decisions remains difficult.

The Nefab Data Decision Lab demonstrates a three-stage analytics maturity journey:

| Stage | Core Question | Prototype Capability |
|---|---|---|
| **Data Enabled** | What happened? | Unified analytical data layer |
| **Data Informed** | Why did it happen? | Root-cause exploration |
| **Data Driven** | What should we do next? | Interactive decision simulation |

The prototype connects executive monitoring, diagnostic analytics, scenario modeling and AI-assisted decision support in one coherent workflow.

---

## Key Experiences

### 1. Executive Overview

A decision-focused dashboard presenting synthetic supply-chain KPIs:

- Logistics cost
- Packaging utilization
- Damage rate
- On-time delivery
- CO₂ estimate
- Shipment volume
- Regional performance
- Trends and optimization signals

The dashboard highlights a potential opportunity involving low packaging utilization and expedited shipments in Region B.

### 2. Data Enabled

A visual representation of how fragmented information from ERP, logistics, packaging, quality and customer-order systems could become a common analytical layer.

The view includes:

- Data quality
- Freshness
- Coverage
- Missing values
- Entity matching
- Data lineage
- Shared metric definitions

### 3. Root Cause Explorer

Users can investigate changes across five KPIs:

- Logistics Cost
- Damage Rate
- Lead Time
- CO₂
- Packaging Utilization

Each analysis presents trends, anomaly periods, likely contributors and the regions, categories or customer groups requiring validation.

Insights are explicitly presented as synthetic hypotheses—not proven causality.

### 4. Decision Simulator

The central experience of the prototype.

Users can adjust:

- Packaging utilization
- Damage rate
- Expedited shipment share

The interface dynamically estimates the effect on:

- Annual logistics cost
- CO₂ emissions
- Damage cost
- On-time delivery

A recommended scenario explains why specific operational levers were selected while keeping every assumption visible and editable.

### 5. AI Decision Copilot

A deterministic, ChatGPT-style analytics interface supporting questions such as:

- Why did logistics cost increase?
- Which region should we optimize first?
- What is driving the damage rate?
- How could we reduce CO₂?
- Which packaging configurations appear inefficient?

Every response follows an explainable structure:

1. **Observation**
2. **Evidence**
3. **Recommended Action**
4. **Expected Impact**
5. **Confidence**

No external AI service is connected. Responses are generated from predefined synthetic scenarios.

---

## Research Direction

### Potential Master’s Thesis

**Research question:**

> How can data-enabled analytics and AI-assisted decision support help transform industrial supply-chain data from descriptive information into explainable and actionable decisions?

### Potential Evaluation Dimensions

- Decision usefulness
- Recommendation accuracy
- Explainability
- User trust
- Data-quality sensitivity
- Operational relevance

---

## Design Principles

- Scandinavian industrial aesthetic
- Executive-dashboard clarity
- Restrained green and teal palette
- Minimal visual clutter
- Explainability before automation
- Visible assumptions and confidence
- Responsive desktop and mobile layouts

---

## Technology

- Next.js
- TypeScript
- React
- Tailwind CSS
- Recharts
- Cloudflare Workers
- Wrangler

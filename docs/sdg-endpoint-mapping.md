# UN SDG Mapping — TEOS-API-Sovereign Endpoints

This document maps key TEOS-API-Sovereign endpoints to UN Sustainable Development Goals (SDGs).
The mapping supports government RFPs, development programs, and institutional reporting.

## Mapping Legend
- **Primary SDG:** Direct alignment and measurable impact pathway
- **Secondary SDG:** Indirect enabling impact

---

## /governance/action (POST)
**Purpose:** Submit regulated actions for review/approval.

- **Primary:** SDG 16 (Peace, Justice and Strong Institutions)  
  Strengthens institutional decision-making, accountability, and lawful authorization.
- **Secondary:** SDG 17 (Partnerships for the Goals)  
  Enables transparent coordination across institutions and stakeholders.

---

## /governance/decision (POST)
**Purpose:** Human/institutional approval or rejection.

- **Primary:** SDG 16  
  Ensures human authority, due process, and institutional oversight.
- **Secondary:** SDG 9 (Industry, Innovation and Infrastructure)  
  Establishes governance confidence required for resilient DPI adoption.

---

## /compliance/check (POST)
**Purpose:** Regulatory gate evaluation by jurisdiction and use-case.

- **Primary:** SDG 16  
  Supports rule of law through compliance enforcement and auditable controls.
- **Secondary:** SDG 9  
  Enables safer infrastructure by reducing systemic risk in digital services.

---

## /identity/assess (POST)
**Purpose:** Identity risk assessment for civic service access.

- **Primary:** SDG 16  
  Reduces fraud and strengthens identity trust in public institutions.
- **Secondary:** SDG 10 (Reduced Inequalities)  
  Supports equitable access by improving integrity and reducing exclusion risks from fraud.

---

## /identity/revoke (POST)
**Purpose:** Authority-only identity revocation with reason and authorization.

- **Primary:** SDG 16  
  Enables lawful enforcement and protects civic systems from abuse.
- **Secondary:** SDG 9  
  Improves resilience and operational integrity of digital infrastructure.

---

## /services/activate (POST)
**Purpose:** Activate regulated services under approved governance.

- **Primary:** SDG 9  
  Enables deployment of resilient national digital infrastructure under governance.
- **Secondary:** SDG 16  
  Ensures infrastructure remains governed, accountable, and auditable.

---

## /audit/logs (GET)
**Purpose:** Retrieve immutable audit events for oversight and reporting.

- **Primary:** SDG 16  
  Enables transparency, anti-corruption controls, and accountable institutions.
- **Secondary:** SDG 17  
  Supports cross-institution reporting and coordination for shared programs.

---

## Reporting Notes (RFP-Friendly)

### Suggested Indicators
- Number of governance actions submitted/approved/rejected
- Mean time to decision (human oversight)
- Compliance pass/fail rates by jurisdiction profile
- Identity status distribution (trusted/watchlist/revoked)
- Audit export frequency for regulators

### Institutional Statement
TEOS-API-Sovereign is designed to support SDG-aligned digital public infrastructure
by ensuring that innovation in AI and Web3 operates under lawful, human-governed authority.

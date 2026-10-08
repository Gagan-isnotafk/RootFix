# RootFix
The AI-Based Operational Exception Resolution System uses AI agents to investigate operational issues across orders, ERP, warehouse, carrier, and policy data. It identifies root causes, recommends the best solution with evidence, and executes approved actions through APIs, reducing manual effort and improving resolution speed.

# System Architecture
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/35dbbe2a-3bc2-4152-97c1-ba0805d259bb" />

# Workflow
<img width="1842" height="854" alt="image" src="https://github.com/user-attachments/assets/3eedcd28-ee13-4827-82f9-b5d03374dc52" />

### Workflow Stages

1. **Exception Detection** — Identify an operational discrepancy.
2. **Evidence Collection** — Gather relevant records from connected sources.
3. **Reconciliation** — Compare records and reconstruct the incident timeline.
4. **Policy Check** — Retrieve applicable policies and eligibility rules.
5. **Resolution Evaluation** — Compare possible actions using expected value.
6. **Human Approval** — Review evidence and approve, reject or escalate.
7. **Execution** — Execute the approved resolution.
8. **Audit & Closure** — Record the outcome and close the case.

# Roadmap

### Phase 1 — Hackathon Prototype
- [ ] Mock FBA data
- [ ] n8n workflow
- [ ] Evidence collection
- [ ] Root-cause analysis
- [ ] Policy RAG
- [ ] Resolution ranking
- [ ] Human approval
- [ ] Audit logging

### Phase 2 — Real Integrations
- [ ] Amazon SP-API
- [ ] Carrier APIs
- [ ] ERP integration
- [ ] Gmail integration

### Phase 3 — Scale
- [ ] OCR for operational documents
- [ ] Learning from historical outcomes
- [ ] Manufacturing
- [ ] Logistics
- [ ] Insurance
- [ ] Healthcare operations

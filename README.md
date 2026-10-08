# RootFix
The AI-Based Operational Exception Resolution System uses AI agents to investigate operational issues across orders, ERP, warehouse, carrier, and policy data. It identifies root causes, recommends the best solution with evidence, and executes approved actions through APIs, reducing manual effort and improving resolution speed.

# System Architecture
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/35dbbe2a-3bc2-4152-97c1-ba0805d259bb" />

# Workflow

Exception
    ↓
Evidence Collector
    ↓
Reconciliation
    ↓
Policy Agent
    ↓
Resolution Agent
    ↓
Human Approval
    ↓
Execution
    ↓
Audit Log

# AI agents investigation layer

### Evidence Collector
Collects relevant records and documents.

### Reconciliation Agent
Compares records and reconstructs the incident timeline.

### Policy Agent
Retrieves relevant policies, SLAs and claim rules using RAG.

### Resolution Agent
Evaluates possible actions and calculates expected value.

### Execution Agent
Prepares the approved action for execution.


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

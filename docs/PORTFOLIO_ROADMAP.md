# Portfolio Roadmap — 18 Public Projects

This roadmap is designed around current Upwork demand and Jordan Morris's strongest differentiators: finance/FP&A, Snowflake/Power BI architecture, automation, AI systems, and client-facing business systems delivery.

## Portfolio rule

Build many, pin few.

- Maintain 15–20 public projects for highly targeted proposal proof.
- Pin only the strongest 6 on the GitHub profile.
- Every project must prove a distinct business problem or marketable capability.
- Avoid duplicate repos that differ only by industry or minor implementation details.

## Tier 1 — Current Flagship Projects

### 1. ai-finance-intelligence-platform
AI CFO / finance intelligence, governed Q&A, executive briefs, variance analysis.

### 2. enterprise-acv-revenue-intelligence
Snowflake + Power BI recurring-revenue architecture, contract exposure, ACV analytics.

### 3. bookings-revenue-intelligence
Bookings, weighted pipeline, revenue stages, forecasting, variance, renewals.

### 4. finance-close-reconciliation-platform
Deterministic reconciliation, exceptions, controls, duplicate handling, approvals.

### 5. revenue-backlog-automation
Multi-currency backlog, FX translation, project revenue, regional reporting.

### 6. retention-attrition-intelligence
GRR, NRR, logo/revenue attrition, expansion, contraction, health scoring.

## Tier 2 — Highest-Priority Market Expansion

### 7. quickbooks-ai-bookkeeping-agent
**Market gap:** QuickBooks + AI + finance controls.

Build:
- synthetic bank / credit-card transactions
- synthetic receipts and invoices
- vendor matching
- chart-of-accounts recommendation engine
- project/job cost assignment
- confidence scoring
- human review queue
- audit history

Stack: Python, FastAPI, QuickBooks-style API abstraction, OCR mock layer, Claude/OpenAI-compatible tool layer, n8n-style orchestration.

### 8. crm-accounting-sync-platform
**Market gap:** two-way CRM + accounting automation.

Build:
- HubSpot/GoHighLevel-style contacts and deals
- QuickBooks/Xero-style customers, invoices, payments
- field mapping
- duplicate detection
- conflict resolution
- event-driven sync
- failed-event retry queue
- reconciliation dashboard

Stack: Python, APIs, webhooks, Postgres/Supabase, n8n reference workflow.

### 9. rag-enterprise-knowledge-assistant
**Market gap:** production RAG with citations.

Build:
- document upload
- chunking and embeddings
- pgvector / local vector abstraction
- metadata filtering
- grounded answers
- source citations
- conversation history
- evaluation set
- hallucination / no-answer controls

Stack: Python, FastAPI, LangChain/LangGraph-compatible patterns, pgvector, OpenAI/Claude abstraction.

### 10. ai-voice-receptionist
**Market gap:** Vapi / Retell / Twilio voice-agent implementations.

Build:
- synthetic inbound call scenarios
- intent classification
- lead qualification
- appointment booking
- escalation / transfer logic
- call summary
- CRM writeback
- transcript analytics
- failure / latency telemetry mock

Stack: Vapi/Retell-style interfaces, Twilio-style telephony abstraction, Python, APIs, webhooks.

### 11. revops-ai-automation-platform
**Market gap:** HubSpot / Salesforce / n8n / AI sales operations.

Build:
- lead enrichment
- lead scoring
- routing
- lifecycle-stage automation
- AI follow-up drafting
- SLA alerts
- opportunity hygiene
- pipeline analytics
- executive RevOps dashboard

Stack: HubSpot/Salesforce-style data, n8n, Python, APIs, Power BI/Streamlit.

### 12. snowflake-dbt-analytics-engineering
**Market gap:** Snowflake + dbt + SQL + Python + data quality.

Build:
- raw → staging → marts architecture
- dimensional model
- dbt models
- tests
- incremental loads
- data-quality checks
- finance marts
- orchestration example

Stack: Snowflake-compatible SQL, dbt, Python, GitHub Actions, analytics engineering documentation.

## Tier 3 — Finance + BI Depth

### 13. fpa-planning-variance-dashboard
Power BI / Streamlit FP&A model with budget, forecast, actuals, drivers, scenario analysis, variance waterfall, and executive narrative.

### 14. cash-flow-liquidity-forecast
13-week cash forecast, receivables/payables timing, scenario toggles, liquidity alerts, covenant-style thresholds, management dashboard.

### 15. sales-commission-accrual-engine
Quota / bookings / revenue inputs → commission calculations → accrual vs payout → true-up / under-accrual detection → management bridge.

### 16. project-margin-job-costing-intelligence
Labor + non-labor + billing + project revenue → project margin, utilization, ETC/EAC, WIP, over/under performance, exception alerts.

## Tier 4 — Operations & Document Automation

### 17. intelligent-document-processing
Invoice / statement / contract ingestion → classification → structured extraction → validation → confidence → human review → downstream API payload.

Stack: OCR abstraction, Python, LLM structured extraction, validation rules, approval queue.

### 18. business-operating-system-command-center
Cross-functional reference architecture modeled after modern client operating-system requests.

Build:
- Postgres/Supabase canonical database
- CRM / finance / project entities
- internal dashboard
- approval queues
- document register
- n8n-style orchestration
- AI classification / drafting
- audit logs
- permissions model

This repo should demonstrate architecture and delivery leadership more than any single tool.

## Suggested GitHub Pins

Keep the pinned six outcome-oriented and balanced:

1. ai-finance-intelligence-platform
2. enterprise-acv-revenue-intelligence
3. finance-close-reconciliation-platform
4. quickbooks-ai-bookkeeping-agent
5. rag-enterprise-knowledge-assistant
6. revops-ai-automation-platform OR ai-voice-receptionist

Rotate the sixth pin depending on the Upwork lane producing the most interviews.

## Creation Order

### Wave 1 — immediate
7. quickbooks-ai-bookkeeping-agent
8. crm-accounting-sync-platform
9. rag-enterprise-knowledge-assistant
10. revops-ai-automation-platform

### Wave 2 — market expansion
11. ai-voice-receptionist
12. snowflake-dbt-analytics-engineering
13. fpa-planning-variance-dashboard

### Wave 3 — finance authority
14. cash-flow-liquidity-forecast
15. sales-commission-accrual-engine
16. project-margin-job-costing-intelligence

### Wave 4 — enterprise systems
17. intelligent-document-processing
18. business-operating-system-command-center

## Definition of Done for Every Repo

A project is not portfolio-ready until it has:

- README.md written for a buyer, not only a developer
- docs/case-study.md
- docs/architecture.md
- docs/business-rules.md
- docs/data-dictionary.md
- docs/security.md
- docs/runbook.md
- deterministic synthetic data
- executable business logic
- interactive public demo where appropriate
- automated tests
- architecture diagram
- 4–6 screenshots
- 60–120 second walkthrough script
- Upwork portfolio copy
- explicit statement that data is synthetic / public-safe

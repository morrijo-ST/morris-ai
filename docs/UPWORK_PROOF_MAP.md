# Upwork Job → Proof Map

Use this file when deciding which portfolio link to include in a proposal. Never send every project. Send the one project that most closely mirrors the client's business problem.

| Upwork job language | Primary proof repo | Secondary proof |
|---|---|---|
| AI CFO / finance automation / Claude + finance | ai-finance-intelligence-platform | fpa-planning-variance-dashboard |
| QuickBooks automation / AI bookkeeping / receipt matching | quickbooks-ai-bookkeeping-agent | finance-close-reconciliation-platform |
| CRM + accounting sync | crm-accounting-sync-platform | finance-close-reconciliation-platform |
| Power BI FP&A dashboard | enterprise-acv-revenue-intelligence | fpa-planning-variance-dashboard |
| Revenue / bookings forecast | bookings-revenue-intelligence | enterprise-acv-revenue-intelligence |
| Retention / churn / NRR / GRR | retention-attrition-intelligence | enterprise-acv-revenue-intelligence |
| Close automation / reconciliation | finance-close-reconciliation-platform | quickbooks-ai-bookkeeping-agent |
| Services / project backlog | revenue-backlog-automation | project-margin-job-costing-intelligence |
| RAG / vector DB / knowledge assistant | rag-enterprise-knowledge-assistant | ai-finance-intelligence-platform |
| n8n AI agent / workflow automation | revops-ai-automation-platform | crm-accounting-sync-platform |
| HubSpot / Salesforce automation | revops-ai-automation-platform | crm-accounting-sync-platform |
| AI voice receptionist / Vapi / Retell / Twilio | ai-voice-receptionist | revops-ai-automation-platform |
| Snowflake / dbt / analytics engineer | snowflake-dbt-analytics-engineering | enterprise-acv-revenue-intelligence |
| Cash flow / liquidity forecast | cash-flow-liquidity-forecast | ai-finance-intelligence-platform |
| Commission automation / sales comp | sales-commission-accrual-engine | bookings-revenue-intelligence |
| Job costing / construction FP&A / project margins | project-margin-job-costing-intelligence | revenue-backlog-automation |
| OCR / invoice / statement processing | intelligent-document-processing | quickbooks-ai-bookkeeping-agent |
| Business operating system / command center | business-operating-system-command-center | revops-ai-automation-platform |

## Proposal proof rule

A proposal should normally contain:

1. One sentence proving business-domain fit.
2. One relevant portfolio link.
3. One sentence explaining exactly which part of the demo maps to the client's request.
4. A brief implementation plan.
5. One high-quality discovery question.

Do not dump a GitHub profile URL with no context. Make the proof link feel selected specifically for the client.

## Example

Client asks for QuickBooks + email + receipt matching + AI categorization.

Use:

`quickbooks-ai-bookkeeping-agent`

Proposal language:

> I built a public-safe reference implementation of this exact pattern: transactions + receipt/invoice matching + deterministic accounting rules + AI-assisted categorization + confidence scoring + human exception review. For your environment I'd replace the synthetic QBO adapter with your live QBO API connection and map your chart of accounts / cost codes before enabling any high-confidence automation.

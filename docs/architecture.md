System Architecture
Objective

Design a modular LeadOps automation system capable of:

Capturing incoming leads

Enriching and qualifying leads

Prioritizing business emails

Triggering real-time notifications

Logging structured data

Architecture Flow

Webhook → Data Enrichment (JavaScript Node) → Conditional Logic →
Gmail Notification → Google Sheets Logging → Webhook Response

Design Decisions

Modular workflows instead of monolithic automation

Conditional branching for business email prioritization

Structured JSON output for downstream processing

Google Sheets as lightweight CRM layer

Scalability

Each workflow can:

Run independently

Be extended with external APIs

Integrate with CRM systems

Support AI scoring models

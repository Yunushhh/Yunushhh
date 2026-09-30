# Hi, I'm Yunus 👋

### Workflow Automation & AI

I design stateful automation systems in n8n and Make.com — workflows that connect CRMs, databases, inboxes and AI services, and that stay correct when a step fails. I run n8n self-hosted on Docker, keep AI to the parts that genuinely need language understanding, and document every design decision.

## Projects

**[RevOps Deal Risk Assessment & Alert System](https://github.com/Yunushhh/n8n-revops-deal-risk-alert-system)**
n8n (self-hosted) · PostgreSQL · HubSpot · Slack · OpenRouter

Scores every open HubSpot deal daily against explicit business rules and alerts Slack only when a deal's risk materially changes. PostgreSQL stores what was last alerted, so notifications fire on change rather than every morning.

**[AI Lead Triage & Support Router](https://github.com/Yunushhh/make-ai-lead-triage-support-router)**
Make.com · Make Data Store · OpenRouter · Gmail · Google Sheets

Classifies inbound email with one LLM call and routes it to sales, support, review or a log. A single state field makes every run resumable, and a message caught mid-send is held for a person to check rather than sent twice.

Both are documented end to end — architecture, setup, test cases and known gaps — and can be reproduced from the repository.

## What I focus on

- **State and recovery** — persistent state, deduplication, and runs that resume without repeating work
- **Failure handling** — explicit error paths, grouped alerts, and no duplicate sends
- **Scoped AI** — one LLM call where language needs understanding, deterministic rules for every decision
- **Human in the loop** — AI-written replies are drafts, and uncertainty goes to a person

## Stack

`n8n` `Make.com` `PostgreSQL` `Docker` `HubSpot` `Slack` `Gmail` `Google Sheets` `OpenRouter` `REST APIs` `Webhooks`

## Contact

Open to remote roles — full-time, part-time and contract.
[LinkedIn](https://www.linkedin.com/in/mohmmadyunus)

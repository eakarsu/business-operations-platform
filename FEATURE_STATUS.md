# Feature status — Business operations & organizational knowledge

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 159 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 1 | 0 | Native records/view |
| Calendar | records | 2 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 2 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 5 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 0 | 0 | Provider request records only |
| Sources | records | 2 | 0 | Native records/view |
| Insights | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Anomalies | records | 1 | 0 | Native records/view |
| Queries | records | 2 | 0 | Native records/view |
| Connectors | integration | 2 | 0 | Provider request records only |
| Agent dispatcher | records | 1 | 0 | Native records/view |
| Decision replay | records | 1 | 0 | Native records/view |
| Kpis | records | 1 | 0 | Native records/view |
| Workflows | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Chief of staff | records | 1 | 0 | Native records/view |
| Tickets | records | 2 | 0 | Native records/view |
| Intent graph | records | 1 | 0 | Native records/view |
| Export | records | 1 | 0 | Native records/view |
| Rbac | records | 1 | 0 | Native records/view |
| Alerting | records | 1 | 0 | Native records/view |
| Pii redaction | records | 1 | 0 | Native records/view |
| Transcripts | records | 1 | 0 | Native records/view |
| Webhook ingest | integration | 2 | 0 | Provider request records only |
| Connector scripts | integration | 1 | 0 | Provider request records only |
| Query suggest | records | 1 | 0 | Native records/view |
| Source onboarding | records | 1 | 0 | Native records/view |
| Self improving queries | records | 1 | 0 | Native records/view |
| Policy drift | records | 1 | 0 | Native records/view |
| Commitments | records | 1 | 0 | Native records/view |
| Meetings | records | 3 | 0 | Native records/view |
| Executive | records | 2 | 0 | Native records/view |
| Commitment | records | 1 | 0 | Native records/view |
| Follow-Up | records | 1 | 0 | Native records/view |
| Meeting Note | records | 1 | 0 | Native records/view |
| Weekly Report | records | 1 | 0 | Native records/view |
| Decision Brief | records | 1 | 0 | Native records/view |
| Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source Feed | records | 1 | 0 | Native records/view |
| Action Item | records | 1 | 0 | Native records/view |
| Escalation | records | 1 | 0 | Native records/view |
| Stakeholder | records | 1 | 0 | Native records/view |
| Calendar Window | records | 1 | 0 | Native records/view |
| Draft: Commitment Scanner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Meeting Note Structurer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Decision Brief Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Flow | records | 1 | 0 | Native records/view |
| Friction | records | 1 | 0 | Native records/view |
| AI Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Team | records | 1 | 0 | Native records/view |
| Delivery Cycle | records | 1 | 0 | Native records/view |
| Work Item | records | 1 | 0 | Native records/view |
| Rework Event | records | 1 | 0 | Native records/view |
| Approval Delay | records | 1 | 0 | Native records/view |
| Coordination Cost | records | 1 | 0 | Native records/view |
| Quality Signal | records | 1 | 0 | Native records/view |
| AI Usage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Productivity Baseline | records | 1 | 0 | Native records/view |
| Experiment | records | 1 | 0 | Native records/view |
| Benchmark | records | 1 | 0 | Native records/view |
| Executive Report | records | 1 | 0 | Native records/view |
| Draft: Velocity Briefing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Friction Root-Cause | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Gains vs Activity Separator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendors | records | 3 | 0 | Native records/view |
| Bids | records | 1 | 0 | Native records/view |
| Contracts | records | 3 | 0 | Native records/view |
| RFPs | records | 1 | 0 | Native records/view |
| Products | records | 1 | 0 | Native records/view |
| Spend Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Savings | records | 1 | 0 | Native records/view |
| Compliance | records | 3 | 0 | Native records/view |
| Approvals | records | 3 | 0 | Native records/view |
| Emails | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Onboarding | records | 1 | 0 | Native records/view |
| Expenses | records | 2 | 0 | Native records/view |
| Data Entry | records | 2 | 0 | Native records/view |
| Process Miner | records | 2 | 0 | Native records/view |
| Workflow Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| RPA Scripts | records | 2 | 0 | Native records/view |
| Exception Handler | records | 2 | 0 | Native records/view |
| ROI Calculator | records | 2 | 0 | Native records/view |
| Automation Tasks | records | 1 | 0 | Native records/view |
| Support Tickets | records | 1 | 0 | Native records/view |
| HR Onboarding | records | 1 | 0 | Native records/view |
| AI Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Document | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Contract | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Categorize Email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest Workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Expense | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Meeting Agenda | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prioritize Ticket | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evaluate Vendor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest Onboarding Tasks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Extract Data | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Suggest Approval Chain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workflow triggers | records | 1 | 0 | Native records/view |
| Bottleneck heatmap | records | 1 | 0 | Native records/view |
| Anomaly check | records | 1 | 0 | Native records/view |
| Workflow builder | records | 1 | 0 | Native records/view |
| Compliance watchdog | records | 1 | 0 | Native records/view |
| Process analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stream | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly detection | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Toolbox | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Backlog tools | records | 1 | 0 | Native records/view |
| Exception cost attribution | records | 1 | 0 | Native records/view |
| Ameritai work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Knowledge | records | 1 | 0 | Native records/view |
| Procedures | records | 1 | 0 | Native records/view |
| Policies | records | 1 | 0 | Native records/view |
| Decisions | records | 1 | 0 | Native records/view |
| Source connectors | integration | 1 | 0 | Provider request records only |
| Ingestion | records | 1 | 0 | Native records/view |
| Hybrid search | records | 1 | 0 | Native records/view |
| Embedding models | records | 1 | 0 | Native records/view |
| Knowledge graph | records | 1 | 0 | Native records/view |
| Retrieval eval | records | 1 | 0 | Native records/view |
| Tenants acl | records | 1 | 0 | Native records/view |
| Skill file generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Knowledge refresh agent | records | 1 | 0 | Native records/view |
| Query route to source | records | 1 | 0 | Native records/view |
| Contradiction detector | records | 1 | 0 | Native records/view |
| Onboarding curriculum | records | 1 | 0 | Native records/view |
| Embeddings store | records | 1 | 0 | Native records/view |
| Versioning | records | 1 | 0 | Native records/view |
| Dept access control | records | 1 | 0 | Native records/view |
| Scim sso | records | 1 | 0 | Native records/view |
| Skills json | records | 1 | 0 | Native records/view |
| Staleness pr | records | 1 | 0 | Native records/view |
| Multi llm voting | records | 1 | 0 | Native records/view |
| Dept graphs | records | 1 | 0 | Native records/view |
| Meeting transcripts | records | 1 | 0 | Native records/view |
| Requests | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| Studio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approval exposure | records | 1 | 0 | Native records/view |
| Sap controls | records | 1 | 0 | Native records/view |
| Sap process hub | records | 1 | 0 | Native records/view |
| Sap configuration | records | 1 | 0 | Native records/view |
| Sap workflow | records | 1 | 0 | Native records/view |
| Sap authorization | records | 1 | 0 | Native records/view |
| Sap finance ledger | records | 1 | 0 | Native records/view |
| Sap production planning | records | 1 | 0 | Native records/view |
| Sap sales distribution | records | 1 | 0 | Native records/view |
| Sap inventory warehouse | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 159 feature pages were visited in the browser; 157 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 37 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

37 original AI entries are now grouped into **4 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

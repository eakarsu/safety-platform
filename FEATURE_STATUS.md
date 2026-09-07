# Feature status — Emergency response & safety

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 167 pages |
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
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Permit Closeout Readiness | records | 1 | 0 | Native records/view |
| Site Inspections | records | 1 | 0 | Native records/view |
| Violations | records | 1 | 0 | Native records/view |
| Safety Checklists | records | 1 | 0 | Native records/view |
| Incident Reports | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Inspections | records | 2 | 0 | Native records/view |
| Worker Certifications | records | 1 | 0 | Native records/view |
| Safety Training | records | 2 | 0 | Native records/view |
| Hazard Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency Plans | records | 1 | 0 | Native records/view |
| PPE Inventory | records | 2 | 0 | Native records/view |
| Corrective Actions | records | 1 | 0 | Native records/view |
| Crisis Incidents | records | 1 | 0 | Native records/view |
| Media Monitoring | records | 1 | 0 | Native records/view |
| Stakeholders | records | 1 | 0 | Native records/view |
| Response Templates | records | 1 | 0 | Native records/view |
| Crisis Simulations | records | 1 | 0 | Native records/view |
| Communication Log | records | 1 | 0 | Native records/view |
| Team Management | records | 1 | 0 | Native records/view |
| Incident Timeline | records | 1 | 0 | Native records/view |
| Press Releases | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Media | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Talking Points | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post-Crisis Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: PredictiveCrisisDetectio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CF: AgenticResponsePlanning | records | 1 | 0 | Native records/view |
| CF: SentimentDrivenEscalatio | records | 1 | 0 | Native records/view |
| CF: ScenarioStressTesting | records | 1 | 0 | Native records/view |
| CF: PostCrisisLearningAutoma | records | 1 | 0 | Native records/view |
| Gap: AllMajorFunctionsLackAiE | records | 1 | 0 | Native records/view |
| Gap: NoRealTimeAlertSystemFor | records | 1 | 0 | Native records/view |
| Gap: LimitedIntegrationWithMe | integration | 1 | 0 | Provider request records only |
| Gap: NoWebhooks | integration | 2 | 0 | Provider request records only |
| Gap: LimitedPushNotificationD | records | 1 | 0 | Native records/view |
| Gap: NoApprovalWorkflowForCri | records | 1 | 0 | Native records/view |
| Gap: NoPaymentBillingModule | records | 1 | 0 | Native records/view |
| Crisis Severity Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Message Consistency Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Template Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Impact Forecaster | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Automated Media Alert | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Notification Cascade | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Mention Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft Press Release | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Escalation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Auto Talking Points | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tactical Playbook | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resources | records | 2 | 0 | Native records/view |
| Shelters | records | 2 | 0 | Native records/view |
| Volunteers | records | 2 | 0 | Native records/view |
| Supplies | records | 2 | 0 | Native records/view |
| Evacuations | records | 2 | 0 | Native records/view |
| Damage Assessments | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Weather Alerts | records | 2 | 0 | Native records/view |
| Donations | records | 2 | 0 | Native records/view |
| Medical Resources | records | 2 | 0 | Native records/view |
| Search & Rescue | records | 1 | 0 | Native records/view |
| Infrastructure | records | 2 | 0 | Native records/view |
| Threat Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Live Map | records | 1 | 0 | Native records/view |
| Commander Briefing | records | 1 | 0 | Native records/view |
| External Data | records | 1 | 0 | Native records/view |
| Mutual Aid Board | records | 1 | 0 | Native records/view |
| AAR Workflow | records | 1 | 0 | Native records/view |
| AI New Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seismic Feed Ingest | records | 1 | 0 | Native records/view |
| P-Wave Detection | records | 1 | 0 | Native records/view |
| Tsunami Propagation | records | 1 | 0 | Native records/view |
| Population Alert Router | records | 1 | 0 | Native records/view |
| EEW Siren Network | records | 1 | 0 | Native records/view |
| ShakeAlert Gateway | records | 1 | 0 | Native records/view |
| Supply Distribution Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Donation-to-Need Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Shelter Assignment Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vulnerability Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Recovery Trajectory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real time impact forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resource constrained optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply chain prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery trajectory modeling | records | 1 | 0 | Native records/view |
| Supplyroutes lacks optimize supply distribution | records | 1 | 0 | Native records/view |
| Donationroutes lacks match donation to need | records | 1 | 0 | Native records/view |
| Shelterroutes lacks optimize shelter assignments | records | 1 | 0 | Native records/view |
| Volunteerroutes lacks ai volunteer matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No real time crisis command center dashboard surface beyond | records | 1 | 0 | Native records/view |
| Limited mobile app for first responders | records | 1 | 0 | Native records/view |
| Limited integration with emergency services 911 fema red cro | integration | 1 | 0 | Provider request records only |
| No social media monitoring for crisis information | records | 1 | 0 | Native records/view |
| No payment billing module for donations beyond crud | records | 1 | 0 | Native records/view |
| No calendar integration | integration | 1 | 0 | Provider request records only |
| PPE Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety Audits | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Reports | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazard Zones | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OSHA & Near-Miss | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic & Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Employees | records | 2 | 0 | Native records/view |
| Shift Schedules | records | 1 | 0 | Native records/view |
| Emergency Contacts | records | 1 | 0 | Native records/view |
| Safety Alerts | records | 1 | 0 | Native records/view |
| Lockout Tagout | records | 1 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| behavioral intelligence platform | records | 1 | 0 | Native records/view |
| threat severity scoring | records | 1 | 0 | Native records/view |
| mental health early identification | records | 1 | 0 | Native records/view |
| emergency playbook automation | records | 1 | 0 | Native records/view |
| community risk monitoring | records | 1 | 0 | Native records/view |
| staff training personalization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| threatriskscore severity ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| behavioralpatterndetection | records | 1 | 0 | Native records/view |
| bullyingdetection from textcommunication | records | 1 | 0 | Native records/view |
| emergencyreadinessassessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| firstresponderbrief autogeneration | records | 1 | 0 | Native records/view |
| mentalhealthreferral ai triage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited anonymous reporting tips route exist | records | 1 | 0 | Native records/view |
| sospanic alert system integration | integration | 1 | 0 | Provider request records only |
| massnotification smsvoice emergency comms | records | 1 | 0 | Native records/view |
| firstresponder integration cad push | integration | 1 | 0 | Provider request records only |
| sis student information system integratio | records | 1 | 0 | Native records/view |
| limited training compliance tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fire Detections | records | 1 | 0 | Native records/view |
| Evacuation Plans | records | 1 | 0 | Native records/view |
| Resource Allocations | records | 1 | 0 | Native records/view |
| Weather Analyses | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smoke Reports | records | 1 | 0 | Native records/view |
| Community Alerts | records | 1 | 0 | Native records/view |
| Spread Predictions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Water Sources | records | 1 | 0 | Native records/view |
| Crew Deployments | records | 1 | 0 | Native records/view |
| Equipment Tracking | records | 1 | 0 | Native records/view |
| Quick Risk Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Situation Report Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fire Behavior Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prevention Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Training Scenario Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fire Spread Predictor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Evacuation Route Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resource Allocation Planner | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Post-Fire Damage Assessor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Weather Risk Monitor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Resource Deployment Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Community Alert Prioritization | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Multi model prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evacuation traffic | records | 1 | 0 | Native records/view |
| Resource prepositioning | records | 1 | 0 | Native records/view |
| Drone damage assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Psps coordination | records | 1 | 0 | Native records/view |
| Recovery planning | records | 1 | 0 | Native records/view |
| R quality alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 167 feature pages were visited in the browser; 165 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 65 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

65 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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

# ai-work-samples
AI-powered AR and collections tools — work samples for Near application
AI Work Samples — Joel Solís
Application for: AI-Powered Operator · Near / US Staffing Client


"I use AI every day to get real work done — not as a novelty, but as infrastructure."

This repository contains three fully functional work samples built to demonstrate hands-on AI execution across finance, operations, and business automation. Each project combines domain expertise (18+ years in AR, collections, and financial systems) with practical AI tooling.

📦 What's Inside
#ProjectTypeAI Used01AR Aging Intelligence DashboardExcel (.xlsx)AI-assisted logic & recommendations02AI Business Document EvaluatorInteractive HTMLClaude API (live)03Collections Automation FlowInteractive HTMLClaude API (live)

01 · AR Aging Intelligence Dashboard
File: 01-ar-aging-dashboard/Joel_Solis_AR_Aging_Dashboard.xlsx
A professional multi-sheet Excel dashboard that replicates the kind of AR intelligence tool a senior collections specialist would build to manage a real portfolio.
What it includes:

📋 AR Data — 25 realistic customer accounts with aging buckets, dispute flags, risk scores, and contact history. Color-coded by severity.
📊 Aging Summary — Dynamic SUMIF/COUNTIF formulas across 5 aging buckets, 8 live KPI cards (Total AR, DSO, dispute rate, at-risk %), and breakdowns by region and account manager.
🎯 Collections Priority — AI-generated action recommendations for each account, ranked by urgency with specific deadlines and escalation logic.
💰 Cash Forecast — 30-day recovery model with adjustable recovery rate assumptions per aging bucket. Shows expected recovery, at-risk amount, and dispute exposure.
📝 Executive Summary — Auto-generated weekly summary that pulls all figures dynamically. Designed to replace a manual 3-hour reporting process.

Skills demonstrated: Advanced Excel, financial modeling, AR operations, AI-assisted workflow design, executive communication.

02 · AI Business Document Evaluator
File: 02-ai-document-evaluator/Joel_Solis_AI_Document_Evaluator.html
A live web application that uses Claude to evaluate AI-generated business documents (Excel reports, PowerPoint decks, Word memos, emails) across 6 professional dimensions.
Evaluation rubric:
DimensionWeightAccuracy & Data Integrity25%Clarity & Communication20%Tone & Professionalism20%Format & Structure15%Logical Consistency15%Hallucination Risk5%
Output includes:

Overall score (0–100) with verdict
Per-dimension scores with progress bars and specific comments
Color-coded findings (Issues / Warnings / Passes)
Prioritized action plan (High / Medium / Low)
Prompt transparency tab — shows the exact engineered prompt sent to the API

Skills demonstrated: Prompt engineering, AI output evaluation, business document standards, UI design, API integration.
▶ How to run (live AI version)

Open Claude.ai
Start a new chat
Upload Joel_Solis_AI_Document_Evaluator.html
Ask Claude: "Please render this as an artifact"
Click "Load sample document" → "Evaluate Document Quality"


The Claude.ai environment automatically handles API authentication. No API key needed.

▶ How to run (offline / browser)
Open the HTML file directly in any browser. If the API is unavailable, the tool uses realistic pre-generated evaluations so the full workflow is always demonstrable.

03 · Collections Automation Flow
File: 03-collections-automation-flow/Joel_Solis_Collections_Automation_Flow.html
An end-to-end interactive demo of an AI-assisted AR collections workflow. Shows exactly how AI and human judgment work together to process a queue of overdue accounts efficiently.
The 5-step workflow:

Select Account — Queue of 8 real accounts from the AR Dashboard, ranked by risk
AI Classification — Claude analyzes the account profile and recommends a strategy: Standard Reminder / Urgent Follow-Up / Dispute Resolution / Legal Escalation / Payment Plan Offer / Executive Escalation
Draft Email — Claude writes a complete, tone-appropriate collections email with live streaming effect
Human Review — Collector approves, regenerates, or reclassifies. AI proposes, human decides.
Log & Next Action — Action logged, follow-up scheduled, queue updated

Skills demonstrated: AR collections expertise, workflow automation design, prompt engineering, AI-human collaboration patterns, real-time API integration.
▶ How to run (live AI version)

Open Claude.ai
Start a new chat
Upload Joel_Solis_Collections_Automation_Flow.html
Ask Claude: "Please render this as an artifact"
Select any account from the left panel to start the workflow

▶ How to run (offline / browser)
Open directly in any browser. Offline mode uses pre-generated classifications and email templates so the complete 5-step workflow runs without API access.

About Me
Joel Solís · Panama City, Panama · Remote-ready
18+ years of end-to-end execution across AR, financial systems, and operations at multinational companies including NextRoll, Quest Software, Philips (Respironics), and Grainger.
AI stack I use daily:

Claude, ChatGPT, Gemini — analysis, writing, automation
Ollama + Chat RTX (NVIDIA) — local LLM deployment and model evaluation
ComfyUI — generative AI pipelines
AntiGravity DevTools — prompt engineering and workflow testing

Certifications: Google Certified AI Professional · English C2 (Stanford Language Center)
Systems: NetSuite · SAP · Oracle R12 · Salesforce (SFDC) · MS Access · Zendesk · Excel Advanced
📧 jrazielsolis@outlook.com
🔗 LinkedIn: https://www.linkedin.com/in/joel-solis-ag/

Tech Stack Used in These Projects
AI:          Claude API (claude-sonnet-4-20250514)
Frontend:    HTML · CSS · Vanilla JavaScript
Data:        Python (openpyxl) · Microsoft Excel
Fonts:       DM Serif Display · Syne · JetBrains Mono · Outfit
Hosting:     GitHub · Claude.ai Artifacts

Built independently as work samples for the Near / AI Operator application. All data is fictional and generated for demonstration purposes.

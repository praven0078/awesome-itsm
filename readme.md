Awesome ITSM ![Awesome](https://awesome.re/badge.svg)
> A curated list of outstanding resources for IT Service Management professionals — frameworks, tools, certifications, communities, AI tooling, metrics, and templates.
IT Service Management (ITSM) is the discipline of designing, delivering, managing, and improving the way IT is used within an organisation. This list is maintained by a practitioner with 27 years of ITSM experience across India, New Zealand, and Australia.
---
Contents
Frameworks and Standards
ServiceNow
Certifications
AI Tools for ITSM
AI Agents for ITSM
Metrics and KPIs
Communities
Blogs and Newsletters
Podcasts
Books
Tools and Platforms
Templates and Checklists
YouTube Channels
---
Frameworks and Standards
ITIL 4 - The most widely adopted ITSM framework globally. Covers the service value system, four dimensions model, and 34 management practices.
COBIT 2019 - Governance and management framework for enterprise IT, published by ISACA.
ISO/IEC 20000 - International standard for IT service management. The formal certification path for ITSM at the organisational level.
VeriSM - Modern service management model designed for the digital age, wrapping existing frameworks under a governance umbrella.
SIAM - Service Integration and Management — the framework for managing multiple service providers in a complex IT supply chain.
ServiceNow
ServiceNow Documentation - Official product documentation covering all modules, releases, and APIs.
ServiceNow Developer Portal - Free Personal Developer Instance (PDI), API references, guides, and best practices.
Now Learning - ServiceNow's official learning platform with on-demand courses, certifications, and hands-on labs.
SNDevs Slack - Independent ServiceNow community with 13,000+ admins, developers, and architects.
ServiceNow Community - Official forum for Q&A, product ideas, user groups, and knowledge base articles.
ServiceNow Australia Release Notes - GA May 2026. Key changes include auto-inclusion of sn_cmdb_admin with itil_admin, Service Graph Workspace replacing CMDB Workspace, and Platform Analytics replacing Performance Analytics.
awesome-servicenow by stevezero - Curated list of ServiceNow resources focused on the developer experience.
Certifications
ITIL 4 Foundation - Entry-level certification covering core ITSM concepts. Industry baseline for practitioners.
ITIL 4 Managing Professional (MP) - Advanced track covering practical and technical skills for running IT-enabled services.
ITIL 4 Strategic Leader (SL) - For professionals who influence business strategy using IT.
COBIT 5 Foundation - Governance framework certification by ISACA.
ServiceNow CSA - Certified System Administrator. Core ServiceNow platform certification.
ServiceNow CIS-ITSM - Certified Implementation Specialist for ITSM. Validates ability to implement ITSM on the Now Platform.
HDI Certifications - Support centre-focused certifications including HDI-SCA, HDI-SCM, and HDI-DST.
SDI Certifications - Service Desk Institute certifications for service desk professionals.
AI Tools for ITSM
Claude - AI assistant well-suited to ITSM documentation, root cause analysis drafts, process design, and knowledge article generation.
ServiceNow Now Assist - Generative AI capabilities embedded natively in ServiceNow across ITSM, ITOM, and CSM.
Atlassian Intelligence - AI features across Jira Service Management for summarisation, auto-classification, and virtual agents.
Make.com - No-code automation platform for connecting ITSM tools, ticketing systems, and notification workflows. (Affiliate)
Notion AI - AI-powered workspace useful for ITSM knowledge bases, runbooks, and SOP management. (Affiliate)
ElevenLabs - AI voice synthesis — useful for creating ITSM training content and process walkthrough videos. (Affiliate)
CodePlain - PowerShell-based tool that explains scripts and automation code in plain English. Useful for ITSM admins managing ServiceNow scripting without a development background.
AI Agents for ITSM
Agentic AI is the fastest-moving category in ITSM right now. Unlike generative AI tools that assist humans, AI agents act autonomously — perceiving tickets, logs, and CMDB data, then planning and executing multi-step resolutions with minimal human input. This section covers platforms, frameworks, reading, and research for ITSM professionals navigating this shift.
Platforms and Tools
ServiceNow AI Agents - Native agentic AI capabilities across the Now Platform. Covers autonomous incident triage, CMDB updates during remediation, and cross-workflow orchestration.
Atomicwork - AI-native ITSM platform built around agentic service management. Automatically detects and clusters incidents from Slack, Teams, and email without manual ticket creation.
Freshservice Freddy AI - Natively embedded AI agent across Freshservice. Handles end-to-end request fulfilment, incident detection, and proactive problem identification.
incident.io AI SRE - Slack-native AI agent that autonomously investigates incidents, surfaces root causes, and drafts post-mortems from captured timeline data.
PagerDuty AIOps - AI-driven alert noise reduction, incident correlation, and automated runbook execution for on-call teams.
Automation Anywhere ITSM Agents - Agentic AI combined with RPA for closed-loop incident resolution — detects, diagnoses, and remediates L1/L2 tickets end-to-end.
Aisera - AI co-pilot and agent platform for ITSM with natural language self-service across Microsoft Teams and other channels. Covers IT, HR, and Facilities.
Atlassian Rovo - AI agent layer across Jira Service Management. Surfaces root causes during incidents, suggests runbooks, and automates knowledge article creation from resolved tickets.
BigPanda - AIOps platform focused on alert correlation and incident prioritisation. Reduces alert noise before it reaches the service desk.
n8n - Open-source low-code workflow automation platform. Suitable for building custom AI-powered ITSM automations without vendor lock-in.
Reading and Research
Agentic AI in ITSM — ITSM.tools - Practitioner-written overview of how agentic AI changes major incident detection, clustering, and stakeholder communication.
AI Survey 2026: Agentic AI Adoption in ITSM — ITSM.tools - Industry survey on where the ITSM community sits with agentic AI adoption. Covers low, mid, and high agency definitions.
Agentic AI in ITSM: 10 Workflows to Automate — SMC Consulting - Practical guide to identifying which service desk workflows are safe to hand to AI agents and which still need human judgement.
ITSM AI Trends 2026 — DI.net - Australian perspective on AI adoption in service management. Covers virtual agents, agentic AI, and ROI benchmarks relevant to ANZ organisations.
Gartner AI Applications in ITSM - Gartner Peer Insights reviews for AI ITSM tools. Useful for vendor comparison and real-world practitioner assessments.
Key Concepts
Agentic AI vs Generative AI — Generative AI drafts a response for a human to action. Agentic AI acts autonomously end-to-end. The distinction matters when evaluating vendor claims.
Agency levels — Low agency: single-step assistance. Mid agency: multi-step reasoning and adaptive execution. High agency: goal-driven autonomy with planning and reprioritisation.
Human in the loop — Best practice for 2026 is agentic AI handling high-volume low-risk tasks (password resets, triage, categorisation) with human oversight retained for ambiguous, high-impact, or sensitive situations.
AIOps — AI for IT Operations. Focuses on event correlation, anomaly detection, and predictive analytics to prevent incidents before they impact users. Distinct from ITSM but closely integrated.
Metrics and KPIs
ITIL KPI Library — Axelos - Official Axelos guidance on measuring ITSM practices across the service value chain.
HDI Support Center Metrics - Industry benchmarks for service desk performance including FCR, AHT, CSAT, and abandonment rate.
Freshservice Benchmark Report - Annual industry benchmark data for ITSM metrics across company sizes and verticals.
Communities
ITSMF International - IT Service Management Forum — the global professional association for ITSM practitioners.
ITSMF Australia and New Zealand - ANZ chapter with local events, SIGs, and networking for ITSM professionals.
HDI Community - Global community focused on technical support and service management.
r/sysadmin - Large Reddit community with frequent ITSM, service desk, and process discussions.
ServiceNow SNDevs Slack - 13,000+ registered members. The most active independent ServiceNow practitioner community.
Blogs and Newsletters
AXELOS Blog - Official ITIL and PRINCE2 publisher blog covering framework updates, case studies, and best practices.
HDI SupportWorld - Articles, research, and guides for support centre and ITSM professionals.
ServiceNow Blog - Product news, customer stories, and platform updates from ServiceNow.
ITSM.tools - Independent blog covering ITSM tools, trends, and vendor comparisons.
Barclay Rae Consulting - Practitioner-written blog from one of the most respected independent ITSM consultants globally.
Podcasts
ITSM Crowd - Long-running ITSM practitioner podcast with episodes covering frameworks, tools, and industry trends.
Ticket Volume - Interviews with IT support and ITSM leaders about people, process, and technology.
ServiceNow Podcast Directory - Curated list of ServiceNow-specific podcasts covering platform, community, and thought leadership.
Books
ITIL 4 Foundation - The core ITIL 4 text published by Axelos. Essential reading for any ITSM practitioner.
The Phoenix Project - Gene Kim, Kevin Behr, George Spafford. Novel-format book demonstrating ITSM, DevOps, and lean principles in practice. Widely recommended as an introduction to modern IT operations.
The DevOps Handbook - Gene Kim et al. Practical companion to The Phoenix Project. Bridges ITSM and DevOps practices.
The ServiceNow Developer's Handbook - Tim Woodruff. Considered the definitive reference for ServiceNow administrators and developers.
Lean IT - Steve Bell and Mike Orzen. Applies lean manufacturing principles to IT operations and service management.
Tools and Platforms
ServiceNow - Enterprise ITSM platform. Market leader for large and mid-enterprise ITSM, ITOM, and ITBM.
Jira Service Management - Atlassian's ITSM platform. Strong in software-forward organisations using Confluence and Jira already.
Freshservice - Cloud-based ITSM platform well suited to mid-market organisations. Strong AI features and competitive pricing.
Ivanti Neurons - ITSM platform with strong asset management and endpoint management integration.
BMC Helix - Enterprise ITSM and AI operations platform from BMC. Competitor to ServiceNow in large enterprises.
Zendesk - Customer service and ITSM platform. Strong for organisations with a significant external customer service function alongside internal IT.
xMatters - Incident management and on-call scheduling. Integrates with ServiceNow, Jira, PagerDuty.
PagerDuty - Digital operations management platform for major incident response and on-call management.
Templates and Checklists
Major Incident Management Runbook Template - Atlassian's runbook template and guidance for P1/P2 incident response.
ITIL Process Templates — Process Street - Free process templates for common ITSM processes including change management, incident management, and problem management.
ServiceNow Update Set Checklist - Official best practices for Update Set management and cross-instance promotion.
CMDB Health Check Framework - ServiceNow community guidance on CMDB health scoring, completeness, and compliance metrics.
YouTube Channels
The AI Productivity Lab - ITSM and AI productivity content for service management professionals. Tips on using AI tools in day-to-day ITSM work.
ServiceNow - Official ServiceNow channel with product demos, Knowledge conference sessions, and platform tutorials.
ITSM Crowd - Long-running practitioner channel covering frameworks, tools, and career advice for ITSM professionals.
Atlassian - Jira Service Management tutorials, ITSM best practices, and Atlassian product walkthroughs.
---
Contributing
Contributions welcome. Please read the contribution guidelines before submitting a pull request. This list only accepts items that are actively maintained and genuinely useful to ITSM practitioners.
---
License
![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)
To the extent possible under law, the contributors have waived all copyright and related or neighbouring rights to this work.

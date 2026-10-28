# Hi, I'm Haiyang 👋

### Workflow Automation · AI Automation · Agent Integration

I help businesses connect their systems, reduce repetitive work, and turn business data into useful actions—with clear human review where it matters.

My production experience includes **ERP, WMS and CRM integrations**, sales and production-order reporting, and **DingTalk integrations**. I use mapping tables and reference fields to reconcile identifiers across systems. I have also integrated LLMs to organize information and generate business conclusions.

## What I build

- **Connected workflows:** API integrations, data synchronization, field mapping and reporting.
- **AI-assisted operations:** tool-calling agents that retrieve business data and prepare reviewable recommendations.
- **Reliable handovers:** input validation, execution records, tests and clear setup documentation.

## Featured projects

These runnable portfolio prototypes use fictional business data. Their AI workflows have been tested with real model calls. Screenshots show recorded execution results, including tool calls and pending review tasks.

### 1. Lead Operations Agent

**Help a sales team see which enquiry needs attention next.**

A Python/SQLite lead workbench combines duplicate prevention, stage tracking and activity history with a tool-calling agent. The agent reads open leads and proposes follow-up actions for human review. In the live example, it identified an overdue, unassigned lead and queued a follow-up suggestion.

[Explore code and setup](https://github.com/haiyangyereps/lead-intake-pipeline) · [Verification](https://github.com/haiyangyereps/lead-intake-pipeline/blob/main/VERIFICATION.md)

![Lead agent: pipeline lookup and pending follow-up task](https://raw.githubusercontent.com/haiyangyereps/lead-intake-pipeline/main/agent-live.png)

### 2. Guest Support Agent

**Prepare grounded answers and route sensitive requests for review.**

The agent retrieves approved property knowledge before drafting a response. Live tests cover a parking question and an urgent fire/refund request: the latter was escalated without a reply draft. Evidence-linked proposals stay in a local review queue.

[Explore code and setup](https://github.com/haiyangyereps/guest-reply-assistant) · [Verification](https://github.com/haiyangyereps/guest-reply-assistant/blob/main/VERIFICATION.md)

![Guest support agent: knowledge-grounded draft and urgent escalation](https://raw.githubusercontent.com/haiyangyereps/guest-reply-assistant/main/agent-live.png)

### 3. Sales Analysis Agent

**Turn validated sales metrics into focused management reviews.**

Python validates orders and refunds and calculates metrics before the model interprets them. The agent inspects channel performance and creates an evidence-linked review task. The live example investigates negative marketplace contribution while keeping facts separate from hypotheses. Contribution is not net profit.

[Explore code and setup](https://github.com/haiyangyereps/sales-report-automation) · [Verification](https://github.com/haiyangyereps/sales-report-automation/blob/main/VERIFICATION.md)

![Sales agent: validated channel metrics and management review task](https://raw.githubusercontent.com/haiyangyereps/sales-report-automation/main/agent-live.png)

## How I approach automation

**Understand the process → connect the data → validate the rules → add AI where useful → test and document.**

Critical calculations stay in application code. AI handles interpretation and drafting through defined tools. The portfolio agents use bounded execution, validated tool arguments and recorded proposals; approval records a local decision. They do not send customer messages or write to external business systems. These prototypes are separate from my client production work.

**Core tools:** Python · REST APIs · SQL / SQLite · Webhooks · OpenAI-compatible tool calling · Git

Have a workflow involving disconnected systems or repeated manual steps? [Find me on Upwork](https://www.upwork.com/freelancers/~012078f8bc5443b3bf).

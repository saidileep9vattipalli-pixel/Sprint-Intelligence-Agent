# Sprint Intelligence Agent

An agentic AI workflow that automatically analyzes Agile sprint reports 
and drafts professional stakeholder emails using multi-step AI orchestration.

## Live Workflow
View Live Workflow: https://saidileep.app.n8n.cloud/workflow/oOP54Kyq2seXGLU5 
## What It Does 

- **Step 1 — Sprint Analyzer:** Accepts a sprint report via chat, 
analyzes it, and produces structured output: summary, key risks, 
and recommendations
- **Step 2 — Email Drafter:** Takes the analysis and automatically 
drafts a professional stakeholder update email with subject line, 
summary, risks, and next steps

## Tech Stack

- n8n (workflow orchestration)
- OpenAI GPT-4 (AI model)
- Multi-agent pipeline architecture
- Chat-triggered interface

## Business Problem Solved

Scrum Masters and Delivery Managers spend 30-60 minutes after every 
sprint manually writing stakeholder updates. This agent reduces that 
to under 60 seconds with consistent, high-quality output.

## Sample Output

**Input:** Raw sprint report pasted into chat

**Agent 1 Output:**
- Summary of sprint performance
- Key risks and blockers identified
- Actionable recommendations

**Agent 2 Output:**
- Professional stakeholder email with subject line
- Risk summary with business impact
- Recommended next steps

## Impact

- ~60% reduction in sprint reporting time
- Consistent, structured output across all sprints
- Scalable to any Agile team

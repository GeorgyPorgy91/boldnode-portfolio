# AI-Driven Intake Automation

An autonomous intake workflow that processes new registrations 
instantly — from raw form submission to personalised draft email 
and team notification, in seconds.

---

## The Problem

Processing new registrations manually takes time and introduces 
inconsistency. Someone reads the form, updates a spreadsheet, 
writes a personalised response, and notifies the team. 
This workflow eliminates all of it.

---

## What It Does

1. Triggers when a new registration arrives via intake form
2. Sends the registration data to Google Gemini for analysis
3. AI generates a personalised draft email based on the intake content
4. Updates the CRM / database with the new record
5. Creates the draft email ready for review
6. Sends a Slack notification to the team with a summary

---

## Tech Stack

| Tool | Role |
|---|---|
| n8n | Workflow orchestration |
| Google Gemini 2.5 Flash | Personalised email drafting |
| Google Sheets | CRM / database |
| Slack | Team notification |
| Google Forms / Tally | Intake form trigger |

---

## Flow Overview
```
New Registration (Intake Form)
        ↓
AI Recruiter & Copywriter (Gemini 2.5 Flash)
— analyses intake data, generates personalised email draft
        ↓
Update CRM / Database (Google Sheets)
        ↓
Create Draft Email
        ↓
Slack notification to team
```

---

## Key Concepts Demonstrated

- Event-driven automation triggered by form submission
- Generative AI for personalised communication at scale
- Structured output parsing to enforce consistent JSON schema
- CRM update integrated into the same flow
- Human-in-the-loop via draft email — AI prepares, human approves

---

*Built by George Panaite — [boldnode.nl](https://boldnode.nl) 
| [LinkedIn](https://linkedin.com/in/george-panaite)*

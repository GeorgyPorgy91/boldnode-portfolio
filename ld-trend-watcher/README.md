# Autonomous L&D Trend Watcher

An autonomous AI agent that scans global Learning & Development news 
every morning and turns it into ready-to-publish social media content — 
including AI-generated visuals. Zero human input required.

---

## The Problem

Marketing and content teams in L&D organizations spend hours 
manually scanning industry news, distilling insights, and drafting 
LinkedIn posts. This workflow eliminates that entirely.

---

## What It Does

1. Triggers automatically every morning at 09:00
2. Scans the eLearning Industry RSS feed for the latest article
3. Filters to the single most recent item
4. Sends the article to Google Gemini for analysis
5. Generates three outputs in Dutch:
   - A concise trend insight (2 sentences)
   - A ready-to-publish LinkedIn draft with emojis
   - An English image prompt for visual generation
6. Generates a matching visual via Pollinations AI
7. Posts everything to a Slack channel for the marketing team
8. Logs the trend, insight and LinkedIn draft to Google Sheets

---

## Tech Stack

| Tool | Role |
|---|---|
| n8n | Workflow orchestration |
| Google Gemini 2.5 Flash | Trend analysis & content generation |
| Pollinations AI | AI image generation (free, no API key required) |
| Slack | Distribution to marketing team |
| Google Sheets | Content calendar logging |
| RSS Feed (eLearning Industry) | News source |

---

## Arc

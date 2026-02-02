# LinkedIn Job Matcher (n8n + AI)

An automated job-search workflow built using n8n that scans LinkedIn jobs, 
matches them against my resume using AI, generates a match score and cover letter, 
and sends high-fit roles directly to Telegram.

## Key Features
- Automated LinkedIn job scraping
- Resume-to-job matching using AI
- Match scoring and AI-generated cover letters
- Google Sheets tracking
- Real-time Telegram alerts for high-fit roles

## Tech Stack
- n8n (workflow automation)
- OpenAI (job matching & cover letter generation)
- LinkedIn job search
- Google Sheets
- Telegram Bot API

## Workflow
The workflow runs on a schedule, processes jobs one by one to avoid rate limits, 
evaluates job fit using AI, stores results, and alerts only high-scoring roles.

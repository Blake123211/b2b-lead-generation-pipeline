# B2B Lead Generation Pipeline

An automated B2B lead generation and cold outreach pipeline built for targeting US-based founders of small Facebook/Meta ads agencies serving ecommerce brands.

## What It Does

- Automatically sources pre-qualified leads matching a custom ICP (Ideal Customer Profile)
- Uses Claude AI to write personalized cold emails for each prospect
- Sends 7 emails per day via Gmail on a weekday schedule on autopilot
- Logs every contact in Google Sheets and prevents duplicate outreach
- Reduced LinkedIn prospecting time by 80%

## How It Works

1. Apify scrapes leads at $1 per 1,000 contacts
2. Apollo.io and Vibe Prospecting enrich leads with email and company data
3. Claude AI generates personalized email copy for each prospect
4. n8n workflow sends emails via Gmail API on automated schedule
5. Google Sheets logs all outreach and flags duplicates

## Tech Stack

- n8n (workflow automation)
- Claude AI API (personalized email generation)
- Gmail API / Google Workspace
- Apollo.io (lead enrichment)
- Apify (web scraping)
- Vibe Prospecting (B2B database)
- Google Sheets (logging and deduplication)

## Results

- 1,000+ leads processed with automated enrichment
- 7 personalized emails sent daily on autopilot
- 80% reduction in manual LinkedIn prospecting time

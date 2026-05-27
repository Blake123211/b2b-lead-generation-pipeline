<img width="1375" height="655" alt="Screenshot 2026-05-27 at 8 37 04 AM" src="https://github.com/user-attachments/assets/c099c9b7-eb7c-49f9-bb55-c4037af9b591" />
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

<img width="1375" height="655" alt="Screenshot 2026-05-27 at 8 37 04 AM" src="https://github.com/user-attachments/assets/c099c9b7-eb7c-49f9-bb55-c4037af9b591" />

<img width="1436" height="542" alt="Screenshot 2026-05-27 at 8 37 42 AM" src="https://github.com/user-attachments/assets/ef915d18-3298-4c9c-99dd-467830c33dfd" />

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

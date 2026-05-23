# GTM Lead Enrichment & Validation System (n8n)

An end-to-end n8n workflow for automated lead enrichment and validation.

## What it does

- Ingests scraped Google Maps business data and maps + scores leads into a structured Google Sheet
- Searches for missing website and Instagram URLs using SearchAPI and fills them in automatically
- Validates email addresses across all leads and triggers a Bright Data scraping flow for any business with a missing or invalid email
- The output is a fully enriched, scored, and contact-ready lead list — built to run with zero manual work

## Tools Used
n8n, Google Sheets, SearchAPI, Bright Data

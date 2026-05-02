#🚀 AI Job Scraper — Structured Data Extraction with LLMs

An intelligent web scraping pipeline that combines browser automation + LLM-powered extraction to transform unstructured job listings into clean, structured datasets ready for production use.

🧠 What This Project Does

This scraper goes beyond traditional scraping.

Instead of just collecting raw HTML, it:

Crawls job listing pages dynamically using a headless browser
Navigates into each job detail page
Uses an LLM (via OpenRouter) to extract and structure meaningful data
Enriches listings with inferred metadata like category, experience level, and tags

👉 Result: Production-ready job data, not messy scraped text.

⚙️ Tech Stack
Python
Playwright — browser automation (Chromium)
Crawl4AI — AI-powered crawling & extraction
Pydantic — strict schema validation
BeautifulSoup — HTML parsing
OpenRouter (LLM API) — intelligent data extraction
🔍 Features
✅ Multi-page crawling (pagination support)
✅ AI-powered structured extraction (schema-based)
✅ Automatic metadata inference:
Category (Tech, Finance, Health, etc.)
Experience level (junior, mid, senior)
Job type (internship, part-time, full-time)
Work mode (remote, hybrid, in-office)
Tags (tech stack, skills, etc.)
✅ Deduplication of job listings
✅ Async crawling for performance
✅ Export to:
CSV
JSON

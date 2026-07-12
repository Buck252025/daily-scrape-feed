# Daily Scrape — public feed

Published automatically by the private `daily-brief` GitHub Action after each successful run.
Consumed by https://www.customtechnology.us/daily-scrape.html

- `latest.md` — most recent brief (Content Angles section removed before publish)
- `meta.json` — `{ "date": "...", "updated": "ISO timestamp" }`
- `briefs/` — dated archive

If a day's run fails, nothing is pushed — the previous brief remains current by design.

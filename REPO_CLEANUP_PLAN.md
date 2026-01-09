# Repository Cleanup Plan

> Making your GitHub profile shine

---

## Phase 1: Pin Best Repos (Do First)

These 6 repos should be pinned on your profile:

| Repo | Why Pin It | Action Needed |
|------|-----------|---------------|
| `awesome-webscraping-blogs` | Your top repo (9⭐), shows curation | Ready to pin |
| `brand_analytics_automation` | Shows real automation skills | Add better description |
| `django-celery-redis-example` | Shows backend + queue skills | Ready to pin |
| `zillow-webscraper-chrome-extension` | Shows JS + extension skills | Add README |
| `send-sellers-messages` | Shows e-commerce automation | Add description |
| `bullmq-redis-scraper` | Shows current learning | Keep updating |

---

## Phase 2: Add Descriptions (High Impact)

Repos that need descriptions:

| Repo | Suggested Description |
|------|----------------------|
| `linkedin-companies-scraper` | Scrape company profiles from LinkedIn using Python |
| `indeed_crawlers` | Job listings scraper for Indeed.com |
| `opentable_scraping` | Restaurant data scraper for OpenTable |
| `Muckrack_Scraper` | Journalist and PR professional data from MuckRack |
| `chrome_web_store_crawler` | Chrome extension metadata scraper |
| `ec2-pricing-on-demand-price-crawler` | AWS EC2 pricing data collector |
| `angi_crawler` | Home service professional data from Angi.com |
| `bazos_crawler` | Classifieds scraper for Bazos marketplace |
| `sqmresearch_scraper` | Australian property research data scraper |
| `emoryhealthcare_crawler` | Healthcare provider data scraper |
| `nepal-import-export-crawler` | Nepal trade statistics scraper |
| `producthunt2021` | Product Hunt launches scraper |
| `webscraping_hipages` | Australian tradie directory scraper |
| `automate_medicomtoy` | Japanese lottery ticket automation |
| `gh_repo_automate` | Bulk GitHub repository creation tool |
| `valpak_crawler` | Coupon and deals scraper |
| `web_archive_image_crawler` | Wayback Machine image extractor |
| `ripehouse_webscraping_up` | Real estate data scraper |
| `shopify_webscraping_up` | Shopify store data extractor |
| `scraping_binklist` | BIN database scraper |

---

## Phase 3: Archive Old/Unused Repos

These repos add clutter and can be archived:

### Academic/Old Projects (Archive)
- `CPP` - Old IOE programs
- `Cprogramming` - Old C programs
- `fyp` - Old final year project
- `EngineeringEnglishSummary` - Old notes
- `EnglishPractisingWords` - Old practice
- `OctaveTutorials` - Old Matlab
- `SmartHealthMonitoringSystem` - Old Arduino project
- `timer` - Old exam timer

### Empty/Unused Forks (Archive or Delete)
- `TestRepository`
- `projectslide1`
- `us_states_counties_states`
- `zipcodes`
- `realtors_profiles`
- `Random-Errors-Logs`
- `proxy_ip_checker`
- `ioe_syllabus_app_scraping`
- `languages`

### Learning Repos to Consolidate
Instead of many small repos, consider:
- Archive: `c_tutorial`, `vim_tutorial`, `D3Guide`, `GUIProject`
- Keep: `JavaScript30`, `python_examples`

---

## Phase 4: Polish Key Scrapers

Pick 3 scrapers and make them showcase-ready:

### Suggested: `brand_analytics_automation`

Add to README:
```markdown
# Amazon Brand Analytics Automation

Automate downloading Amazon Search Terms from Seller Central.

## Features
- Automated login handling
- Search term data extraction
- CSV/Excel export
- Scheduled runs via cron

## Tech Stack
Python | Selenium | Pandas

## Setup
[Installation steps]

## Usage
[Code examples]

## Screenshots
[Add screenshots]
```

### Suggested: `zillow-webscraper-chrome-extension`

Add to README:
```markdown
# Zillow Scraper Chrome Extension

Extract property listings from Zillow and export to CSV.

## Features
- One-click scraping
- Multiple listing support
- CSV export
- Price history extraction

## Installation
1. Download extension
2. Load unpacked in Chrome
3. Navigate to Zillow
4. Click extension icon

## Demo
[Add GIF showing usage]
```

### Suggested: `linkedin-companies-scraper`

Add to README:
```markdown
# LinkedIn Company Scraper

Extract company information from LinkedIn company pages.

## Data Extracted
- Company name
- Industry
- Size
- Location
- Description
- Employee count

## Usage
[Code examples]

## Disclaimer
For educational purposes only. Respect LinkedIn's ToS.
```

---

## Phase 5: Update Topics/Tags

Add topics to improve discoverability:

| Repo | Topics to Add |
|------|---------------|
| `awesome-webscraping-blogs` | `awesome-list`, `web-scraping`, `resources`, `python`, `scrapy` |
| `brand_analytics_automation` | `amazon`, `automation`, `selenium`, `python`, `scraping` |
| `linkedin-companies-scraper` | `linkedin`, `scraping`, `python`, `data-extraction` |
| `django-celery-redis-example` | `django`, `celery`, `redis`, `python`, `task-queue` |
| `zillow-webscraper-chrome-extension` | `chrome-extension`, `zillow`, `real-estate`, `scraping`, `javascript` |

---

## Execution Order

### Day 1 (Done)
- [x] Create profile README

### Day 2
- [ ] Pin 6 repos
- [ ] Add descriptions to top 10 scrapers

### Day 3
- [ ] Archive 10 old/unused repos
- [ ] Add topics to top 5 repos

### Day 4
- [ ] Polish `brand_analytics_automation` README
- [ ] Polish `zillow-webscraper-chrome-extension` README

### Day 5
- [ ] Polish `linkedin-companies-scraper` README
- [ ] Final review

---

## Commands Reference

```bash
# Add description to repo
gh repo edit REPO_NAME --description "New description"

# Add topics to repo
gh repo edit REPO_NAME --add-topic topic1 --add-topic topic2

# Archive a repo
gh repo archive REPO_NAME

# Delete a repo (careful!)
gh repo delete REPO_NAME --yes
```

---

## Result

**Before:** 116 repos, scattered, hard to navigate

**After:**
- 6 pinned showcase repos
- 20+ repos with proper descriptions
- 15+ archived old repos
- 3 polished, demo-ready projects
- Clear professional brand

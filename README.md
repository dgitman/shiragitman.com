# Counting the Days for Shira

A public, self-updating timeline at [shiragitman.com](https://shiragitman.com/).

- Days since May 21, 2026
- Days until the bench trial on November 4, 2026
- A dot for every day in between, with today marked in gold

## How to use

Open `index.html` in any web browser. The counts recalculate automatically from your device's date — no updates ever needed. If left open, the page refreshes itself at midnight.

## Search indexing

The site is intentionally crawlable and indexable. The SEO implementation includes:

- Canonical URLs and indexable robots metadata on every HTML page
- A root `sitemap.xml` referenced from `robots.txt`
- `WebSite` and `WebPage` JSON-LD structured data
- Open Graph and Twitter metadata, including image descriptions
- Dedicated HTML summaries for the custody order and contempt motion
- Explicit language distinguishing an entered court order from allegations in a motion

After deployment, submit `https://shiragitman.com/sitemap.xml` in Google Search Console and use URL Inspection to request indexing for the three canonical HTML pages.

## Public-content note

This site and the linked court PDFs are publicly reachable. Search-engine controls do not provide privacy or access control.

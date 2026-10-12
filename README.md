# How to Check Whether a Backlink Is Indexed in Google

A practical field guide for link builders and SEO professionals who need to verify that placed backlinks are actually indexed by Google and passing link equity.

## Why Backlink Indexation Matters

When a page linking to your site isn't indexed by Google, that backlink passes **zero PageRank**. Google must first crawl and index the donor page before any link equity flows. For link-building campaigns, a significant portion of placements may be invisible to Google — especially on newer or lower-authority sites.

## 6 Methods to Verify Indexation

| Method | Works on 3rd-party domains | Scale | Accuracy |
|---|---|---|---|
| `site:` operator | ✓ | 1–10 URLs | Medium |
| Cache check | ✓ | 1–5 URLs | Medium |
| GSC URL Inspection | Own domains only | 1 URL | High |
| SEO tools (Ahrefs/Semrush) | ✓ | Unlimited | Crawler data, not Google |
| [SpeedyIndex bulk checker](https://en.speedyindex.com/google-index-checker/) | ✓ | Thousands | High |

### 1. The `site:` Operator
Search `site:donorsite.com/specific-page`. If the page appears in Google results, it's indexed. Quick for spot-checks; may miss indexed pages not surfaced by the operator.

### 2. Google Cache Check
Search `cache:donorsite.com/specific-page`. A fresh cache entry confirms recent crawling.

### 3. Google Search Console URL Inspection
Definitive status — but only for pages you own in GSC. Not usable for third-party donor sites.

### 4. Third-Party SEO Tools
Ahrefs, Semrush, Majestic show crawler discovery, not Google indexation. Use as an initial filter.

### 5. Google Indexing API
Designed only for JobPosting and BroadcastEvent schema pages. Not appropriate for ordinary backlinks.

### 6. Bulk Verification — SpeedyIndex
For 50+ URLs, manual methods don't scale. [Check Google index in bulk](https://en.speedyindex.com/google-index-checker/) with SpeedyIndex — no GSC access to donor sites required.

## 8-Step Workflow

1. Export all placed backlink URLs from your campaign tracker
2. Separate your own pages (check via GSC) from third-party pages
3. For ≤10 URLs: use `site:` + cache check
4. For 10–50 URLs: run through your preferred SEO tool
5. For 50+ URLs: run through SpeedyIndex bulk checker
6. Flag unindexed URLs older than 3 weeks as priority action items
7. For each flagged URL: check noindex tag, robots.txt, and content quality on the donor page
8. Schedule quarterly re-checks — pages can fall out of index over time

## Common Mistakes

- **Checking too soon** — Wait at least 2 weeks after publication before the first check
- **Confusing crawler data with Google indexation** — Tool visibility ≠ Google-indexed
- **Not rechecking** — Pages can deindex weeks or months after initial crawl
- **Reporting tool link counts as "indexed links"** to clients

## Resources

- [Check Google index in bulk](https://en.speedyindex.com/google-index-checker/)
- [Backlink indexation guide](https://en.speedyindex.com/how-to-check-backlink-indexation/)
- [Full article on GitHub Pages](https://uskotoivo81-netizen.github.io/check-whether-backlink-indexed-google/)

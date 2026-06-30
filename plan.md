# Plan: Canadian Bitcoin Tax Guide Section

## Goal
Add a comprehensive, CRA-aligned Canadian Bitcoin tax guide to `index.html` on giantstepslearning.com, matching the site's clean educational style.

## Placement
- **After:** `#shakepay` (Buy Bitcoin with Shakepay)
- **Before:** `#contact` (Get In Touch)
- Insert between Shakepay and `#get-started` for logical flow: buy → taxes → get started → contact

## Files to Change
| File | Changes |
|------|---------|
| `index.html` | Nav link, step 5 in How-to, new `#tax-guide` section, SEO meta tags |
| `style.css` | Tax section styles (toc, table, disclaimer, CTA) — reuses existing design tokens |

## Section Structure (`#tax-guide`)
1. **Intro** — educational disclaimer (not tax advice)
2. **How CRA Treats Bitcoin** — commodity, capital property
3. **Taxable Events** — bulleted list
4. **Capital Gains Basics** — 50% inclusion rate, example
5. **Adjusted Cost Base (ACB)** — average-cost method
6. **Capital vs Business Income** — comparison table
7. **Common Transactions** — buying, selling, swapping, spending, gifts
8. **Superficial Loss Rule** — 30-day window
9. **Record Keeping** — what to track
10. **Tax Software Comparison** — responsive table (Koinly, CoinTracker, CoinTracking, Shakepay exports)
11. **Filing Checklist** — Schedule 3, T1
12. **CTA** — Shakepay referral button

## Navigation Updates
- Top nav: add `<a href="#tax-guide">Canadian Taxes</a>` between Shakepay and Get Started
- How to Get Off Zero: add Step 5 "Understand Canadian Taxes" with anchor link

## Accessibility & SEO
- Semantic headings (`h2` → `h3`, no skipped levels)
- `meta name="description"` in `<head>`
- Table with `<caption>`, `<thead>`, `scope` attributes
- Internal toc with `aria-label`
- Mobile: horizontal scroll wrapper on comparison table

## Note on Content
Original tax guide text was not found in session history. Content is CRA-aligned educational material in Giant Steps tone. User can paste original copy for replacement if needed.
# BrightCart E-Commerce Profitability Analysis
**Prepared by:** Shubham Sahu
**Date:** June 2025
**Submitted to:** CEO, BrightCart

---

## Executive Summary

BrightCart generated $1M+ in gross revenue across 2024–2025
across 8 product categories and 4 sales channels. Despite strong
top-line revenue, net margins are shrinking due to four
compounding factors:

1. **28.15% of orders are unprofitable** (563 of 1,997 orders)
2. **Marketplace platform fees** eating channel margins
3. **$20,582 lost to returns** across all categories
4. **$100,701 in marketing budget** allocated to underperforming
   platforms

This memo identifies the root causes and provides specific,
data-backed recommendations to restore margin health.

---

## The Numbers at a Glance

| Metric | Value |
|---|---|
| Total Orders Analyzed | 1,997 |
| Gross Revenue | $277,648+ |
| Unprofitable Orders | 563 (28.15%) |
| Total Revenue Lost to Returns | ~$20,582 |
| Total Marketing Spend | $503,506 |
| Best Performing Category | Electronics (26.43% margin) |
| Worst Performing Category | Books (10.00% margin) |
| Best Channel | Mobile App (25.85% margin) |
| Worst Channel | Marketplace (11.19% margin) |
| Best Marketing Platform | TikTok Ads (24.4x ROAS) |
| Worst Marketing Platform | Email Marketing (5.4x ROAS) |

---

## Finding 1 — Category Profitability

| Category | Margin % | Total Profit | Return Rate |
|---|---|---|---|
| Electronics | 26.43% 🟢 | $13,973 | 8.61% |
| Toys | 22.44% 🟢 | $8,756 | 7.03% |
| Home & Kitchen | 21.66% 🟢 | $6,689 | 6.00% |
| Food & Beverage | 20.59% 🟢 | $7,592 | 5.67% |
| Sports | 20.28% 🟢 | $7,597 | 7.19% |
| Clothing | 16.72% 🟠 | $6,272 | 8.19% |
| Beauty | 15.02% 🟠 | $3,104 | 5.88% |
| Books | 10.00% 🔴 | $2,236 | 8.40% |

**Root cause of Books underperformance:** High shipping cost
relative to low average selling price destroys margin.
Books has the lowest revenue ($22,360) but proportionally
high shipping costs.

**Root cause of Beauty underperformance:** Lowest return rate
(5.88%) confirms product quality is strong. Discount policy
is eroding margin — not returns.

---

## Finding 2 — Channel Profitability

| Channel | Margin % | Avg Profit/Order | Platform Fee |
|---|---|---|---|
| Mobile App | 25.85% 🟢 | $36.33 | $0.00 |
| Website | 22.57% 🟢 | $31.57 | $0.00 |
| Social Commerce | 12.74% 🟠 | $17.11 | $9.87 |
| Marketplace | 11.19% 🟠 | $15.40 | $18.97 |

Marketplace charges $18.97 per order in platform fees —
cutting avg profit per order nearly in half vs owned channels.
Without platform fees, Marketplace would perform similarly
to Website.

---

## Finding 3 — Return Rate & Revenue Loss

| Category | Return Rate | Revenue Lost |
|---|---|---|
| Electronics | 8.61% 🔴 | $4,078 |
| Clothing | 8.19% 🔴 | $3,209 |
| Food & Beverage | 5.67% 🟢 | $3,505 |
| Beauty | 5.88% 🟢 | $866 |

**Critical finding:** Electronics is simultaneously the best
margin category AND the highest return revenue loss ($4,078).
Returns are the single biggest threat to Electronics dominance.

Social Commerce has the highest channel return rate at 9.14%
— product discovery via social creates expectation mismatches.

---

## Finding 4 — Marketing ROAS

| Platform | ROAS | CPA | Verdict |
|---|---|---|---|
| TikTok Ads | 24.4x 🟢 | $3.93 | Protect + increase |
| Influencer | 23.4x 🟢 | $4.80 | Protect |
| Instagram Ads | 17.0x 🟢 | $5.55 | Protect |
| Google Ads | 13.7x 🟢 | $6.48 | Reduce |
| Facebook Ads | 11.3x 🟠 | $8.38 | Reduce significantly |
| Email Marketing | 5.4x 🔴 | $26.01 | Reduce aggressively |

---

## Top 3 Recommendations

### Recommendation 1 — Fix the Books Margin Problem
Books generates only 10% margin vs 19% company average.
**Action:** Introduce minimum order value of $35 for free
shipping on Books. Orders below threshold pay shipping.
This alone could recover 4–6 margin points.
**Expected impact:** Books margin improves from 10% → 14–16%

### Recommendation 2 — Shift Volume from Marketplace to Mobile App
Marketplace earns $15.40 avg profit per order vs
Mobile App's $36.33 — a 2.36x difference driven entirely
by the $18.97 platform fee.
**Action:** Run Mobile App exclusive promotions and
reduce SKUs listed on Marketplace to only high-margin
Electronics and Toys where the fee is absorbed.
**Expected impact:** $10–15 additional profit per redirected order

### Recommendation 3 — Reallocate 20% Marketing Budget
Cut $100,701 from underperforming platforms and
reinvest into TikTok and Influencer.

| Platform | Action | Amount |
|---|---|---|
| Email Marketing | Cut 60% | Save $14,677 |
| Facebook Ads | Cut 40% | Save $42,581 |
| Google Ads | Cut 26% | Save $39,662 |
| Instagram Ads | Cut 5% | Save $3,258 |
| TikTok Ads | Increase | Reinvest savings |
| Influencer | Increase | Reinvest savings |

**Expected impact:** Moving budget from 5.4x ROAS platforms
to 24.4x ROAS platforms could increase revenue attributed
per marketing dollar by 3–4x.

---

## Conclusion

BrightCart's margin erosion is not a revenue problem —
it is a cost structure and allocation problem. The company
is selling the right products (strong category margins)
through the wrong mix of channels (too much Marketplace)
with misallocated marketing spend (too much Facebook/Email).

Implementing these three recommendations targets the three
largest margin leaks simultaneously and can bring net margin
meaningfully closer to healthy e-commerce benchmarks of 20%+.

---
*Analysis: Python (pandas, matplotlib), MySQL, Power BI*
*Dataset: BrightCart synthetic retail dataset, 2024–2025*
*Analyst: Shubham Sahu | June 2025*
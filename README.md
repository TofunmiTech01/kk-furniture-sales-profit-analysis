# 🪑 KK Furniture Sales & Profit Performance Dashboard (2014–2017) — Excel Business Intelligence Project

> **A comprehensive Excel-powered analytics dashboard uncovering four years of sales, profit, and operational performance across $742K in revenue, 2,121 orders, 707 customers, and 375 unique furniture products — built entirely in Microsoft Excel with Pivot Tables, dynamic slicers, and dual-page interactive visualizations.**

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Business Context](#business-context)
- [Dataset Summary](#dataset-summary)
- [Tools & Technologies](#tools--technologies)
- [Dashboard Preview](#dashboard-preview)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Analytical Insights](#analytical-insights)
  - [Revenue & Profit Growth Trajectory](#1-revenue--profit-growth-trajectory)
  - [Sub-Category Performance](#2-sub-category-performance)
  - [Regional Analysis](#3-regional-analysis)
  - [Customer Segment Analysis](#4-customer-segment-analysis)
  - [Shipping Mode Analysis](#5-shipping-mode-analysis)
  - [Geographic Performance](#6-geographic-performance)
  - [Monthly & Seasonal Trends](#7-monthly--seasonal-trends)
  - [Quarterly Breakdown](#8-quarterly-breakdown)
  - [Product-Level Intelligence](#9-product-level-intelligence)
  - [Profit Margin Health](#10-profit-margin-health)
- [Strategic Recommendations](#strategic-recommendations)
- [Live Dashboard](#live-dashboard)
- [Connect With Me](#connect-with-me)

---

## Project Overview

Revenue growth without profit growth is not a success story — it is a warning sign. KK Furniture grew sales by 37% from 2014 to 2017, yet ended that same period with profits nearly halved from peak. Understanding *why* requires peeling back the layers of sub-category performance, regional dynamics, shipping cost structures, and product-level profitability — exactly what this dashboard delivers.

This project presents a fully interactive, dual-page Excel dashboard analyzing **$741,999 in furniture sales** across **2,121 orders**, **707 unique customers**, **375 products**, and **4 years (2014–2017)** — built entirely in Microsoft Excel using Pivot Tables, GETPIVOTDATA formulas, dynamic slicers, custom charts, and Bing Maps integration. Two dashboard pages cover the full picture: Page 1 for sales and operational performance, Page 2 for deep profit and margin intelligence.

---

## Business Context

KK Furniture operates across four U.S. regions — West, East, Central, and South — serving three customer segments (Consumer, Corporate, Home Office) across four product sub-categories: Chairs, Tables, Bookcases, and Furnishings. The central business challenge this analysis addresses:

- Sales are growing year-over-year, yet profit growth is erratic and declining in 2017
- Two of four product sub-categories are structurally loss-making
- One-third of all orders generate negative profit
- Regional profitability is sharply divided — with the Central region operating at a net loss

These are not small inefficiencies. They are strategic crises hiding behind a healthy revenue headline — and this dashboard makes them visible.

---

## Dataset Summary

| Attribute | Detail |
|---|---|
| **Period Covered** | 2014 – 2017 |
| **Total Records** | 2,121 rows |
| **Total Orders** | 1,764 unique orders |
| **Total Customers** | 707 unique customers |
| **Unique Products** | 375 |
| **Total Sales** | $741,999.80 |
| **Total Profit** | $18,451.27 |
| **Overall Profit Margin** | 2.49% |
| **Regions** | West, East, Central, South |
| **Segments** | Consumer, Corporate, Home Office |
| **Sub-Categories** | Chairs, Tables, Bookcases, Furnishings |
| **Ship Modes** | Standard Class, Second Class, First Class, Same Day |
| **Key Fields** | Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Segment, City, State, Region, Sub-Category, Product Name, Sales, Quantity, Profit, Duration |

---

## Tools & Technologies

- **Microsoft Excel** — End-to-end analytics and dual-page dashboard design
- **Pivot Tables** — Multi-dimensional aggregation across all key dimensions
- **GETPIVOTDATA** — Dynamic KPI card extraction
- **Power Query** — Data transformation and computed column generation
- **Excel Slicers** — Interactive filtering by Year, Region, Month, and Sub-Category
- **Custom Charting** — Line, bar, donut, map, and combination visualizations
- **Bing Maps Integration** — State-level sales and profit geographic mapping
- **Conditional Formatting** — Profit/loss visual flagging across KPI cards

---

## Dashboard Preview

![KK Furniture Dashboard Page 1 — Sales Performance](https://github.com/TofunmiTech01/kk-furniture-sales-profit-analysis/blob/main/KK_Furniture_Dashboard1.PNG)

![KK Furniture Dashboard Page 2 — Profit Intelligence](https://github.com/TofunmiTech01/kk-furniture-sales-profit-analysis/blob/main/KK_Furniture_Dashboard2.PNG)

---

## Key Performance Indicators (KPIs)

| KPI | 2014 | 2015 | 2016 | 2017 |
|---|---|---|---|---|
| **Total Sales** | $157,193 | $170,518 | $198,901 | $215,387 |
| **Sales YoY Change** | — | +8.5% | +16.6% | **+8.3%** |
| **Total Profit** | $5,458 | $3,015 | $6,960 | $3,018 |
| **Profit YoY Change** | — | -44.8% | +130.8% | **-56.6%** |
| **Profit Margin** | 3.47% | 1.77% | 3.50% | 1.40% |
| **Quantity Sold** | 1,623 | 1,775 | 2,193 | 2,437 |
| **Orders** | 353 | 371 | 476 | 564 |

**4-Year Cumulative Totals:**
- Total Sales: **$741,999**
- Total Profit: **$18,451**
- Overall Margin: **2.49%** | Average Order Margin: **3.89%** | Median Order Margin: **11.1%**

---

## Analytical Insights

### 1. Revenue & Profit Growth Trajectory

The four-year performance story is one of **growing sales disguising deteriorating profitability:**

| Year | Sales | Profit | Margin |
|---|---|---|---|
| 2014 | $157,193 | $5,458 | 3.47% |
| 2015 | $170,518 | $3,015 | 1.77% |
| 2016 | $198,901 | $6,960 | 3.50% |
| 2017 | $215,387 | $3,018 | 1.40% |

**Key Findings:**

- **Sales grew every single year** — from $157K in 2014 to $215K in 2017, a 37% cumulative increase. On the surface, a business in growth mode.
- **Profit tells a completely different story.** It oscillates violently: -44.8% in 2015, then +130.8% recovery in 2016, then a devastating -56.6% collapse in 2017 — ending 2017 at the same profit level ($3,018) as 2015, despite generating $45K more in sales.
- **2017 is the alarm bell:** The business sold more than ever (2,437 units, $215K revenue) yet made the thinnest profit margin in four years (1.40%). More volume, less efficiency — a classic sign of unprofitable growth.
- **The profit volatility is driven by Tables**, whose loss deepened to -$8,141 in 2017 alone — more than wiping out the profit gains from Chairs and Furnishings.

---

### 2. Sub-Category Performance

This is the most critical finding in the entire analysis:

| Sub-Category | Total Sales | Total Profit | Margin | Verdict |
|---|---|---|---|---|
| **Chairs** | $328,449 | $26,590 | **8.1%** | ✅ Star Performer |
| **Furnishings** | $91,705 | $13,059 | **14.2%** | ✅ Margin Champion |
| **Bookcases** | $114,880 | -$3,473 | **-3.0%** | ❌ Chronic Loss-Maker |
| **Tables** | $206,966 | -$17,725 | **-8.6%** | 🚨 Critical Problem |

**Key Findings:**

- **Tables is the single biggest threat to business health.** At $206,966 in sales (27.9% of total revenue), it is the second-largest sub-category — yet it has never turned a profit in any single year across 2014–2017. Its annual loss has been *worsening*: -$3,124 → -$3,510 → -$2,951 → **-$8,141**. The 2017 acceleration is alarming.
- **Bookcases have lost money in 3 of 4 years.** Only 2016 delivered a marginal profit of $212. The structural profitability issue suggests deep pricing or cost problems.
- **Furnishings is the hidden gem of the portfolio** — 14.2% margin on $91.7K in sales. Despite being the smallest revenue sub-category, it delivers the highest return on every dollar sold. It is systematically underinvested.
- **Chairs carries the entire business.** $26,590 in profit from $328,449 in sales. Without Chairs, KK Furniture would have reported a net loss of -$8,139 across four years. The entire business profitability rests on one sub-category.

---

### 3. Regional Analysis

| Region | Sales | Profit | Margin | Sales Share |
|---|---|---|---|---|
| **West** | $252,613 | $11,505 | **4.6%** | 34.0% |
| **East** | $208,291 | $3,046 | **1.5%** | 28.1% |
| **Central** | $163,797 | **-$2,871** | **-1.8%** | 22.1% |
| **South** | $117,299 | $6,771 | **5.8%** | 15.8% |

**Key Findings:**

- **The West is the profit engine**, generating $11,505 (62.3% of total profit) from 34% of sales — the only region with both scale and healthy margins. California alone accounts for $156,064 in sales and $9,163 in profit.
- **The South punches above its weight** — 15.8% of sales but 36.7% of profit. With a 5.8% margin (the highest of any region), it is the most efficient market in the portfolio. Its growth is being underinvested relative to its performance.
- **The Central region is a net destroyer of value** at -$2,871 in profit. Despite $163,797 in sales, the Central region costs the company money. A breakdown reveals the culprit: Tables (-$3,560), Furnishings (-$3,906), and Bookcases (-$1,998) are all loss-making in Central — only Chairs ($6,593) saves it from deeper losses.
- **The East is profitable but barely** — $3,046 profit from $208,291 in sales is a 1.5% margin. Given that East is the second-largest region by revenue, this thin margin represents a massive missed opportunity.

---

### 4. Customer Segment Analysis

| Segment | Sales | Profit | Margin |
|---|---|---|---|
| **Consumer** | $391,049 | $6,991 | 1.79% |
| **Corporate** | $229,020 | $7,585 | 3.31% |
| **Home Office** | $121,931 | $3,875 | 3.18% |

**Key Findings:**

- **Consumer is the largest segment by sales (52.7%) but the lowest margin (1.79%)** — the classic high-volume, low-efficiency trap. Consumers likely demand more discounting and generate more return/loss activity.
- **Corporate is the most valuable segment per dollar of revenue** at 3.31% margin — more than 1.8x the Consumer margin. Growing Corporate accounts should be a top strategic priority.
- **Home Office mirrors Corporate efficiency** at 3.18% — a niche segment with premium margin characteristics, likely due to less price sensitivity and more purposeful purchases.
- **The regional-segment breakdown exposes the Central Consumer problem:** Central's Consumer segment loses -$3,994 — dragging the entire Central region into loss territory. Central Corporate (+$2,322) is the only Central segment generating meaningful positive profit.

---

### 5. Shipping Mode Analysis

| Ship Mode | Sales | Profit | Margin | Sales Share | Orders |
|---|---|---|---|---|---|
| **Standard Class** | $435,831 | $10,361 | 2.38% | **58.7%** | 1,248 |
| **Second Class** | $156,289 | $4,226 | 2.70% | 21.1% | 427 |
| **First Class** | $110,731 | $3,067 | 2.77% | 14.9% | 327 |
| **Same Day** | $39,149 | $797 | 2.04% | 5.3% | 119 |

**Key Findings:**

- **Standard Class dominates at 58.7% of total sales** — the business depends heavily on its cheapest, slowest shipping option. This is operationally efficient but may limit appeal for time-sensitive buyers.
- **First Class has the best margin (2.77%)** despite being a premium service — suggesting that customers who pay for faster shipping are less price-sensitive and more profitable overall.
- **Same Day has the lowest margin (2.04%)** — the urgency premium charged likely does not fully offset the elevated fulfillment cost, making it a marginal proposition at current pricing.
- **All four shipping modes operate in the 2.0–2.8% margin band**, suggesting that shipping mode itself is not the primary profit lever — product mix and regional pricing are far more impactful.
- From the dashboard, Standard Class represents **59%** of order volume, followed by Second Class at **20%**, First Class at **15%**, and Same Day at **6%**.

---

### 6. Geographic Performance

#### Top 10 States by Sales:

| Rank | State | Sales | Profit | Margin |
|---|---|---|---|---|
| 1 | **California** | $156,065 | $9,163 | **5.9%** |
| 2 | New York | $93,373 | $5,858 | 6.3% |
| 3 | Texas | $60,593 | **-$10,436** | -17.2% |
| 4 | Washington | $48,020 | $7,194 | **15.0%** |
| 5 | Pennsylvania | $39,355 | **-$7,197** | -18.3% |
| 6 | Illinois | $28,275 | **-$9,076** | -32.1% |
| 7 | Virginia | $25,322 | $5,204 | 20.6% |
| 8 | Ohio | $24,199 | **-$4,206** | -17.4% |
| 9 | Florida | $22,987 | -$2,255 | -9.8% |
| 10 | Michigan | $22,321 | $4,676 | 20.9% |

#### Top 6 Cities (as featured on Dashboard):

| City | Sales | Profit | Margin |
|---|---|---|---|
| **New York City** | $75,691 | $5,307 | 7.0% |
| **Seattle** | $40,996 | $6,209 | **15.1%** |
| **Los Angeles** | $54,000 | $3,072 | 5.7% |
| **San Francisco** | $36,357 | $1,491 | 4.1% |
| **Philadelphia** | $36,496 | **-$6,827** | **-18.7%** |
| **Houston** | $23,183 | **-$3,405** | **-14.7%** |

**Key Findings:**

- **California at $156,065 is the #1 revenue state by a massive margin** — nearly 1.7x the #2 state (New York at $93,373). Its 5.9% margin makes it both the largest and one of the more profitable markets.
- **The "Big State Profitability Trap":** Three of the top 5 revenue states — Texas (#3), Pennsylvania (#5), and Illinois (#6) — are all loss-making. Texas alone loses -$10,436 on $60,593 of sales (-17.2% margin). The business is generating significant revenue from states that actively destroy profit.
- **Washington State is the standout efficiency market** — $48,020 in sales at a 15.0% margin, the highest margin of any major state. Seattle's 15.1% city margin confirms this is a structurally healthy market.
- **Illinois is the worst state in the portfolio** at -32.1% margin. For every $1 of furniture sold in Illinois, the business loses 32 cents. This is not a rounding error — it is a fundamental market failure.
- **Philadelphia (-18.7%) and Houston (-14.7%) are the two most profit-destructive cities** among the top 6 highlighted on the dashboard — cities with significant order volumes that are actively bleeding the P&L.

---

### 7. Monthly & Seasonal Trends

| Month | Sales | Profit |
|---|---|---|
| January | $31,569 | **-$1,944** |
| February | $15,766 | $694 |
| March | $50,768 | $772 |
| April | $40,699 | $1,460 |
| May | $48,365 | $2,302 |
| June | $52,999 | $982 |
| July | $49,377 | $1,413 |
| August | $44,884 | $4 |
| September | $106,381 | $5,460 |
| October | $58,088 | **-$3,028** |
| November | $121,286 | $3,920 |
| December | $121,818 | $6,416 |

**Key Findings:**

- **November and December are the revenue kings**, each generating over $121K in sales — together representing 32.8% of annual revenue in just 2 of 12 months. The Q4 holiday and year-end spending effect is unmistakable.
- **September is the surprise performer** at $106,381 — the 3rd highest month by sales with a strong $5,460 profit. Back-to-school and Q3 corporate purchasing cycles likely drive this spike.
- **January is a profit disaster** — the second-highest order month in perception but it logs -$1,944 in profit on $31,569 in sales. Post-holiday discounting and clearance pricing likely explain this.
- **October loses money** (-$3,028) despite $58K in sales — unusual for a pre-holiday month and a red flag. Heavy discounting ahead of November promotions likely erodes October margins.
- **August nearly breaks even** ($4 profit on $44,884 in sales) — a concerning near-zero margin in a mid-volume month.
- The monthly profit trend from the dashboard shows extreme volatility, with sharp swings between profit and loss — a sign of inconsistent pricing discipline rather than predictable seasonal patterns.

---

### 8. Quarterly Breakdown

| Quarter | Sales | Profit | Margin |
|---|---|---|---|
| Q1 (Jan–Mar) | $98,103 | **-$479** | **-0.5%** |
| Q2 (Apr–Jun) | $142,063 | $4,745 | 3.3% |
| Q3 (Jul–Sep) | $200,642 | $6,877 | 3.4% |
| Q4 (Oct–Dec) | $301,192 | $7,308 | 2.4% |

**Key Findings:**

- **Q1 runs at a net loss** (-$479) — the business begins every year unprofitably, driven by January's negative margin and February's low volume.
- **Q4 dominates in sales ($301,192 — 40.6% of annual revenue)** but ranks below Q2 and Q3 in profit margin (2.4% vs 3.3%–3.4%). Heavy November/December promotional activity inflates revenue while compressing margins.
- **Q3 is the most profitable quarter per dollar of revenue (3.4%)** — the September spike with relatively less discounting makes Q3 the highest-quality revenue quarter.
- **The business front-loads losses (Q1) and back-loads volume (Q4)** — a cash flow and profitability profile that requires careful working capital management.

---

### 9. Product-Level Intelligence

#### Top 10 Products by Sales:

| Product | Sales | Profit |
|---|---|---|
| HON 5400 Series Task Chairs | $21,871 | — |
| Riverside Palais Royal Lawyers Bookcase | $15,611 | — |
| Bretford Rectangular Conference Table Tops | $12,995 | — |
| Global Troy Executive Leather Low-Back Tilter | $12,975 | — |
| SAFCO Arco Folding Chair | $11,573 | $1,179 |

#### Top Profit-Generating Products:

| Product | Profit |
|---|---|
| Hon Deluxe Fabric Upholstered Stacking Chairs | $1,927 |
| Global Deluxe High-Back Manager's Chair | $1,559 |
| Hon Pagoda Stacking Chairs | $1,541 |
| Hon 4070 Series Pagoda Armless Stacking Chairs | $1,389 |
| Office Star Professional Matrix Back Chair | $1,306 |

#### Worst Loss-Making Products:

| Product | Sales | Loss |
|---|---|---|
| Chromcraft Bull-Nose Wood Oval Conference Table | $9,918 | -$2,876 |
| Bush Advantage Collection Racetrack Conference Table | $9,545 | -$1,934 |
| Balt Solid Wood Round Tables | $6,519 | -$1,201 |
| BoxOffice By Design Rectangular Multi-Purpose Table | $1,706 | -$1,148 |
| Riverside Furniture Oval Coffee Table | $4,446 | -$1,147 |

**Key Findings:**

- **123 of 375 products (32.8%) are loss-making** — nearly one in three products sold actively destroys margin. This is not a minor SKU rationalization opportunity — it is a structural product portfolio crisis.
- **Conference and meeting room tables are the most loss-intensive products** — Chromcraft (-$2,876), Bush Conference Table (-$1,934), and multiple other table variants dominate the loss leaderboard. This directly explains the Tables sub-category's -8.6% overall margin.
- **All top profit products are Chairs** — the Hon, Global, and Office Star chair lines are the reliable profit workhorses. The product portfolio's health is entirely dependent on chairs performing well.
- **The gap between best and worst product profitability is massive** — from +$1,927 (Hon Stacking Chair) to -$2,876 (Chromcraft Conference Table). A product rationalization exercise focused on the bottom 30 products could meaningfully reshape the company's profitability profile.

---

### 10. Profit Margin Health

| Metric | Value |
|---|---|
| **Overall Profit Margin** | 2.49% |
| **Average Order Profit Margin** | 3.89% |
| **Median Order Profit Margin** | 11.1% |
| **Loss-Making Orders** | 714 of 2,121 (33.7%) |
| **Total Profit from Positive Orders** | +$79,387 |
| **Total Loss from Negative Orders** | -$60,936 |
| **Net Profit** | $18,451 |

**Key Findings:**

- **The median order margin of 11.1% vs. the overall margin of 2.49% reveals something critical:** the majority of individual orders are actually quite profitable — the business is being dragged down by a minority of deeply loss-making orders that offset healthy ones.
- **33.7% of all orders lose money** — more than one in three transactions is unprofitable. These 714 loss-making orders generate -$60,936 in total losses, nearly wiping out the +$79,387 generated by the profitable 66.3%.
- **The business is net positive only because its profitable orders slightly outweigh its loss-making ones** — a precarious equilibrium that 2017's profit collapse is beginning to undermine.
- **Eliminating even half the loss-making orders** (through pricing correction, minimum order thresholds, or product rationalization) could more than double total profit without adding a single new customer.

---

## Strategic Recommendations

### 1. 🚨 Immediate Action: Tables Pricing & Cost Audit
Tables lost -$17,725 across 4 years with losses accelerating to -$8,141 in 2017 alone — a +176% worsening in a single year. This requires an emergency review: Are tables being systematically under-priced? Are shipping and handling costs disproportionate? Are certain Table SKUs (conference tables especially) being offered below cost? Until this is resolved, every Tables sale harms the business.

### 2. ✂️ Rationalize the 123 Loss-Making Products
Nearly one-third of the product catalogue generates negative profit. Conduct a structured SKU rationalization: retire or reprice the bottom 50 products by profit contribution. The Chromcraft and Bush conference table lines alone account for -$4,810 in losses — removing these two products would deliver more profit impact than growing sales by ~15%.

### 3. 🌱 Invest Heavily in Furnishings
Furnishings delivers a 14.2% profit margin — nearly 6x the overall business margin and the highest of any sub-category. Despite this exceptional return, it represents only 12.4% of total sales. A targeted campaign to grow Furnishings sales could transform the overall profitability profile without requiring any operational change.

### 4. 🗺️ Exit or Restructure the Illinois Market
Illinois operates at a -32.1% profit margin — the worst of any state. For every $1 sold in Illinois, 32 cents is lost. Either a market-specific pricing correction or a strategic exit is warranted. At minimum, no new customer acquisition spend should be directed toward Illinois until the margin structure is fixed.

### 5. ⚠️ Fix Texas, Pennsylvania, and Ohio
Three of the top 5 revenue states are loss-making (Texas: -$10,436, Pennsylvania: -$7,197, Ohio: -$4,206). These are large markets where significant sales volume is being converted to losses. Geographic pricing adjustments, reduced discounting, and product mix management are needed urgently in these states.

### 6. 📈 Scale the Corporate Segment
Corporate customers deliver a 3.31% margin vs. Consumer's 1.79% — nearly double the efficiency. The Corporate segment requires dedicated sales resources, account management, and tailored product bundles. Growing Corporate's revenue share from 30.9% to 40% could add an estimated $3–4K in annual profit without growing total sales.

### 7. 📅 Defend Q4 Margins — Stop the October Discount Spiral
October generates -$3,028 in profit despite $58K in sales — a pre-holiday discounting problem that erodes margins before the peak season even begins. Implement a pricing floor for October to protect margins going into the highest-volume two months of the year (November and December).

### 8. 🏆 Build on Washington and Virginia — Replicate Their Success
Washington (15.0% margin) and Virginia (20.6% margin) are the two highest-margin major states. Understand what makes these markets work — product mix, customer type, shipping efficiency, or competitive landscape — and apply those learnings to underperforming high-revenue states like Texas and Illinois.

---

## Live Dashboard

> 🔗 Interact with the full Excel dashboard **[HERE](#)** *(insert your file or dashboard link)*

---

## Connect With Me

Let's connect, collaborate, or talk data!

- 💼 [LinkedIn](https://www.linkedin.com/in/oluwatofunmi-isholadaniel/)
- 💻 [GitHub](https://github.com/TofunmiTech01)

---

*Built with Microsoft Excel · Analyzed with precision · Designed for decisions.*


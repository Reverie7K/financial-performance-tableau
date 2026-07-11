# Business Performance Analysis
### A Strategic Review of Global Sales, Profitability, and Operational Drivers

**Prepared by:** Kennith Vazhappilly Babu
**Degree Programme:** BSc Business and Management, University of London
**Tool:** Tableau (5-dashboard interactive story)

> 📊 **Note:** This report is designed to be read alongside the accompanying Tableau story. Small preview thumbnails of each dashboard are included below for reference — open the `.twbx` workbook in Tableau (or Tableau Public/Reader) for the full interactive experience.

---

## Table of Contents

1. [Executive Recommendations](#executive-recommendations)
2. [Introduction](#introduction)
3. [Dashboard 1: Overall Business Performance](#dashboard-1-overall-business-performance)
4. [Dashboard 2: Customer Analytics](#dashboard-2-customer-analytics)
5. [Dashboard 3: Sales & Profitability Drivers](#dashboard-3-sales--profitability-drivers)
6. [Dashboard 4: Marketing & Promotional Efficiency](#dashboard-4-marketing--promotional-efficiency)
7. [Dashboard 5: Strategic Risks & Opportunities](#dashboard-5-strategic-risks--opportunities)

---

## Executive Recommendations

From the data exploration exercise conducted using Tableau, the following recommendations are made to the executive team:

1. **Enforce a strict discount ceiling.** The data shows discounts above 20% cause profitability to plummet. Management must cap discounts, particularly in the **Corporate segment** and the **Furniture (Tables)** category.
2. **Overhaul fulfilment pricing.** The current approach to expedited shipping is eroding product margins. The company should either raise the minimum order threshold for free expedited shipping, or standardise fulfilment on the significantly more economical **Standard Class** option.
3. **Sunset or reprice "bleeding" categories.** The **Tables** sub-category in the **South region** is draining the overall profit pool. If supply-chain pricing cannot be renegotiated, management should consider withdrawing it from that region entirely.
4. **Balance marketing spend with seasonal demand.** Promotional spending should be skewed decisively toward **November and December**, and messaging should shift from deep discounts toward value-adds — such as the reliability of standard shipping — to protect the bottom line.

---

## Introduction

In today's retail landscape, it is imperative for companies to keep abreast of not only revenue but also expenses in order to remain competitive. The primary aim of this report is to examine the company's raw sales data and distil it into valuable business insights. Using an interactive five-part Tableau story, this analysis goes beyond simple reporting to identify the underlying factors influencing the company's financial performance. The findings that follow are intended to give senior executives the evidence needed to stem shrinking margins and capitalise on high-value market segments.

---

## Dashboard 1: Overall Business Performance

<img src="assets/dashboard1_overall_performance.png" alt="Dashboard 1: Overall Business Performance" width="700">

This dashboard establishes a foundation for understanding overall business health, visualising the company's global sales footprint and how performance changes over time.

The KPI header at the top of the page shows **total sales of $12.63M** against a **total profit of $1.47M** — a net profit margin of **11.61%**. The global map illustrates a robust market presence in the **United States and Canada**.

However, the year-over-year dual-axis trend chart reveals a concerning gap: while sales volume is steadily increasing, the profit line frequently diverges from sales growth. This indicates it is becoming progressively more costly to grow the business — top-line growth is not effectively translating into profit.

The Category Performance chart makes this divergence even clearer. Filtering sales by sub-category and colouring bars by profit shows that **selling a large quantity of a product is not, by itself, a marker of success**. **Tables**, for example, sells in high volume but generates a **net loss** — actively dragging down overall company profitability.

---

## Dashboard 2: Customer Analytics

<img src="assets/dashboard2_customer_analytics.png" alt="Dashboard 2: Customer Analytics" width="700">

Identifying the buyer profile is a critical step in shaping sales strategy. This dashboard breaks down the customer base to identify where value is concentrated.

Segment analysis shows the **Consumer segment** is the largest single contributor to overall sales.

However, the **Top 10 Customers matrix** reveals a significant concentration risk: a very small share of the overall customer base drives a disproportionately large share of total sales. Colouring the matrix by profitability reveals that **two of the highest-grossing customers are, in fact, a net loss** to the business.

This is reinforced by the **Customer Value scatter plot**. While a large group of customers sit safely in the profitable region of the chart, there is a clear cluster of customers who are not breaking even — the business is effectively subsidising them. Management needs to determine whether continuing to absorb these losses is worthwhile, or whether these accounts need urgent renegotiation.

---

## Dashboard 3: Sales & Profitability Drivers

<img src="assets/dashboard3_sales_profitability_drivers.png" alt="Dashboard 3: Sales & Profitability Drivers" width="700">

To pinpoint exactly why certain products and customers are losing money, this dashboard examines unit economics — specifically, the effects of pricing and fulfilment costs.

The key takeaway comes from the **Discount Impact** chart: there is a strong negative correlation between discount level and profit margin, with the break-even point occurring at approximately a **20% discount rate**. Any discount above this threshold guarantees negative unit economics.

The **Profitability Matrix** localises exactly where this is happening. By cross-referencing region against sub-category, rather than relying on guesswork, the matrix clearly identifies the **Tables category in the South region** as the primary source of the company's margin problem.

Finally, the **Shipping Economics** view shows that expedited shipping options (such as Same Day) have a markedly negative effect on profit margins compared to Standard shipping — indicating the additional costs of expedited fulfilment are not being passed on to the customer.

---

## Dashboard 4: Marketing & Promotional Efficiency

<img src="assets/dashboard4_marketing_promotional_efficiency.png" alt="Dashboard 4: Marketing & Promotional Efficiency" width="700">

As direct advertising spend data is not available, this dashboard instead evaluates promotional effectiveness indirectly — through seasonality, discounting patterns, and shipping preferences.

The **Seasonality Trend** chart shows purchasing patterns vary substantially through the year, with sharp demand spikes in **November and December** and pronounced dips in **February and July**. The marketing calendar should reflect this cycle, with ad spend maximised just ahead of these natural demand peaks.

The **box-and-whisker plot** of discount distribution points to a lack of pricing discipline within the sales teams: the wide spread of discount percentages — particularly in the **Corporate segment** — suggests discounts are being applied opportunistically to close sales, rather than deployed as a deliberate marketing lever.

Adding to this, the **Delivery Efficiency** stacked bar chart shows that most markets already favour **Standard Class** shipping. Marketing teams can lean into this by actively promoting the cheaper, already-preferred shipping method — closing sales without sacrificing margin.

---

## Dashboard 5: Strategic Risks & Opportunities

<img src="assets/dashboard5_strategic_risks_opportunities.png" alt="Dashboard 5: Strategic Risks & Opportunities" width="700">

The final dashboard brings these insights together into a single strategic view, spotlighting immediate risks alongside the best opportunities for future growth.

The **Opportunity Quadrant** plots every sub-category against company averages for sales and profit. Resources should be directed toward the **"Star" quadrant** (top-right) — sub-categories such as **Copiers**, which are consistently above average on both dimensions.

Conversely, the filtered **"Bleeding Sub-Categories"** chart isolates the specific product lines currently losing money.

The **Profit Recovery Waterfall** chart makes the cost of these inefficiencies concrete: it shows the cumulative profit built up by strong categories, followed by the sharp declines contributed by the bleeding ones. The implication is straightforward — removing the negative steps on the right-hand side of the chart would return the company's bottom line to its former peak.

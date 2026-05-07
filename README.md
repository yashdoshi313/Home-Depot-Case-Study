# Weiser × Home Depot Canada: eCommerce Performance Review

A portfolio-style eCommerce analytics case study built using a fictional Home Depot Canada specimen dataset. The goal was to analyze supplier performance, identify digital shelf gaps, and translate SKU-level data into prioritized Product Information Page improvement actions.

> **Note:** This project is based on fictional data created for a case study exercise. It is not based on actual Home Depot Canada performance data.

---

## Project Snapshot

| Area | Details |
|---|---|
| **Business focus** | eCommerce performance, digital shelf optimization, Product Information Page analysis |
| **Brand analyzed** | Weiser, door hardware category |
| **Dataset grain** | Monthly SKU-level performance data |
| **Core channels** | Online sales, online visits, online orders, in-store sales |
| **Primary output** | Vendor-facing performance review and 12-month digital shelf roadmap |
| **Tools used** | Excel, PowerPoint, eCommerce KPI analysis, data storytelling |

---

## Business Question

How can a supplier improve eCommerce performance on HomeDepot.ca by using SKU-level sales, traffic, conversion, rating, and Product Information Page signals?

The analysis focused on one central idea:

> The Product Information Page is not only a product detail page. It is the decision-making shelf where online and in-store purchase intent is created.

---

## Case Study Preview

The project was delivered as a vendor-facing eCommerce performance review. The visuals below show the main analytical storyline: current performance, funnel leakage, monetization efficiency, and customer trust signals.

### Performance Overview

![Performance Overview showing total online sales, total orders, average conversion rate, blended revenue per visit, online sales TY vs LY, and top SKU table](visuals/performance-overview.png)

**Key message:** Revenue is concentrated across a few key SKUs, but performance varies sharply in conversion and monetization efficiency.

---

### Funnel Analysis

![Funnel Analysis showing online visits by SKU, conversion rate by SKU, and diagnosis table for high-traffic low-conversion SKUs](visuals/funnel-analysis.png)

**Key message:** SKU 15 and SKU 17 attract strong traffic but convert below 0.65%, indicating a digital shelf problem rather than a demand problem.

---

### Monetization Analysis

![Monetization analysis showing blended revenue per visit, store dependency ratio, and AOV online vs store premium](visuals/monetization-analysis.png)

**Key message:** SKU 20 generates the highest blended revenue per visit, while SKU 12 leads on online AOV. High AOV alone does not guarantee visit efficiency.

---

### Customer Signal Analysis

![Customer signal analysis showing monthly average rating, monthly conversion rate, and SKU trust tier table](visuals/customer-signal-analysis.png)

**Key message:** Low-rated SKUs create trust friction, while stronger rating periods align with better conversion performance.

---

## Work Expected vs Work Delivered

| Case Study Requirement | Work Delivered |
|---|---|
| Choose a brand sold on HomeDepot.ca | Selected **Weiser** as the brand for analysis within the door hardware category |
| Analyze the provided dataset | Built a SKU and month-level KPI workbook covering online sales, orders, visits, ratings, conversion, AOV, and YoY growth |
| Highlight online performance from the supplier perspective | Created a vendor-facing performance story showing where revenue was concentrated and where conversion was leaking |
| Calculate key KPIs | Calculated conversion rate, AOV, YoY growth, online product visits, orders, ratings, and additional business KPIs |
| Add extra KPIs that create value | Added Blended Revenue per Visit, Store Dependency Ratio, Channel AOV Premium, retail price change, and growth decomposition |
| Review Product Information Pages | Audited live-style PIP examples to identify title, image, specification, description, and Q&A gaps |
| Provide recommendations | Prioritized recommendations across content optimization, search and findability, and digital shelf enhancements |
| Build a clear presentation | Delivered a structured case study pitch deck with charts, tables, key messages, and executive-ready recommendations |
| Outline a 12-month plan | Created a three-phase roadmap: Diagnose & Fix, Build & Enrich, Scale & Optimize |

---

## Dataset Overview

The dataset contained monthly performance records across multiple SKUs and included:

- SKU and category details
- Retail price this year and last year
- In-store sales and units
- Online sales and units
- Online product visits
- Online orders
- Average product rating
- Year-over-year performance fields

The raw dataset was enhanced with a calculation layer to support deeper commercial analysis.

---

## New KPI Calculations Added

The case study went beyond standard reporting by adding metrics that connect traffic, conversion, omnichannel behaviour, and monetization efficiency.

| KPI | Formula | Business Purpose |
|---|---|---|
| **Retail Price Change** | `Retail Price TY - Retail Price LY` | Identifies product-level price movement |
| **Online Sales Growth %** | `(Online Sales TY - Online Sales LY) / Online Sales LY` | Measures YoY online revenue growth |
| **Online Orders Growth %** | `(Online Orders TY - Online Orders LY) / Online Orders LY` | Separates order volume growth from revenue growth |
| **Online Product Visit Growth %** | `(Visits TY - Visits LY) / Visits LY` | Measures demand and traffic movement |
| **Conversion Rate TY** | `Online Orders TY / Online Product Visits TY` | Shows how efficiently traffic becomes orders |
| **Conversion Rate Growth %** | `(Conversion Rate TY - Conversion Rate LY) / Conversion Rate LY` | Shows whether the funnel improved YoY |
| **Online AOV** | `Online Sales / Online Orders` | Measures online order value efficiency |
| **In-Store AOV** | `In-Store Sales / In-Store Units` | Benchmarks store transaction value |
| **Channel AOV Premium** | `Online AOV TY - In-Store AOV TY` | Identifies SKUs where online buyers spend more |
| **Blended Revenue per Visit** | `(Online Sales + In-Store Sales) / Online Product Visits` | Connects online traffic to total commercial value |
| **Store Dependency Ratio** | `In-Store Sales / (In-Store Sales + Online Sales)` | Shows how much revenue still closes in-store after digital discovery |
| **Incremental Order Opportunity** | `Visits × (Target Conversion Rate - Current Conversion Rate)` | Estimates potential order lift from PIP improvements |

---

## Key Findings

### 1. Revenue was growing, but not evenly

The portfolio generated approximately **$5.46M in online sales**, up **10.3% YoY**, with **15,994 online orders**, up roughly **3.4% YoY**.

However, revenue growth outpaced order growth. This suggested that Average Order Value was carrying a meaningful share of the increase rather than pure order volume.

---

### 2. High-traffic SKUs were not converting efficiently

SKU 15 and SKU 17 attracted more than **230K annual visits combined**, but both converted below **0.65%**.

This suggested a funnel issue rather than a demand issue. Customers were reaching the product pages, but the pages were not doing enough to convert interest into orders.

---

### 3. Blended Revenue per Visit exposed monetization gaps

Blended Revenue per Visit varied sharply across the portfolio, ranging from roughly **$2.51 to $24.39**.

This showed that traffic volume alone was not enough. Some SKUs created far more revenue per visit because of stronger AOV, better conversion, or stronger in-store pull-through.

---

### 4. Online research influenced in-store purchase behaviour

A large share of revenue closed in-store, but the online Product Information Page still played a major role in customer decision-making.

This made the PIP the key bridge between online discovery and in-store purchase intent.

---

### 5. Ratings and Q&A gaps signalled trust friction

Several SKUs had low average ratings, including SKUs below **2.5 stars**. The PIP audit also showed unanswered customer questions, limited product images, confusing product titles, and specification gaps.

These are trust leaks. Each missing answer or unclear attribute increases customer hesitation.

---

## Digital Shelf Audit Themes

The Product Information Page review focused on how content supports or blocks the customer journey.

### Issues identified

- Product titles were long or confusing
- Some specifications appeared unclear or misleading
- Product descriptions were feature-led instead of benefit-led
- Some products had only one image
- Q&A sections contained unanswered customer concerns
- Important search terms were missing from titles or attributes
- Product pages did not fully replicate the confidence a shopper gets from seeing packaging in-store

---

## Recommendations

### High Priority: Content Optimization

- Correct specification and attribute errors across priority SKUs
- Rewrite product titles using a consistent structure: `Brand + Line + Function + Finish`
- Lead descriptions with customer benefits before technical features
- Convert repeated Q&A concerns into visible FAQ-style product copy

### Medium Priority: Search and Findability

- Add customer-searchable terms such as keyless entry, smart lock, finish, function, and use case
- Complete filter-driving attributes such as connectivity, smart technology, voice assistant, and BHMA grade
- Add descriptive image alt text
- Audit category taxonomy so products appear in the right filtered browsing paths

### High Priority: Digital Shelf Enhancements

- Expand each priority SKU to at least five product images
- Add lifestyle, installation, finish close-up, scale reference, and packaging images
- Add short installation videos for complex or high-consideration products
- Add a SmartKey technology module to explain the product differentiator
- Create a comparison guide to help customers choose between product lines

---

## 12-Month Roadmap

| Phase | Timeline | Focus | Output |
|---|---:|---|---|
| **Phase 1: Diagnose & Fix** | Months 1-3 | Attribute audit, title cleanup, urgent spec corrections | Cleaned priority PIPs and fixed trust blockers |
| **Phase 2: Build & Enrich** | Months 4-8 | Description rewrites, image expansion, FAQ copy, installation assets | Richer product pages that answer buyer questions |
| **Phase 3: Scale & Optimize** | Months 9-12 | Search keyword optimization, performance tracking, scale to broader SKU set | Repeatable digital shelf playbook |

### KPIs to track monthly

- Conversion Rate % by SKU
- Online Orders Growth %
- Online Product Visits
- Blended Revenue per Visit
- Store Dependency Ratio
- Q&A Response Rate
- Image Count per PIP
- Average Product Rating

---

## Skills Demonstrated

- eCommerce KPI analysis
- SKU-level performance analysis
- Product Information Page audit
- Funnel analysis
- YoY growth analysis
- AOV and revenue decomposition
- Omnichannel customer journey thinking
- Excel-based KPI engineering
- Executive storytelling
- Vendor-facing recommendation building
- 12-month roadmap planning

---

## Suggested Repository Structure

```text
.
├── README.md
├── data/
│   └── sample_dataset_calculations.xlsx
├── presentation/
│   └── case_study_pitch_deck.pptx
├── visuals/
│   ├── performance-overview.png
│   ├── funnel-analysis.png
│   ├── monetization-analysis.png
│   └── customer-signal-analysis.png
└── docs/
    └── case_study_guidelines.pdf
```

---

## How to Read This Project

For a quick review:

1. Start with the **Case Study Preview** to understand the visual storyline.
2. Review the **Key Findings** to understand the business interpretation.
3. Open the **Excel calculation workbook** to see the KPI logic.
4. Open the **pitch deck** to see how the analysis was translated into a vendor-facing recommendation.
5. Review the **12-month roadmap** to understand how insights were converted into action.

---

## Future Enhancements

If this were expanded into a full analytics portfolio project, the next version could include:

- A Power BI dashboard for interactive SKU filtering
- A Python or SQL pipeline to automate KPI generation
- A weighted KPI summary table for portfolio-level reporting
- Before and after PIP mockups
- Search keyword mapping by product type
- A prioritization score combining visits, conversion gap, rating risk, and revenue potential

---

## Disclaimer

This is an independent portfolio case study created for learning and demonstration purposes. The dataset is fictional and does not represent actual Home Depot Canada, Weiser, or supplier performance. Brand names are used only to provide realistic business context for the analysis.

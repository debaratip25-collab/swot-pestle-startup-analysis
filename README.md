# SWOT & PESTLE Analysis for a Startup Idea

Strategic feasibility, risk, and growth-potential evaluation of a startup idea using SWOT and PESTLE frameworks — combining a consulting-style case-study report with a 100-company benchmarking dataset and an interactive Excel dashboard.

## Objective

To evaluate the feasibility, risks, opportunities, and growth potential of a startup idea before launch, using two of the most widely used strategic frameworks in business analysis: **SWOT** (Strengths, Weaknesses, Opportunities, Threats) and **PESTLE** (Political, Economic, Social, Technological, Legal, Environmental).

## Startup Idea: ChargeNova Mobility

The core case study evaluates **ChargeNova Mobility**, an illustrative startup building a network of EV charging and battery-swap stations across **Tier-2 Indian cities** — a market segment under-served by national charging networks today. The idea is benchmarked against a wider 100-startup dataset spanning 17 industries, so the same evaluation logic can be tested at scale, not just for a single company.

> This is an illustrative, educational case study built for portfolio purposes. No real company, investment, or regulatory advice is implied.

## SWOT Framework

| Quadrant | Summary |
|---|---|
| **Strengths** | First-mover footprint in 12 Tier-2 cities, smart-routing app, asset-light hub model, DISCOM tariff tie-ups, experienced founding team |
| **Weaknesses** | High capital intensity per site, limited brand recognition, grid-quality dependence, revenue concentration in low-margin segments |
| **Opportunities** | PM E-DRIVE & state EV policy support, fast 2W/3W EV adoption, B2B fleet contracts, battery-swap revenue, ESG-linked financing |
| **Threats** | Aggressive national competitors, policy/subsidy uncertainty, slower EV penetration, fast-evolving charging standards |

Full detail, with a color-coded 2×2 matrix, is in [`reports/SWOT_PESTLE_Case_Study_Report.docx`](reports/SWOT_PESTLE_Case_Study_Report.docx).

## PESTLE Framework

| Factor | Strategic Implication (summary) |
|---|---|
| **Political** | PM E-DRIVE & state EV policies lower setup cost; scheme renewal cycles add medium-term risk |
| **Economic** | Falling EV total-cost-of-ownership drives adoption; a slowdown could delay fleet capex |
| **Social** | Younger, eco-conscious consumers adopt faster, but "range anxiety" persists |
| **Technological** | Falling battery costs and faster charging expand the market, but require continuous capex |
| **Legal** | Evolving safety/grid-interconnection standards raise compliance overhead |
| **Environmental** | Strong alignment with decarbonisation goals supports long-term demand |

## Industry Analysis (100-Startup Dataset)

A synthetic benchmarking dataset of **100 startups across 17 industries** (EdTech, FinTech, HealthTech, AgriTech, CleanTech/EV, E-commerce, FoodTech, Logistics & Supply Chain, SaaS, AI/ML, Cybersecurity, PropTech, TravelTech, Gaming & Esports, InsurTech, LegalTech, HR Tech) was built across 20 analytical parameters, including 6 PESTLE impact scores, Competitive Intensity, Risk Level, and Growth Potential.

- **Most represented industries:** EdTech (8) and Logistics & Supply Chain (8), followed by FoodTech (7)
- **Average market size estimate:** $325.9M
- **Average Growth Potential Score:** 5.6 / 10
- **Highest-average PESTLE factors:** Technological (6.67/10) and Social (5.59/10)
- **Lowest-average PESTLE factor:** Environmental (3.94/10)

## Risk Assessment

| Risk Level | Count | Share |
|---|---|---|
| Low | 19 | 19% |
| Medium | 56 | 56% |
| High | 25 | 25% |

High-risk startups are concentrated in sectors with elevated competitive intensity and legal/regulatory exposure (FinTech, HealthTech, InsurTech).

## Strategic Recommendations

1. Prioritise two/three-wheeler fast-charging and battery-swap formats, where demand is growing fastest and competition is lowest.
2. Lock in multi-year power-supply agreements with regional DISCOMs to de-risk unit economics.
3. Pursue anchor B2B contracts with e-commerce/delivery fleets for predictable utilisation.
4. Apply for available capital-subsidy schemes before committing further owned capital.
5. Build a secondary SaaS revenue line (fleet energy/charge scheduling) to improve margin mix.
6. Use a data-driven site-selection model rather than opportunistic real-estate availability.

## Dashboard Features

The Excel dashboard (`dashboard/Startup_SWOT_PESTLE_Dashboard.xlsx`) includes:

- **6 KPI cards** — Total Startups, Avg. Growth Potential, Avg. Investment Attractiveness, High-Risk Count, Avg. Market Size, Top Industry
- **Startup Count by Industry** (bar chart)
- **Risk Level Distribution** (pie chart)
- **Average PESTLE Impact Score** (radar chart)
- **Top 10 Startups by Investment Attractiveness** (bar chart)
- **Strategic Map: Growth Potential vs. Competitive Intensity** (scatter chart, all 100 startups)
- **Strategic Insights & Recommendations** panel
- Fully formula-driven `Data`, `Scorecard`, and `Calc` sheets — the workbook recalculates automatically if source data changes

`![Dashboard Screenshot](screenshots/dashboard_overview.png)`

## Key Insights

- Technological and Economic factors carry the highest average PESTLE impact, favouring tech-enabled, cost-efficient business models.
- 25% of the benchmarked startups fall into the High-Risk band, concentrated in regulation-heavy sectors.
- The clearest growth whitespace sits where high Growth Potential meets low-to-moderate Competitive Intensity.
- The top 10 startups by Investment Attractiveness skew toward Cybersecurity, SaaS, HealthTech, and FinTech.
- Environmental impact scores are the lowest on average — a forward-looking differentiation opportunity for new entrants.

## Repository Structure

```
swot-pestle-startup-analysis/
|-- README.md
|-- data/
|   `-- startup_dataset_100_records.csv
|-- dashboard/
|   `-- Startup_SWOT_PESTLE_Dashboard.xlsx
|-- reports/
|   |-- SWOT_PESTLE_Case_Study_Report.docx
|-- screenshots/
|   |-- dashboard_overview_1.png
|   |-- dashboard_overview_2.png
|   `-- dashboard_overview_3.png

```

## Tech Stack

- **Python** — synthetic dataset generation (100 records, 17 industries, 20 parameters)
- **Excel / openpyxl** — formula-driven workbook, conditional formatting, charts, KPI dashboard
- **Word (docx)** — consulting-styled case-study report and execution guide

## Conclusion

This project demonstrates a complete strategic-analysis workflow — from framework selection and qualitative case-study development through to a quantitative, dashboard-ready benchmarking dataset — in the same structured way Business Analysts, strategy consultants, and venture investors evaluate startup ideas before committing time or capital.


## Author

Debarati Pal

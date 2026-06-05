# FastShip Logistics — Excel Performance Analysis

**Excel · Power Pivot · DAX · Interactive Dashboard**

A logistics performance analysis built entirely in Microsoft Excel using Power Pivot. Investigates 2,000 shipment records from 2023 to identify delivery failures, carrier inefficiencies, and cost savings opportunities — then delivers an executive-ready dashboard and recommendation report.

Built as part of the **Data with Danny** cohort curriculum.

---

## The Business Scenario

FastShip Logistics operates 10 warehouses across the United States and partners with 7 carriers — UPS, FedEx, DHL, USPS, Amazon Logistics, OnTrac, and LaserShip.

Operations Manager Sarah Chen has flagged inconsistent delivery performance and rising costs. The executive team needs answers on four fronts: rising shipping costs, delivery delays, lost packages, and operational efficiency.

Your job: turn 2,000 raw shipment records into a dashboard leadership can act on.

---

## What This Project Covers

### Data Model
- Power Pivot data model with imported shipment data
- Calendar dimension table for time-based analysis
- Relationships between fact and dimension tables

### DAX Measures (15+)
- Total shipping cost and cost per shipment
- On-time delivery rate and problem rate
- Cost per mile by carrier
- Average transit time by warehouse and carrier
- Lost and returned shipment counts

### Dashboard (2 pages)
- **Executive Summary** — headline KPIs, monthly trends, overall health
- **Carrier Performance** — side-by-side cost and delivery comparison
- **Warehouse Analysis** — problem rate and on-time rate by location
- **Problem Tracking** — delays, losses, and returns broken down by carrier

### Insights Report
- Answers to all 19 business questions from the project brief
- 3 actionable recommendations with projected financial impact

---

## Key Findings

| Metric | Value | Benchmark |
|--------|-------|-----------|
| On-Time Delivery | 82.4% | ❌ Below 85% |
| Problem Rate | 13.8% | ❌ Above 10% |
| Total Shipping Cost | $401,912 | — |
| Average Transit Time | 4.18 days | — |
| Worst Carrier | Amazon Logistics (17.9% problem rate) | — |
| Worst Warehouse | San Francisco (17.2% problem rate) | — |
| Potential Annual Savings | $31,200 | — |

---

## Top 3 Recommendations

**1. Reduce Amazon Logistics volume by 50%**
Shift to UPS and FedEx for affected routes.
Impact: Problem rate drops from 13.8% → 11.5%. Annual savings: $2,700.

**2. Route all shipments under 500 miles to USPS**
USPS costs $0.14/mile vs the current $0.16/mile average across 600 affected shipments.
Impact: Annual savings of $24,000. ROI: 380%.

**3. Replicate the NYC warehouse playbook at San Francisco**
NYC operates at 88.8% on-time and 8.2% problem rate. Study and apply their processes to SF.
Impact: On-time delivery improves to 86%, problem rate drops to 11%, 112 fewer problem shipments per year.

**Total investment: $14,500 → Annual savings: $31,200 → 3-year savings: $79,100**

---

## Dataset

| Field | Description |
|-------|-------------|
| Shipment_ID | Unique identifier (SH10000–SH12000) |
| Origin_Warehouse | One of 10 US warehouse locations |
| Destination | Destination city |
| Carrier | Shipping carrier used |
| Shipment_Date | Date package was shipped |
| Delivery_Date | Date delivered (blank if not delivered) |
| Weight_kg | Package weight in kilograms |
| Cost | Shipping cost in USD |
| Status | Delivered / Delayed / In Transit / Lost / Returned |
| Distance_miles | Distance traveled |
| Transit_Days | Days in transit |

2,000 rows. Simulated data for educational purposes.

---

## Tools Used

- Microsoft Excel
- Power Pivot (Data Model)
- DAX (calculated measures and columns)
- Power Query (data cleaning and calendar table)
- Pivot Tables and Pivot Charts
- Slicers for interactivity

---

## Repository Structure

```
fastship-logistics-excel-analysis/
│
├── Dataset/
│   └── Shipment_Data.xlsx
│
├── Analysis/
│   └── FastShip_Analysis.xlsx          # Power Pivot model + dashboard
│
├── Report/
│   └── FastShip_Executive_Summary.docx # Executive summary with recommendations
│
└── README.md
```

---

## Skills Demonstrated

- Power Pivot data modelling from raw CSV/Excel data
- DAX measure writing (SUM, AVERAGE, COUNT, CALCULATE, FILTER, RELATED)
- Calendar table creation for time intelligence
- Multi-page interactive dashboard design
- Business insight generation from operational data
- Executive communication of analytical findings

---

## Part of the DwD Curriculum

This project is one of two Excel capstone projects in the **Data with Danny** cohort program.

The program covers Excel, SQL, Python, Power BI, Statistics, Figma, PowerPoint, and AI integration across a structured 4-month curriculum.

**Cohort 9 starts June 25, 2026** → [nestuge.com/mzlik606d](https://nestuge.com/mzlik606d)

---

*Built by [Your Name] · Data with Danny Cohort [X] · [Year]*

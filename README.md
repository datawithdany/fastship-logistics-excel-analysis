# FastShip Logistics — Excel Performance Analysis

**Excel · Power Pivot · DAX · Interactive Dashboard**

A Data with Danny cohort project. You are a Data Analyst at FastShip Logistics. You have 2,000 shipment records from 2023 and one job — figure out what is broken and how to fix it.

---

## The Scenario

FastShip Logistics operates 10 warehouses across the United States and partners with 7 carriers: UPS, FedEx, DHL, USPS, Amazon Logistics, OnTrac, and LaserShip.

Operations Manager **Sarah Chen** has flagged inconsistent delivery performance and rising costs. The executive team needs answers on four fronts:

- Are we spending too much on certain routes or carriers?
- Which carriers and warehouses are causing delays?
- Why are packages getting lost or returned?
- Can we optimise our carrier partnerships?

You have been given `Shipment_Data.xlsx` containing 2,000 shipment records. Your job is to build a Power Pivot model, write DAX measures, and deliver an interactive dashboard that the operations team can use to make decisions.

---

## Your Deliverables

### 1. Power Pivot Data Model
- Import the shipment data into Power Pivot
- Build a Calendar table for time-based analysis
- Create relationships between tables

### 2. DAX Measures (10–15)
- Total cost, average cost per shipment
- On-time delivery rate
- Problem rate (delayed + lost + returned)
- Cost per mile by carrier
- Average transit time by warehouse and carrier

### 3. Interactive Dashboard (1–2 pages)
- **Executive Summary** — headline KPIs and monthly trends
- **Carrier Performance** — cost and delivery comparison across all carriers
- **Warehouse Analysis** — problem rate and on-time rate by location
- **Problem Tracking** — delays, losses, and returns broken down

### 4. Insights Report
Answer all 19 business questions from the project brief and provide at least 3 actionable recommendations with projected financial impact.

---

## The 19 Business Questions

**Cost Analysis**
1. What is the total shipping cost for 2023?
2. What is the average cost per shipment?
3. Which carrier is most expensive on average?
4. Which warehouse has the highest total shipping costs?
5. What is the cost per mile for each carrier?

**Delivery Performance**
6. What percentage of shipments were delivered on time?
7. Which carrier has the best delivery success rate?
8. Which carrier has the worst performance?
9. What is the average transit time across all shipments?
10. Which warehouse has the longest average transit times?

**Operational Insights**
11. What is the total shipped weight for the year?
12. What is the average package weight?
13. Which destination city receives the most shipments?
14. Which carrier handles the most volume?
15. Is there a relationship between distance and transit time?

**Problem Areas**
16. How many shipments were lost or returned?
17. What percentage of shipments have issues?
18. Which carrier has the most lost packages?
19. Which warehouse has the highest problem rate?

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

## Repository Structure

```
fastship-logistics-excel-analysis/
│
├── Dataset/
│   └── Shipment_Data.xlsx          ← Start here
│
├── Project Brief/
│   └── FastShip_Project_Brief.pdf  ← Full instructions
│
├── Analysis/
│   └── FastShip_Analysis.xlsx      ← Your completed workbook goes here
│
├── Report/
│   └── FastShip_Executive_Summary  ← Your insights report goes here
│
└── README.md
```

---

## Success Criteria

Your project is complete when you can say yes to all of these:

- [ ] Power Pivot data model is built and relationships are correct
- [ ] All required DAX measures are written and return accurate results
- [ ] All 19 business questions are answered with data
- [ ] Dashboard is interactive — slicers filter all visuals
- [ ] At least 3 recommendations with projected financial impact
- [ ] A non-technical stakeholder can read your insights report and take action

---

## How to Submit

1. Fork this repo or create your own public repo
2. Upload your completed Excel file and insights report
3. Update the README with your name, cohort number, and a screenshot of your dashboard
4. Share the link in the DwD community

**The goal is not just to complete the project. The goal is to build something you can show a recruiter or client.**

---

## Tools Required

- Microsoft Excel (2016 or later with Power Pivot enabled)
- Power Pivot add-in (free, built into Excel on Windows)

---

## Part of the DwD Curriculum

This is one of two Excel projects in the **Data with Danny** cohort program — a structured 4-month curriculum covering Excel, SQL, Python, Power BI, Statistics, and AI integration.

**Cohort 9 starts June 25, 2026** → [nestuge.com/mzlik606d](https://nestuge.com/mzlik606d)

---

*Data with Danny · Excel Project 2 · datawithdany@gmail.com*

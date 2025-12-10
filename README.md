# Real Estate Leads & Opportunities Pipeline – Power BI Dashboard 🏢📊

This repository contains a **Power BI dashboard** for monitoring the pipeline of **leads and leasing opportunities** in a real estate company.

The report focuses on:

- How many **opportunities** the commercial team generates
- In which **status/stage** each opportunity currently is
- How many **m²** (square meters) are involved per stage
- How many opportunities are generated **per shopping center / asset**

It is based on real internal data (anonymized) used to support commercial decisions.

---

## 🎯 Business Objective

The company needs a clear view of its **commercial funnel**:

- How many opportunities are in:
  - **Propuesta presentada**
  - **En negociación**
  - **Negociación acordada**
  - **Trámite**
  - **Ganada**
  - **Perdida**
  - **Aplazada**
  - **Interesado**
- How many **m²** are associated with each stage
- How many opportunities are created in each **shopping center / asset**
- Which segments perform better:
  - Premium / Medium / Standard
- Which **assets or areas** (shopping centers, logistic parks, offices, etc.) generate more volume

The dashboard answers these questions visually and in real time.

---

## 🗂️ Project Structure

```text
real-estate-leads-pipeline-powerbi/
│
├── report/
│   └── RealEstate-Leads-Pipeline.pbix   # Main Power BI report
│
├── images/
│   ├── overview-pipeline.png            # General pipeline summary
│   └── detalle-etapa.png                # Detailed stage view (table)
│
└── README.md



🔍 Key Metrics & Views
🧩 Pipeline by Stage

For each stage (Presentada, Negociación, Negociación acordada, Trámite, Ganada, Perdida, Aplazada, Interesado), the report shows:

Number of opportunities (#)

Total m² under that stage

Quick comparison between stages to understand bottlenecks

🏬 Opportunities by Shopping Center / Asset

Breakdown by asset:

How many opportunities were created in each shopping center or building

Total m² associated to each asset

Which assets have more opportunities in advanced stages (Trámite, Ganada)

🎯 Segment & Client Profile

Segmentation of opportunities by:

Segment: Premium / Medium / Standard

Class of use and product type:

Comercio, Oficinas, Logística, UStorage, etc.

This allows a better understanding of which market segments are more active.

📷 Dashboard Preview
Pipeline Overview	Stage Detail

	
🛠️ Tools & Techniques

Power BI Desktop

Data modelling between opportunities, assets, segments and stages

DAX measures for counting opportunities and summing m²

Slicers for:

Product (commerce, offices, logistics, storage…)

Asset / shopping center

Segment (Premium / Medium / Standard)

Stage and date ranges

Excel / CSV

Data exported from the internal CRM

Cleaning and transformation before importing into Power BI

🚀 How to Use This Project

Clone or download this repository.

Open report/RealEstate-Leads-Pipeline.pbix with Power BI Desktop.

Explore the different pages:

Commercialization view

Stage-specific views (Ganada, Trámite, Negociación, etc.)

Replace the underlying data with your own CRM export (keeping a similar column structure).

Refresh the report to obtain your own pipeline analytics.

🛠️ Tools & Techniques

Power BI Desktop

Data modelling between opportunities, assets, segments and stages

DAX measures for counting opportunities and summing m²

Slicers for:

Product (commerce, offices, logistics, storage…)

Asset / shopping center

Segment (Premium / Medium / Standard)

Stage and date ranges

Excel / CSV

Data exported from the internal CRM

Cleaning and transformation before importing into Power BI

🚀 How to Use This Project

Clone or download this repository.

Open report/RealEstate-Leads-Pipeline.pbix with Power BI Desktop.

Explore the different pages:

Commercialization view

Stage-specific views (Ganada, Trámite, Negociación, etc.)

Replace the underlying data with your own CRM export (keeping a similar column structure).

Refresh the report to obtain your own pipeline analytics.

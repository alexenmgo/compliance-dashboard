# Compliance & Risk Monitoring Dashboard
### Business Intelligence for Regulatory Compliance — Securities Broker

> **Role:** Data & Compliance Specialist · CCI Puesto de Bolsa  
> **Tools:** Looker Studio · Google Sheets · Python · AML Framework

---

## 📌 Overview

A comprehensive Business Intelligence solution built for the compliance department of a Dominican securities broker (Puesto de Bolsa). The dashboard enables continuous monitoring of client risk profiles, regulatory compliance status, and portfolio distribution — supporting internal control, audits, and regulatory submissions to oversight authorities.

> ⚠️ *Data has been anonymized and client information is not disclosed in compliance with regulatory and data privacy requirements.*

---

## 🖥️ Dashboard Preview

### High-Risk Client Monitoring
![Compliance Dashboard - High Risk Clients](images/compliance_dashboard.png)

*Client risk segmentation by sector, PEP condition, geographic distribution, and detailed client table with real-time filters.*

---

## 📊 Key Metrics & Visualizations

| Module | Metrics Tracked |
|--------|----------------|
| **Client Overview** | Active / Inactive clients, total count, status breakdown |
| **PEP Screening** | Politically Exposed Persons — flagged, percentage, condition breakdown |
| **Risk by Sector** | Distribution across Services, Financial, Construction, Public, Commercial, etc. |
| **PEP by Occupation** | Employed, Business Owner, Independent, Unemployed, Retired |
| **Geographic Map** | Client distribution by country of origin (PEP condition) |
| **Trust Accounts** | Fideicomisos count and status |
| **Client Detail Table** | Code, client name, occupation — filterable and sortable |

---

## ⚙️ Technical Architecture

```
Google Sheets (Data Source)
        │
        ▼
Python (ETL / Data Cleaning / Transformation)
        │
        ▼
Looker Studio (Dashboard Layer)
        │
        ├── Filters: Period · Executive · Status
        ├── Charts: Donut, Maps, Tables
        └── KPI Cards: Clients · PEP · Active · Trusts
```

### Data Pipeline Features
- **Automated data ingestion** from Google Sheets with scheduled refresh
- **Data accuracy validation** rules to ensure regulatory report integrity
- **Parameterized filters** for period, executive, and client status
- **Multi-page dashboard** covering compliance risk, portfolio, and client monitoring

---

## 🎯 Business Impact

- Reduced manual compliance reporting time significantly through automation
- Enabled real-time monitoring of PEP clients and high-risk accounts
- Supports AML (Anti-Money Laundering) internal audits and regulatory submissions
- Provides a single source of truth for compliance metrics across the organization

---

## 🛠️ Tech Stack

`Looker Studio` · `Google Sheets` · `Python` · `AML Framework` · `Data Governance`

---

## 📋 Compliance Framework

This dashboard aligns with:
- **AML/CFT** (Anti-Money Laundering / Counter Financing of Terrorism) monitoring requirements
- **PEP identification** standards per local and international regulatory guidelines
- **SSOT** (Single Source of Truth) data architecture principles
- Internal audit and regulatory reporting to Dominican financial supervisory authorities

---

*Built for internal compliance use. All client data shown in previews is anonymized.*

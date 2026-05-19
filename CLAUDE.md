# Portfolio — CLAUDE.md

Reference document for developing Aseel Alzahrani's data analyst portfolio site.

---

## About Aseel

| Field | Value |
|---|---|
| Name | Aseel Alzahrani |
| Role | Data Analyst |
| Location | Riyadh, Saudi Arabia |
| Current Employer | Aujan Coca-Cola Beverage Company (ACCBC) |
| Email | alzahraniaseel0@gmail.com |
| Phone | +966 598 261 537 |
| LinkedIn | https://www.linkedin.com/in/aseel-alzahrani-45ba06208/ |
| GitHub | https://github.com/aseelDE |
| Google Sites Portfolio | https://sites.google.com/view/assel0/projects |

**Summary:** Data Analyst specializing in turning raw, scattered data into clear dashboards and reports that help teams make faster, better decisions. Focuses on three core areas: data insights, automation of repetitive reporting tasks, and building automated data pipelines.

---

## Education

**Bachelor of Management Information Systems**
- University of Tabuk · Tabuk, KSA
- 2019 – 2023
- GPA: 4.72 / 5.0
- Covered: databases, systems analysis, programming, organizational decision-making with information systems

---

## Work Experience

### Data Analyst — Aujan Coca-Cola Beverage Company (ACCBC), Riyadh
**Aug 2025 – Present**

- Collect, clean, and transform raw datasets from multiple sources (Excel, databases, external files) using Power Query, ETL pipelines, and Microsoft Fabric
- Participate in performance reviews with the sales team to drive business unit initiatives and close performance gaps
- Identify product sales trends to help stakeholders make informed business decisions
- Design and build interactive dashboards and reports in Power BI to track KPIs, trends, and business performance
- Leverage AI tools to automate and enhance business reports
- Develop internal web portals to support business operations using Microsoft Azure
- Update and distribute the daily sales report to internal teams and branch offices

**Key outputs:** Power BI dashboards, automated daily reports, internal Azure web portals

**Tags:** Microsoft Fabric, Power BI, Azure, ETL

---

### ICT Graduate — AECOM (NEOM Airport Project), Neom, KSA
**Aug 2023 – Apr 2025**

- Reviewed ICT system designs and contractor submissions to ensure compliance with project, technical, and regulatory standards
- Coordinated with stakeholders to gather requirements, define scope, and validate implemented ICT and airport special systems
- Supervised installation and configuration of critical IT infrastructure: networks, cabling, security, and special airport systems

**Tags:** Large-scale Projects, Stakeholder Coordination, Technical Review

---

## Skills

### Dashboards & Reports
- **Tools:** Power BI, DAX, Excel Dashboards
- Builds interactive reports showing trends, KPIs, and decision-support visuals for managers

### Data Collection & Processing
- **Tools:** Microsoft Fabric, Power Query, Power Automate
- Builds automated systems that pull data from multiple sources, clean it, and prepare it for analysis

### Data Storage & Databases
- **Tools:** Snowflake, Google BigQuery, SQL
- Works with cloud databases to store and query large datasets

### Cloud Platforms
- **Tools:** Microsoft Azure, Google Cloud
- Deploys databases, data tools, and internal web portals on the cloud

### Programming & Automation
- **Tools:** Python, SQL, AI-assisted development
- Writes scripts to automate reports, process data, and build tools that reduce manual work

---

## Certifications

- Associate Data Engineer — Snowflake
- Data Analysis using Power BI
- Business Intelligence Path
- Data Ingestion & Semantic Models — Microsoft Fabric
- Data Visualization & Dashboards with Excel
- Reporting in SQL / Importing Data in Python

---

## Projects

### 1. E-commerce Sales Analysis
- **Status:** Completed
- **Problem:** Online retailer had scattered sales data with no view of top products, valuable customers, or lost revenue
- **Solution:** Built complete analysis — sales trends, customer segmentation, KPI dashboard
- **Tools:** Python, SQL, Data Analysis, Charts & Graphs
- **Outcomes:** Sales trends tracked, customer groups identified, KPI dashboard delivered
- **GitHub:** https://github.com/aseelDE/E-commerce-Data-Analytics.git

### 2. Automated Weather Data Collection
- **Status:** Completed
- **Problem:** Manual weather data downloading was slow and error-prone
- **Solution:** Fully automated system — connects to live weather source, collects, cleans, and stores data with no human intervention
- **Tools:** Python, Automation, Live Data Feed, Scheduling
- **Outcomes:** Fully automated pipeline, always-fresh live data, clean structured output
- **GitHub:** https://github.com/aseelDE/weather-data-pipeline.git

### 3. Supermarket Sales & Customer Report
- **Status:** Completed
- **Problem:** Supermarket chain needed a clear view of revenue, best-selling categories, and customer spending patterns
- **Solution:** Full dataset analysis with charts and a comprehensive report managers could immediately act on
- **Tools:** SQL, Python, Power BI, Excel
- **Outcomes:** Revenue analyzed, categories compared, full report delivered
- **GitHub:** https://github.com/aseelDE/aseelDE-Sales-Customer-Analytics.git

---

## Portfolio Site Design

### Concept
Data pipeline metaphor — each section of the portfolio maps to a pipeline stage:

| Stage | Label | Section |
|---|---|---|
| source | About | Profile / who I am |
| ingest | Skills | Tools & stack |
| transform | Projects | Built work |
| model | Experience | Career & education |
| serve | Contact | Reach out |

### Design System
- **Fonts:** JetBrains Mono (monospace, headings/badges/code), DM Sans (body text)
- **Primary:** Blue `#0EA5E9` / Dark Blue `#0284C7`
- **Secondary:** Teal `#10B981` / Dark Teal `#059669`
- **Accent:** Indigo `#6366F1`, Amber `#F59E0B`
- **Background:** `#FAFCFF` (near-white with blue tint)
- **Grays:** `--g50` through `--g900` scale (Slate palette)

### Navigation
- Top pipeline bar with clickable stage nodes
- Left/right arrow keys for keyboard navigation
- Status bar at bottom showing current stage and progress
- Each stage animates in/out with slide transition

### Tone & Voice
- Technical but accessible — avoids jargon, explains what each skill/tool actually does for the business
- Pipeline/data engineering metaphor throughout (files named `profile.json`, `stack.yml`, `career.sql`, etc.)
- Focus on problems solved and outcomes delivered, not just tools listed

### Responsiveness
- Tablet (≤900px): single-column layout, pipeline file names hidden
- Mobile (≤600px): pipeline bar simplified, hero pipeline stacks vertically, all grids collapse to single column

---

## Development Notes

- Single-file site: all HTML, CSS, and JS in `index.html`
- Deployed via GitHub Pages (`.github/workflows/static.yml`)
- No external JS dependencies — vanilla JS only
- No build step required — edit `index.html` directly
- `.vscode/` is gitignored

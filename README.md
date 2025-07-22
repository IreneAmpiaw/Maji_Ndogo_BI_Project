
# Maji Ndogo Water Access BI Project

## Project Overview

The **Maji Ndogo BI Project** is a business intelligence solution developed to support strategic decision-making regarding water access and infrastructure improvements in the fictional country of **Maji Ndogo**. The project aims to present a clear, actionable understanding of water accessibility challenges, infrastructure needs, and cost estimations across national and provincial levels.

This interactive Power BI report translates raw survey and infrastructure data into intuitive visuals that inform high-level stakeholders; including the President, provincial leaders, and planners  on how best to allocate resources to solve the national water crisis.

---

##  Objectives

The report was built with two main user groups in mind:

###  1. National Leadership
- Understand the **status of water access** at a national level.
- Identify **populations affected** by poor water access.
- Estimate **infrastructure upgrade costs**.
- Prioritize **spending by province and improvement type**.

### 2. Provincial Leaders
- View **localized water access data** for decision-making.
- Assess **specific community needs** (e.g., rural vs urban).
- Analyze **infrastructure types**, **queues**, **contamination**, and **budget allocations**.

---

## Key Insights

- **Over 50% of Maji Ndogo's population lacks access to basic water services** under UN criteria, primarily due to contamination, long queues, or broken infrastructure.
- **Wells are common water sources** but a significant portion are polluted and do not qualify as basic access.
-  **Public taps frequently have long queue times** (over 30 minutes), disqualifying them as "basic" water access points.
- **Urban areas generally have better access**, while **rural regions face higher infrastructure challenges** and require more costly upgrades.
- **Rural upgrades cost 50% more** than urban upgrades, based on field conditions and logistics. This factor was built into the cost model using DAX.
- **Total estimated budget** for improving infrastructure nationwide is substantial, requiring prioritization per region.
- **Drill-through functionality allows users to view detailed breakdowns per province**, including water source types, cost per improvement type, and localized needs.
- **Key improvements like installing public taps and repairing infrastructure** will significantly raise basic access levels.
- Using calculated measures and categorized visuals, stakeholders can clearly **see the impact of planned investments on water accessibility**.

---

## Features of the Power BI Report

### National Dashboard
- Population & Water Source Breakdown (Urban vs Rural)
- Visual distribution of source types and service quality
- Aggregated improvement types (e.g., "Install public taps")
- Budget estimations including **rural adjustment factor**
- Bookmark toggles between **cost by province** and **cost by improvement**

### Provincial Dashboards
- Custom views for each province (e.g., Sokoto, Amanzi, etc.)
- Urban vs Rural water service visualization
- Drill-through functionality from national to provincial views
- Key stats including queue times, pollution levels, and gender breakdowns

### Key Metrics Calculated
- **Basic Water Access %** (per UN standards)
- **Total Upgrade Cost (USD)**
- **Estimated lives improved**
- **Rural vs Urban budget adjustment**
- DAX-calculated metrics for:
  - `Rural_adjusted_cost`
  - `Budgeted_improvement_cost`
  - `Basic_water_access`
  - `Formatted_change` in access percentage

---

## Methodology

The report design was driven by a user-centric **user story approach**, where the needs of the President and provincial leaders were considered at each design step. Key decisions include:

- Emphasizing impactful storytelling through visuals.
- Grouping content into three logical blocks:
  1. **Who** is affected?
  2. **What** needs to be done?
  3. **How much** will it cost?
- Making use of **slicers**, **maps**, and **bookmark toggles** for navigation and filtering.
- Providing **clean summaries and interactivity** for decision-makers to drill into relevant data.

---

## Tools Used

- **Power BI Desktop (.pbix)**
- **DAX** (Data Analysis Expressions) for calculations
- **Data modeling & relationships** within Power BI
- **Bookmarking & Buttons** for interactivity


---

## Getting Started

To explore the report:

1. Download and open the `.pbix` file in [Power BI Desktop]
2. Use the slicers to filter by province or region.
3. Toggle bookmarks to view cost breakdowns.
4. Drill through from the national dashboard to individual provinces.

---

## Contribution

Contributions and suggestions are welcome. Please open an issue or submit a pull request if you would like to improve this project.

---

## License

This repository is for educational purposes. All rights to data and content belong to **ExploreAI 2023**.


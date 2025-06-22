# Strategic Analysis of a Facebook Ad Campaign

This repository contains a comprehensive analysis of a Facebook advertising campaign, designed to identify key performance drivers and provide data-driven recommendations for optimizing future ad spend. This project demonstrates a full analytics workflow, from data cleaning and modeling in Excel to strategic reporting and presentation.

---

## 1. Project Objective & Business Problem

The primary objective of this project was to analyze a dataset of Facebook ad campaigns to determine the factors that lead to the highest conversion rates and return on investment (ROI). The analysis aims to answer a core business question: **How can marketing resources be allocated more effectively to maximize campaign performance?**

*   **Research Question:** Which combination of audience demographics and ad spend most significantly influences the Return on Ad Spend (ROAS)?
*   **Hypothesis:** Ads targeted towards the 30-34 age demographic will yield a statistically significant higher ROAS compared to other age segments.
*   **Decision to Support:** The analysis provides a data-driven recommendation for allocating future marketing budgets, prioritizing the most profitable audience segments and campaign strategies.

---

## 2. Project Deliverables

This repository includes three core deliverables:

*   **`Facebook_Ad_Analysis_Report.pdf`**: A three-page academic paper detailing the project's introduction, research methodology, data sources, and a full summary of the findings.
*   **`Facebook_Ad_Campaign_Presentation.pptx`**: A presentation summarizing the project's key insights and strategic recommendations for stakeholders.
*   **`Facebook_Ad_Analysis_Model.xlsx`**: A comprehensive Excel model containing the entire data analysis, from raw data to an interactive executive dashboard.

---

## 3. Methodology & Workflow

The analysis was conducted entirely within Microsoft Excel, leveraging its advanced data modeling and visualization capabilities.

1.  **Data Sourcing and Cleaning (ETL):**
    *   The raw data was sourced from the "Facebook Ad Campaign Stats" dataset on Kaggle.
    *   **Power Query** was used to perform initial data cleaning and transformation, ensuring data types were correct, handling missing values, and creating calculated columns for analysis (e.g., Cost Per Click, Conversion Rate, ROAS).

2.  **Excel Model & Analysis:**
    *   The Excel workbook is structured into four distinct tabs: `Inputs`, `Data`, `Analysis`, and `Dashboard`.
    *   The **`Analysis`** tab contains the core calculations, including PivotTables to segment performance by campaign, ad, and demographic.
    *   Advanced functions like **`XLOOKUP`** and `SUMIFS` were used to aggregate data and link tables.
    *   **Scenario Manager** was utilized to model the potential impact of different budget decisions on key performance indicators like Total Conversions and ROI.

3.  **Dashboarding and Visualization:**
    *   A dynamic dashboard was created to present findings in an intuitive, visual format.
    *   An interactive element allows a user to select a specific **Campaign ID** from a dropdown menu, which dynamically updates all performance metrics and charts on the dashboard.

---

## 4. Key Findings & Recommendations

*   **Finding 1:** **Campaign 1178** consistently achieved the highest Return on Ad Spend (ROAS) at **4.2**, despite having a moderate budget, indicating a highly effective ad creative and targeting strategy.
*   **Finding 2:** The **30-34 age group** proved to be the most valuable audience segment, generating a **25% higher conversion rate** and a **30% higher ROAS** than the next best-performing segment.
*   **Finding 3:** While male audiences generated more total impressions, **female audiences had a 15% higher click-through rate (CTR)**, indicating stronger ad relevance and engagement within that group.
*   **Final Recommendation:** Based on the analysis, it is recommended to reallocate a significant portion of the budget to campaigns mirroring the strategy of **Campaign 1178**, specifically targeting **women aged 30-34**.

---

## 5. Technical Skills & Tools Demonstrated

*   **Data Analysis:** Microsoft Excel, Advanced Formulas (`XLOOKUP`, `INDEX-MATCH`, `IF/AND/OR`), PivotTables, Scenario Manager.
*   **Data Cleaning (ETL):** Power Query.
*   **Data Modeling:** Creation of a structured analytics model with separate tabs for inputs, data, and analysis. Use of Named Ranges for clarity.
*   **Business Intelligence & Visualization:** Interactive Excel Dashboards, Dynamic Charts, Data Validation for user inputs.
*   **Reporting & Presentation:** Microsoft PowerPoint, Formal Academic Writing.

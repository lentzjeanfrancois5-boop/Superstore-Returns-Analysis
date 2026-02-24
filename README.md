# 📦 Superstore Returns Analysis
**Presentation Link:** [Watch the Video Here](https://drive.google.com/file/d/1ruFTdK6p3aygAgf3ulaYCfmO74YObxDf/view?usp=sharing)

![Dashboard Preview](TableauScreenShotofDashboard.png)

## 🔗 Project Link
**Tableau Public Workbook:** [View Interactive Dashboard](https://public.tableau.com/app/profile/lentz.francois/viz/1FinishedStoryTellingWithDataProject/Dashboard1?publish=yes)

---

## 📋 Project Objective
This analysis was prepared for the **Superstore CEO** to identify the root causes of high return rates. The goal is to move beyond simple sales volume and perform a diagnostic audit of geographic, seasonal, and product-specific factors driving capital loss.

## 🔍 Key Insights & Findings
* **The Geography Problem:** The **Western Region** is a significant outlier. Analysis suggests that the return volume is decoupled from sales performance, pointing toward logistical hurdles or distribution center inefficiencies in that territory.
* **High-Risk Categories:** * **Technology:** 27.3% (Highest Impact)
    * **Office Supplies:** 25.7%
    * **Furniture:** 25.6%
* **The Revenue Impact Logic:** While return percentages across categories are within a narrow 1.7% range, the **capital risk** is concentrated in Technology. Due to high unit costs, a 27.3% return rate in Tech represents a much larger drain on net margins than equivalent rates in Office Supplies.
* **Statistical Context (P-Value 0.20):** A P-value of 0.20 indicates that sales volume is **not** a statistically significant predictor of returns. This confirms that returns are driven by **operational variables** (packaging, shipping, or product defects) rather than being a natural byproduct of increased sales.



## 🖥️ Dashboard Functionality
The final dashboard is a synchronized executive monitoring tool designed for "drill-down" diagnostics:
1. **Geographic Map:** Visualizes return "hotspots" to isolate regional failures.
2. **Product Category Analysis:** Compares return rates across business segments to identify margin-dilutive products.
3. **Sales vs. Returns Scatterplot:** Monitors the correlation (or lack thereof) between volume and return frequency.
4. **Customer Tracker:** Utilizes a **Descending Sort** to identify high-frequency "serial returners" for policy review.

> **Technical Note:** This dashboard utilizes **four global filters** applied across the entire data source. Toggling any dimension instantly updates all worksheets to maintain a "Single Source of Truth" during executive reviews.



## 🚀 Proposed Next Steps
* **Technology Quality Audit:** Investigate top-returned Tech SKUs to determine if defects or inadequate protective packaging are driving the 27.3% rate.
* **Western Region Logistics Review:** Audit last-mile shipping partners in the Western territory to address the disproportionate return volume.
* **Return Policy Refinement:** Use the Customer Tracker to assess the feasibility of a tiered return policy for identified high-frequency returners.

---

## 📁 Submission Contents
| File Name | Description |
| :--- | :--- |
| `README.md` | Project summary and Tableau Public Link. |
| `Sketches.pdf` | 3 Low-fidelity pen-and-paper dashboard mock-ups (Design Process). |
| `Dashboard_Final.png` | High-resolution screenshot of the final production dashboard. |
| `Story_Draft.png` | 7-point story arc mapping the narrative flow of the analysis. |

---
*Note: The presentation exceeds the 5-minute suggestion to provide a thorough demonstration of the four synchronized filters and the root cause analysis requested by the rubric.*

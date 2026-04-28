## The Hidden Economy: UK Time Use Survey & The General Production Boundary

[![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Tableau-E97627?style=flat-square&logo=tableau)](#)
[![Analysis](https://img.shields.io/badge/Analysis-Exploratory%20(EDA)-0052CC?style=flat-square)](#)
[![Domain](https://img.shields.io/badge/Domain-Socio--Demographics-1F77B4?style=flat-square)](#)

## Strategic Context & Objective

Conceived as a continuation of the Time Poverty econometric analysis in urban Chile, this supplementary project explores whether the dynamics of unpaid labour and the "General Production Boundary" hold true across different socio-economic and geographic contexts. 

Utilizing the **United Kingdom Time Use Survey (2014-2015)**, this project delivers an **Exploratory Data Analysis (EDA)** focused on visual storytelling. The primary objective is to map time allocation across demographics to uncover the hidden value of non-market labour—activities fundamentally acknowledged as productive by the International Labour Organization (ILO), yet systematically excluded from Neoclassical GDP metrics.

## Data Wrangling & Feature Engineering

Transforming raw survey responses into an analytically viable dataset required extensive feature engineering and data aggregation prior to visualization:

* **Synthesized** over 50 raw, isolated survey variables (e.g., individual minutes spent sweeping, cooking, or commuting) into 7 core analytical time-use categories (such as *Household & Family Care*, *Employment*, and *Leisure*). 
* **Structured** the aggregated data to enable robust macro-level demographic comparisons without compromising the statistical integrity of the original time diaries.

## 🔍 Key Analytical Insights

Employing a top-down visual funnel—from national macro-trends to family micro-dynamics—the analysis reveals two critical structural patterns:

1. **The Myth of Economic Inactivity:** As demonstrated in the *Productive Activities by Age* visualization, segments officially classified by traditional economics as "inactive" (children and the elderly) absorb a massive share of Household Labour. Their unpaid caregiving and domestic work directly subsidize the formal economy by enabling prime-age adults to participate in the market.
2. **The Early Onset of the Gender Gap:** Time allocation breakdowns indicate that the gendered division of household labour emerges in early childhood, mirroring adult patterns. This finding challenges the neoclassical assumption that domestic work allocation is purely a "profitable trade-off" based on adult market wages, pointing instead to deeply ingrained cultural structures.

## 📊 Interactive Data Story (Tableau)

*Click the preview below to explore the interactive dashboard on Tableau Public. Utilize the global filters (Day, Age Group, Country) to customize the demographic view.*

[![UK Time Use Dashboard Preview](./images/dashboard_preview.png)](AQUÍ_PEGA_EL_LINK_DE_TU_TABLEAU_PUBLIC)

> 🔒 **Data Governance & Privacy Note:** > Adhering to data privacy best practices and file size constraints, the underlying raw microdata is excluded from this repository. The interactive Tableau dashboard utilizes an aggregated data extract to protect respondent anonymity while preserving analytical depth.

## 📁 Repository Structure

* `README.md`: Project overview, methodology, and key findings.
* `/images`: Static visual assets and dashboard wireframes.
* `UK_Time_Use_Analysis.twbx`: Packaged Tableau Workbook containing backend calculations and the data model structure.

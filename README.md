# The Hidden Economy: UK Time Use Survey & The General Production Boundary

[![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Tableau-E97627?style=flat-square&logo=tableau)](#)
[![Analysis](https://img.shields.io/badge/Analysis-Exploratory%20(EDA)-0052CC?style=flat-square)](#)
[![Domain](https://img.shields.io/badge/Domain-Socio--Demographics-1F77B4?style=flat-square)](#)

## 🌍 Strategic Context & Objective

Following my econometric modelling of Time Poverty in urban Chile, I developed this supplementary project to explore whether the dynamics of unpaid labour and the "General Production Boundary" hold true across different socio-economic contexts. 

Using the **United Kingdom Time Use Survey (2014-2015)**, this project serves as an **Exploratory Data Analysis (EDA)** focused on visual storytelling. The objective is to map time allocation across demographics to uncover the hidden value of non-market labour—activities fundamentally acknowledged as productive by the International Labour Organization (ILO), yet often invisible in Neoclassical GDP metrics.

## 🛠️ Data Wrangling & Feature Engineering

Before any visualization could occur, the raw survey data required extensive cleaning and feature engineering to be analytically viable. 
* **Variable Synthesis:** I synthesized over **50 raw, isolated survey responses** (e.g., individual minutes spent sweeping, cooking, commuting to specific places) into **7 core analytical time-use categories** (such as *Household & Family Care*, *Employment*, and *Leisure*). 
* This robust aggregation allows for macro-level demographic comparisons without losing the statistical integrity of the original time diaries.

## 🔍 Key Analytical Insights

By employing a top-down visual funnel (from national macro-trends to family micro-dynamics), the data reveals two critical patterns:

1. **The Myth of Economic Inactivity:** As demonstrated in the *Productive Activities by Age* analysis, segments officially classified by traditional economics as "inactive" (children and the elderly) hold a massive share of Household Labour. Their unpaid caregiving and domestic work directly subsidize the formal economy by enabling prime-age adults to participate in the market.
2. **The Early Onset of the Gender Gap:** Time allocation breakdowns reveal that the gendered division of household labour follows the exact same pattern in Children as it does in Adults. This challenges the neoclassical assumption that domestic work allocation is purely a "profitable trade-off" based on adult market wages, pointing instead to deeply ingrained cultural structures.

## 📊 Interactive Data Story (Tableau)

*Click on the preview below to explore the full interactive dashboard on Tableau Public. Use the global filters (Day, Age Group, Country) to customize the demographic view.*

[![UK Time Use Dashboard Preview](./images/dashboard_preview.png)](AQUÍ_PEGA_EL_LINK_DE_TU_TABLEAU_PUBLIC)

> 🔒 **Data Governance & Privacy Note:** > Due to file size constraints and adherence to data privacy best practices, the underlying raw microdata has not been uploaded to this repository. The interactive Tableau dashboard utilizes an aggregated extract to protect respondent anonymity while preserving analytical depth.

## 📁 Repository Structure

* `README.md`: Project overview and key findings.
* `/images`: Static visual assets and dashboard wireframes.
* `UK_Time_Use_Analysis.twbx`: Packaged Tableau Workbook (Backend calculations and data model structure).

# The Hidden Economy: UK Time Use Survey & The General Production Boundary

[![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Tableau-E97627?style=flat-square&logo=tableau)](#)
[![Analysis](https://img.shields.io/badge/Analysis-Exploratory%20(EDA)-0052CC?style=flat-square)](#)
[![Domain](https://img.shields.io/badge/Domain-Socio--Demographics-1F77B4?style=flat-square)](#)

## Strategic Context & Objective

This project originated as a foundational Exploratory Data Analysis (EDA) designed to map time allocation behaviors, establishing the groundwork for subsequent econometric modelling that integrates both time and income metrics into a multidimensional framework.

Utilizing the **United Kingdom Time Use Survey (2014-2015)**, the primary objective is to visually decode demographic patterns and uncover the hidden value of non-market labour—activities fundamentally acknowledged as productive by the International Labour Organization (ILO), yet systematically excluded from Neoclassical GDP metrics.

## Data Wrangling & Feature Engineering

Transforming raw survey responses into an analytically viable dataset required extensive feature engineering and data aggregation prior to visualization:

* **Synthesized** over 335 raw, isolated survey variables (e.g., individual minutes spent sweeping, cooking, or commuting) into 7 core analytical time-use categories (such as *Household & Family Care*, *Employment*, and *Leisure*). 
* **Structured** the aggregated data to enable robust macro-level demographic comparisons without compromising the statistical integrity of the original time diaries.

## Key Analytical Insights

Employing a top-down visual funnel—from national macro-trends to family micro-dynamics—the analysis reveals two critical structural patterns:

1. **The Myth of Economic Inactivity:** As demonstrated in the *Productive Activities by Age* visualization, segments officially classified by traditional economics as "inactive" (children and the elderly) absorb a massive share of Household Labour. Their unpaid caregiving and domestic work directly subsidize the formal economy by enabling prime-age adults to participate in the market.
2. **The Early Onset of the Gender Gap:** Time allocation breakdowns indicate that the gendered division of household labour emerges in early childhood, mirroring adult patterns. This finding challenges the neoclassical assumption that domestic work allocation is purely a "profitable trade-off" based on adult market wages, pointing instead to deeply ingrained cultural structures.
3. **The Commuting Paradox & Mobility:** The impact of vehicle ownership on commute times is heavily dictated by geography and family structure rather than simple economics. While regions like England show marginal differences, lacking a vehicle severely penalises families in Scotland and Wales, highlighting a hidden "infrastructure tax" on unpaid caregiving and household management.

## Interactive Data Story (Tableau)
<img width="1749" height="2936" alt="dashboard_preview_HiddenEconomy" src="https://github.com/user-attachments/assets/17df03b9-ad31-4808-9576-5a69cbbcf18f" />


**[Alternatively, click here to view the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/HiddenEconomy_Master/HiddenEconomy?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

> **Data Governance & Privacy Note:** > Adhering to data privacy best practices and file size constraints, the underlying raw microdata is excluded from this repository. The interactive Tableau dashboard utilizes an aggregated data extract to protect respondent anonymity while preserving analytical depth.


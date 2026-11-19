# Getir – Reducing Avoidable Returns

**Business Analysis | NextLeap Graduation Project | November 2026**

## Project Overview

This project analyses avoidable product returns in Getir's quick-commerce operations across product categories, regions and customer segments.

The objective is to understand where avoidable returns are concentrated, identify frequently recorded return reasons and recommend operational areas for further investigation.

The project combines quantitative data analysis, customer research, business requirements documentation and interactive Tableau reporting.

## Business Problem

Product returns can create additional operational costs and customer inconvenience.

This project examines recorded return patterns to identify areas potentially associated with expiry dates, incorrect items, packaging defects and product handling.

## Project Objectives

- Measure the overall avoidable return rate and associated product value.
- Identify return patterns across product categories and regions.
- Compare customer segments.
- Identify the most frequently recorded avoidable return reasons.
- Explore areas requiring further operational investigation.
- Develop practical recommendations while considering customer experience.

## Tools Used

- **Microsoft Excel:** Data preparation, KPI calculations and exploratory analysis.
- **Tableau Public:** Interactive dashboard development and data visualisation.
- **Business Analysis:** Business requirements, project scoping and recommendations.
- **Customer Research:** Customer experience analysis and thematic analysis.

## Key Findings

The analysis covered 30,271 order-detail records.

| KPI | Result |
|---|---:|
| Total order-detail records | 30,271 |
| Returned rows | 1,424 |
| Avoidable returned rows | 1,125 |
| Avoidable Return Rate | 3.72% |
| Avoidable Share of Returns | 79.00% |
| Estimated Avoidable Return Value | 26,962.47 |

### Category Analysis

- Household Cleaning recorded the highest avoidable return rate at 5.51%.
- Meat & Poultry contributed the highest estimated avoidable return value of 5,980.51.

### Regional Analysis

- Mediterranean recorded the highest regional avoidable return rate at 4.50%.
- Marmara contributed the highest avoidable return count and estimated value.

### Return Reason Analysis

- Expired Date was the most frequently recorded avoidable return reason, with 156 rows.
- Wrong Item Sent followed with 114 rows.

## Tableau Dashboard

Explore the interactive dashboard:

[View Getir – Overall Returns Overview on Tableau Public](https://public.tableau.com:9443/views/NL_Getir_Tableau/OverallReturnsOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Business Recommendations

The analysis identified six areas for further investigation:

1. Review expiry-date checks, stock rotation and inventory controls.
2. Investigate order-picking verification and item accuracy.
3. Prioritise category-level quality reviews.
4. Examine regional return patterns while considering record volumes.
5. Review packaging and product-handling controls.
6. Monitor customer complaints and resolution experiences.

## Project Deliverables

- Final project report.
- Business Requirements Document (BRD).
- Excel-based data analysis and KPI calculations.
- Interactive Tableau dashboard.
- Customer research and thematic analysis.
- Business recommendations.

## Methodology and Limitations

The unit of analysis is an order-detail row representing an individual product line within an order.

A returned row is classified as avoidable when its recorded return reason is other than Customer Changed Mind.

Avoidable Return Value is calculated using:

`UnitPrice × Quantity × (1 − DiscountRate)`

This represents estimated product value, not confirmed refunds, audited losses or net financial impact.

The analysis is descriptive and does not establish the operational root cause of individual returns.

Customer research involved three participant accounts from Zepto, BigBasket and Blinkit. It provides supplementary industry context rather than direct evidence of Getir's operations. Two participant accounts were adapted rather than verbatim transcripts.

The source-level data quality checklist was not fully completed in the working workbook. Therefore, the project does not claim that all source-level validation checks have passed.

## Conclusion

The project establishes a baseline for understanding avoidable returns and identifies variations across product categories, regions and recorded return reasons.

The findings provide a starting point for investigating inventory management, order-picking accuracy, product quality and customer experience.

The recommendations focus on potential operational improvements without assuming that stricter customer return policies are the appropriate solution.

---

**Programme:** NextLeap Graduation Project  
**Project:** Getir – Reducing Avoidable Returns Across Product Categories, Regions and Customer Segments  
**Report Date:** 5 November 2026

# Andes Retail Group: Sales Performance Dashboard

## Executive Summary

Andes Retail Group needed a consolidated view of its sales performance to understand how revenue, profit, margin, and sales volume varied across countries, product categories, customer segments, and time periods.

I developed a Power BI dashboard that transformed transactional sales data into an executive and analytical reporting solution. The report combines commercial KPIs, monthly trends, category performance, geographic comparisons, customer segmentation, and seasonality analysis.

The business generated approximately $5.5 million in revenue and $1.94 million in profit, with an overall margin of approximately 35.1%. Peru and Chile represented a significant share of revenue, while the Premium and Standard customer segments generated the largest proportion of sales.

The analysis also revealed seasonal variations in performance, supporting recommendations related to market prioritization, category strategy, and sales planning.

## Business Problem

The project focused on the following business questions:

- How much revenue and profit did the company generate?
- How did sales performance change throughout the analyzed period?
- Which product categories contributed most to revenue?
- Which countries and customer segments generated the strongest results?
- Were there seasonal patterns that could affect commercial planning?

The objective was to create a dashboard that allowed management to move from a general performance view to more detailed analysis by country, segment, category, and time period.

## Dataset and Scope

The dataset contained sales information for the 2024–2025 period, including:

- Revenue
- Profit
- Units sold
- Customers
- Product categories
- Countries
- Customer segments
- Transaction dates

The 2025 data represents a partial period. For that reason, comparisons between 2024 and 2025 must be interpreted carefully and should not be treated as comparisons between two complete years.

## Data Model and KPI Development

I prepared the data model in Power BI and created measures to evaluate:

- Total revenue
- Total profit
- Profit margin
- Units sold
- Unique customers
- Revenue by country
- Revenue by category
- Performance by customer segment
- Monthly and seasonal trends

DAX measures and filter context were used to ensure that the KPIs responded correctly to the report’s filters and navigation.

## Dashboard Structure

### 1. Executive Overview

The executive page provides a high-level view of:

- Total revenue
- Total profit
- Profit margin
- Units sold
- Unique customers
- Monthly sales trends
- Revenue by product category
- Overall business performance

### 2. Detailed Analysis

The detailed page allows users to explore:

- Revenue by country
- Performance by customer segment
- Category-level comparisons
- Seasonal behavior
- Revenue and margin relationships
- Detailed results through filters and interactive visuals

## Key Findings

- Andes Retail Group generated approximately $5.5 million in revenue.
- Total profit reached approximately $1.94 million.
- The overall profit margin was approximately 35.1%.
- Peru and Chile represented a significant proportion of total revenue.
- Premium and Standard customers generated the largest share of sales.
- Product categories showed meaningful differences in revenue contribution and margin.
- Seasonal variations were identified across the analyzed period.
- Because 2025 is incomplete, its results should not be directly compared with a full year without considering the difference in coverage.

## Business Recommendations

- Prioritize commercial efforts in countries with strong revenue and margin performance.
- Review markets with high sales but comparatively lower margins to identify cost or pricing issues.
- Strengthen the product categories that combine high revenue with healthy margins.
- Develop targeted actions for the Premium and Standard customer segments while exploring opportunities in lower-participation segments.
- Adjust inventory, marketing, and sales planning according to the seasonal patterns identified.
- Continue monitoring 2025 results as additional months become available before making definitive year-over-year conclusions.

## Tools and Techniques

- Power BI
- DAX
- Power Query
- Data modeling
- KPI development
- Time-series analysis
- Customer segmentation
- Seasonal analysis
- Executive data visualization

## Dashboard Preview

### Executive Overview

![Executive Overview](images/executive_overview.png)

### Detailed Analysis

![Detailed Analysis](images/detailed_analysis.png)

## Repository Structure

```text
data/       Dataset used in the analysis
powerbi/    Interactive Power BI report
images/     Dashboard screenshots
README.md   Project documentation

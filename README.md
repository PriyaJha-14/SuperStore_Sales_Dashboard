# Super Store Sales Dashboard

An interactive Power BI project for sales analysis and short-term forecasting using Super Store data. The project combines business-focused dashboarding with time series analysis to uncover patterns in sales, profit, shipping behavior, customer segments, and state-level performance, and extends the analysis with a 15-day sales forecast. 

## Project overview

This project was built to analyze Super Store sales performance and support better decision-making through interactive visuals and forecasting. It focuses on identifying high-level KPIs, comparing year-over-year trends, evaluating operational dimensions such as shipping and payment mode, and forecasting near-term sales using historical patterns.

## Objectives

- Track core business KPIs such as orders, sales, profit, and average shipping days.
- Compare monthly sales and monthly profit across years to identify trends and seasonality.
- Analyze sales distribution by payment mode, region, segment, ship mode, category, sub-category, and state.
- Generate a 15-day sales forecast using time series analysis to support short-term planning.
- Build an interactive dashboard experience that helps users filter performance by region. 

## Dashboard highlights

### 1. Sales performance dashboard

The main dashboard presents a consolidated business view with KPI cards and multiple comparative visuals. Based on the provided dashboard image, the report tracks 22K orders, 1.6M in sales, 175K in profit, and 4 average shipping days, while also allowing region-level analysis through interactive filters.

Key visuals included:
- Sales by payment mode donut chart.
- Sales by region donut chart.
- Sales by segment donut chart.
- Monthly sales by year-over-year line/area view.
- Monthly profit by year-over-year trend view.
- Sales by ship mode bar chart.
- Sales by sub-category bar chart.
- Sales by category bar chart.
- Profit and sales by state map.

### 2. Forecast dashboard

The forecasting page extends the analysis beyond descriptive reporting by projecting sales for the next 15 days. The dashboard uses historical sales behavior to visualize recent performance and a forecast band, helping stakeholders prepare for short-term fluctuations and planning needs.

Key visuals included:
- Sales forecast timeline with projected future values.
- Focused 15-day forecast visual for recent periods.
- State-wise sales ranking bar chart highlighting top-performing states such as California and New York in the provided image.

## Tools and skills used

- Power BI for dashboard design, modeling, and interactivity.
- Data analysis techniques to examine sales, profit, segments, and regional performance.
- Time series analysis for short-term sales forecasting.
- Business storytelling through KPI cards, charts, slicers, and maps.

## Learnings from the project

This project strengthened practical skills in data analysis and business intelligence by combining reporting and forecasting in one solution. It incorporated data analysis techniques, with a focus on time series analysis, to deliver useful insights, accurate sales forecasting, and interactive dashboard creation that can support business success.

Key learnings:
- Converting raw sales data into business-ready insights through dashboard design.
- Selecting KPIs that clearly communicate business performance.
- Comparing year-over-year trends to detect seasonality and growth patterns.
- Using state, segment, and category analysis to identify major revenue contributors.
- Applying forecasting concepts to support short-term planning and strategic decisions.

## Business insights from the provided dashboard

From the supplied visuals, consumer sales appear to contribute the largest segment share, standard class is the dominant shipping mode, and office supplies leads category-wise sales. The forecast page also shows that California is the top state by sales in the displayed ranking, followed by New York and Texas.

The year-over-year monthly trend charts suggest stronger sales and profit performance in the later months of the year in the displayed view, indicating possible seasonality and end-of-year uplift. This kind of analysis can help businesses plan promotions, stock allocation, and shipping operations more effectively.

## Repository structure

A typical structure for this project on GitHub can be:

```bash
SuperStore_Sales_Dashboard/
│── README.md
│── Sales Dashboard.pbix
│── Dashboard_img-1.jpg
│── Forecast_img-2.jpg
└── SuperStore_Sales_Data.xlsx
```

## How to use

1. Download or clone the repository.
2. Open the Power BI file in Power BI Desktop.
3. Refresh the dataset if the source file is included.
4. Use the region filters and chart interactions to explore sales and profit performance.
5. Review the forecast page to analyze projected short-term sales movement.


## Author

Priya Jha

GitHub repository: [SuperStore_Sales_Dashboard](https://github.com/PriyaJha-14/SuperStore_Sales_Dashboard)

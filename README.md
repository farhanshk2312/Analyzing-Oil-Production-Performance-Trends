# Project Title: Analyzing Business Performance Trends Across PADD Areas

(1) Project Overview

Data Source: https://www.eia.gov/petroleum/ 

This project dives deep into historical business performance data to uncover key patterns, track growth, and identify areas of volatility. The dataset contains multiple years of production, pricing, revenue, and volume records, segmented across various Petroleum Administration for Defense Districts (PADD) areas. The goal was to analyze trends, measure consistency, and derive actionable insights that could support data-driven business decisions.


(2) Exploratory Data Analysis

    (2.1) Temporal Trends:
    
        Plotted production and revenue over the years to track long-term performance.
        
        Created monthly trend visualizations to spot seasonality and cyclical patterns.

    (2.2) Regional Analysis:
    
        Grouped data by PADD areas to compare production and revenue contributions region-wise.
        
        Identified high-performing vs low-performing PADD regions and their growth trajectories.

    (2.3) Price vs Volume Relationship:
        
        Built line combo charts comparing price fluctuations with monthly sales volumes.
        
        Observed how price changes affected demand elasticity across different regions.

     (2.4) Volatility & Consistency Checks:
    
        Calculated Coefficient of Variation (CV) for revenue and production to assess stability.
        
        Computed a Revenue Consistency Score based on average revenue and its variability.

        Decline Rate Analysis: 
        Identified periods of decline by calculating the percentage drop between consecutive periods, both overall and per PADD region.


(3) Key Metrics

    Coefficient of Variation	e.g. 0.23	Lower CV means more consistent revenue
   
    Revenue Consistency Score	e.g. 78/100	Higher score means steady revenue growth
    
    Decline Rate	e.g. −12%	Indicates downturn periods in performance
    
    Top PADD Contributor	e.g. PADD 3	Highest share of total production and revenue


(4) Visualizations Created

    Production Trend Over Years (Title: “Yearly Production Trend”)
    
    Revenue Over the Years (Title: “Revenue Growth Over Time”)
    
    Regional Performance (Title: “Production & Revenue by PADD Area”)
    
    Price vs Monthly Volume (Title: “Monthly Volume vs Price Trend”)
    
    KPI Cards showing YoY growth, total revenue, average price, etc.


(5) Insights

    Production showed steady growth with occasional dips aligned to seasonal factors.
    
    Revenue growth was overall positive, though certain months revealed high volatility.
    
    PADD 3 emerged as the largest contributor to production and revenue, while PADD 1 showed the most variability.
    
    Price increases had a noticeable inverse effect on volume after a certain threshold, more pronounced in PADD 2.
    
    Revenue consistency score indicated moderate stability, with room for improving demand forecasting.


(6) Conclusion

This analysis uncovered meaningful trends and performance patterns across multiple PADD regions. By quantifying consistency, tracking decline rates, and segmenting regional contributions, stakeholders can better anticipate downturns and optimize production, pricing, and sales strategies across geographies.


(7) Next Steps:

Build predictive models to forecast demand and revenue by PADD region.

Create automated dashboards that update monthly with fresh data.

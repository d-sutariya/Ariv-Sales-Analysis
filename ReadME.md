# Sales Analysis Dashboard for Ariv Hardware Inc.

## Overview  
Ariv Hardware Inc., headquartered in Delhi, operates stores across various regions of India, including North, South, and Central zones. Until recently, sales projections and business health assessments were conducted manually by the sales director, leading to inconsistencies and inefficiencies. To address this, a dashboard was developed to provide a centralized and interactive view of sales data, ensuring reliable decision-making and streamlined sales tracking.

## Objective  
The primary objective of this project was to design and implement a comprehensive dashboard that enables the company to:  
1. Monitor sales performance across regions and cities.  
2. Analyze profit margins, top-performing markets, and products.  
3. Identify growth opportunities in underserved markets.  
4. Improve decision-making and operational efficiency by leveraging historical sales data.  

## Dataset  
The data was sourced from the company's transactional database, comprising the following tables:  
1. **Date**: Contains hierarchical time data (year, month, etc.).  
2. **Customers**: Stores customer details, including type and code.  
3. **Products**: Details product types and codes.  
4. **Transactions**: Captures key sales metrics, such as quantity sold, sales amount, profit margins, and cost prices.  
5. **Markets**: Contains regional and zone information.  

## Challenges and Data Cleaning  
Real-world data challenges were addressed through robust preprocessing:  
1. Removal of `/r` characters in currency columns.  
2. Elimination of duplicate entries.  
3. Conversion of all currencies to INR for consistency.  
4. Exclusion of data from the USA, as the company no longer operates in this region.  
5. Tackled zero sales amount products by communicating with the team to confirm data accuracy.

## Key Findings  
1. **Regional and Product Insights**:  
   - The company has strong revenue and profit margins in major cities such as Delhi, Mumbai, Ahmedabad, and Chennai due to bulk sales.  
   - Mid-tier cities like Surat, Patna, and Bhubaneswar show significant potential for growth, with higher profit-to-revenue ratios than larger cities.  
2. **Profitability Challenges in Bengaluru**:  
   - Despite being a key market, Bengaluru shows profitability struggles. Targeted strategies should be implemented to strengthen its position.  
3. **Top Markets and Products**:  
   - Analysis of sales trends revealed the most profitable regions, products, and customer types, aiding in inventory optimization and targeted marketing campaigns.  

## Tools and Technologies  
- **Power BI**: For building interactive and visually appealing dashboards with drill-throughs, filters, and regional hierarchies.  
- **Power Query**: Used for data cleaning, transformation, and integration of multiple datasets.  

## Recommendations  
1. Focus on expanding operations and marketing in high-potential mid-tier cities.  
2. Address operational inefficiencies in Bengaluru through market analysis and customer engagement.  
3. Leverage insights to optimize inventory and promotional strategies for top-performing products and regions.  

## Outcome  
The dashboard provides the sales director and other stakeholders with a holistic view of the company's performance, enabling data-driven decisions and improving the overall operational efficiency of Ariv Hardware Inc.  

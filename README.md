# Online Retail Business Insights

This repository contains an end-to-end data analysis and visualization project focused on deriving actionable business insights from online retail transaction data.  
The project demonstrates how clean data and effective visual analytics can support executive decision-making across forecasting, marketing, customer retention, and expansion strategies.

---

## Business Objectives & Scope

- Provide data-driven insights to support strategic decision-making for senior leadership  
- Analyze revenue trends, customer value, and regional performance using transactional data  
- Exclude the United Kingdom from selected analyses to focus on international markets and expansion opportunities, as the UK represents a mature and well-established market  
- Identify high-growth regions, high-value customers, and seasonal demand patterns  

---

## Dataset

- **Name:** Online Retail Dataset  
- **Source:** UCI Machine Learning Repository  
- **Records:** ~541,000 transactional entries  
- **Format:** Excel (.xlsx)  

The dataset contains information such as invoice dates, customer IDs, countries, quantities, and unit prices, enabling comprehensive sales and demand analysis.

---

## Data Cleaning & Preparation

To ensure reliable and accurate analysis, the following data quality steps were performed:

- Removed returned transactions where **Quantity < 1**  
- Removed invalid records where **Unit Price < 0**  
- Created a derived **Revenue** metric using:  
Revenue = Quantity × Unit Price

Only clean and valid sales transactions were used for analysis.

---

## Key Business Questions Addressed

1. What are the monthly revenue trends and seasonal patterns?  
2. Which international markets generate the highest revenue and sales volume?  
3. Who are the top revenue-generating customers?  
4. Which regions show strong product demand and potential for expansion?  

---

## Key Insights

- Identified clear seasonal revenue trends useful for forecasting and planning  
- Highlighted top-performing international markets outside the UK  
- Found that a small group of customers contributes a significant share of total revenue  
- Identified high-demand regions that present strong expansion opportunities  

---

## Tools & Technologies

- **Power BI** – Data cleaning, transformation, and visualization  
- **Microsoft Excel** – Dataset format  
- **Microsoft PowerPoint** – Executive presentation  

---

## Repository Structure
├── data/
│ └── Online_Retail.xlsx
│
├── powerbi/
│ └── Final_Report.pbix
│
├── presentation/
│ └── Online_Retail_Business_Insights.pptx
│
└── README.md

---

## Video Presentation

A short video presentation explaining the analysis approach, visuals, and key insights is available here:

▶️ **Watch the presentation:**  
https://www.youtube.com/watch?v=RIqOeSfJwXo

---

## Conclusion

This project demonstrates the ability to transform raw transactional data into meaningful business insights using structured data cleaning, thoughtful visualization, and executive-focused storytelling.  
The analysis supports data-driven decisions related to growth, customer strategy, and international expansion.


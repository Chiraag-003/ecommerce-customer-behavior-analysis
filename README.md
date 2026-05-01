 📊 Customer Revenue & Behavior Analysis Dashboard

🎯 Objective
To analyze customer purchasing patterns and identify key revenue drivers in an e-commerce dataset, enabling data-driven business decisions.

👉 This project helps businesses identify revenue drivers and optimize product strategy for better profitability.

📊 Dashboard Preview

![Dashboard](images/dashboard.png)

🎯 Business Questions

1. Which products contribute the most to total revenue?
2. Which regions drive the highest sales performance?
3. What are the characteristics of high-demand products?
4. Which products show strong repeat purchase patterns?
5. Where is revenue being lost despite high demand?

📊 Key Metrics

• Total Revenue: ₹X  
• Total Orders: X  
• Top Category: Electronics (X%)  
• Top Region: West (X%)  
• Top Product: [Product Name]  

🔄 Workflow

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Business Insights Generation  
4. Dashboard Visualization (Power BI)  
5. Recommendations for decision-making  

🧾 Dataset Overview

The dataset contains transaction-level data including:

- Order Date  
- Product Name  
- Category  
- Region  
- Quantity  
- Sales  
- Profit  

 🔍 Analysis Performed

 1. Repeat Purchase Analysis
- Identified frequently purchased product-region combinations  
- Highlighted patterns indicating customer preferences  

 2. Purchase Frequency
- Measured total quantity sold per product  
- Identified high-demand products  

3. Revenue Analysis
- Top revenue-generating products  
- Revenue contribution by category  
- Regional sales performance  

 📈 Key Insights

• A small group of products contributes the majority of total revenue (Pareto effect)  
• High-demand products do not always generate high revenue, indicating pricing inefficiencies  
• West region contributes the highest share of total revenue  
• Certain product-region combinations show strong repeat purchase behavior  
• Revenue distribution varies significantly across categories  

💡 Business Recommendations

• Focus marketing and inventory on top 20% revenue-driving products  
• Optimize pricing for high-demand but low-revenue products  
• Expand operations in high-performing regions like West  
• Use repeat purchase insights for targeted marketing campaigns  
• Improve inventory planning using demand trends  

🤖 Optional ML Extension

A simple classification model can be built to identify high-revenue products using:

- Features: Quantity, Category, Region  
- Model: Random Forest  
- Objective: Predict high-value products  

🛠️ Tools & Technologies

- Python (Pandas, Matplotlib)  
- Power BI  
- Jupyter Notebook  

📁 Project Structure

ecommerce-customer-behavior-analysis/
│  
├── data/                # Dataset used for analysis  
├── notebooks/           # Jupyter notebooks (EDA & analysis)  
├── images/              # Dashboard and visualizations  
├── README.md            # Project documentation  
└── final_report.md      # Detailed report  

🚀 Conclusion

This project demonstrates how raw transactional data can be transformed into actionable insights that help businesses:

- Increase revenue  
- Improve customer targeting  
- Optimize product strategy  

⚠️ Note

The original dataset was large; a sample dataset is included for reproducibility.

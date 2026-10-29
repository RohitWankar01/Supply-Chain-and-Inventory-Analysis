# 📦 Supply Chain and Inventory Analysis


# 📌 Project Overview

- This project focuses on analyzing supply chain and inventory data to understand product revenue, manufacturing costs, supplier lead times, shipping expenses, inventory levels, and transportation routes.
- It demonstrates an exploratory data analysis (EDA) workflow using Python, Pandas, Matplotlib, and Seaborn.
- The analysis aims to identify business patterns and generate insights that can support inventory planning and supply chain decision-making.

# 🎯 Project Objectives

- Understand and inspect supply chain data.
- Check missing values, duplicate records, and data types.
- Perform Exploratory Data Analysis (EDA).
- Analyze revenue and manufacturing costs across product categories.
- Compare transportation costs and supplier lead times.
- Explore order quantities, stock levels, and sales relationships.
- Visualize patterns and generate business recommendations.

# 🛠️ Skills & Tools Used

- Python
- Pandas
- NumPy
- Data Inspection and Quality Checks
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Business Insight Generation
- Google Colab

# 📂 Dataset Information

**Dataset Name:** Supply Chain Data  
**Total Records:** 100  
**Total Columns:** 24  
**Data Type:** Structured tabular data

**Key Features:**

- **Product Information:** Product type, SKU, price
- **Sales Information:** Number of products sold, revenue generated
- **Inventory Information:** Stock levels, availability, order quantities
- **Supplier Information:** Supplier name, location, lead times
- **Manufacturing Information:** Production volumes, manufacturing costs, defect rates
- **Shipping Information:** Shipping times, shipping costs, carriers, transportation modes

# 🔍 Project Workflow

## 1️⃣ Data Loading & Understanding

- Loaded the dataset using Pandas.
- Examined the dataset shape, column names, data types, and summary statistics.
- Inspected the initial records and numerical features.

## 2️⃣ Data Quality Checks

- Checked for missing values.
- Checked for duplicate records.
- Examined unique values in categorical columns.
- Reviewed data types and numerical summaries.

## 3️⃣ Exploratory Data Analysis (EDA)

EDA was performed using Matplotlib and Seaborn through the following analyses:

1. Total revenue by product type
2. Manufacturing cost variation across product types
3. Relationship between price and revenue generated
4. Average shipping costs by transportation mode
5. Supplier lead-time comparison
6. Distribution of order quantities
7. Relationship between stock levels and products sold
8. Frequency of supply chain routes
9. Correlation between numerical variables

## 4️⃣ Data Visualization

- Bar charts for category comparisons
- Box plots for manufacturing cost distributions
- Scatter plots for relationships between numerical variables
- Histograms for order quantity distributions
- Pie charts for route frequency
- Correlation heatmaps for numerical variables

## 5️⃣ Business Insights & Recommendations

- Interpreted visualization results.
- Identified areas for further investigation.
- Developed recommendations related to revenue, cost management, transportation, supplier monitoring, and inventory planning.

# 📊 Key Insights

1. **Revenue:** Skincare generated the highest total revenue among the product categories, while cosmetics generated the lowest.
2. **Manufacturing Costs:** Skincare showed wider variation in manufacturing costs than haircare.
3. **Price and Revenue:** The scatter plot showed no clear relationship between product price and revenue generated.
4. **Transportation Costs:** Air transportation had the highest average shipping cost, while sea transportation had the lowest.
5. **Supplier Lead Times:** Supplier 4 had the longest average lead time, while Supplier 3 had the shortest.
6. **Order Quantities:** Order quantities varied across the dataset.
7. **Inventory and Sales:** Stock levels and the number of products sold showed no clear relationship in the scatter plot.
8. **Routes:** Route A had the highest frequency among the routes analyzed.
9. **Correlation:** Most numerical variables showed weak linear correlations, although some moderate relationships were present.

# 📈 Business Recommendations

1. **Revenue Optimization:** Investigate the factors contributing to skincare's higher revenue.
2. **Cost Management:** Examine manufacturing cost variation to identify possible opportunities for cost control.
3. **Transportation Planning:** Compare shipping costs with delivery requirements before selecting transportation modes.
4. **Supplier Monitoring:** Review Supplier 4's lead times and investigate possible operational improvements.
5. **Inventory Planning:** Consider stock levels, sales patterns, and replenishment requirements together.
6. **Further Analysis:** Use additional historical data to investigate demand trends, supplier reliability, and product quality.

# ⚠️ Limitations & Assumptions

## Limitations

- The dataset contains only 100 records, which may limit how widely the findings can be generalized.
- The analysis does not establish long-term trends or seasonality.
- Correlation does not establish causation.
- The project does not include demand forecasting or predictive modelling.
- Supplier performance is primarily compared using lead times rather than a comprehensive reliability assessment.

## Assumptions

- The supplied dataset is sufficiently representative for this exploratory analysis.
- The recorded values are assumed to be accurate for the purpose of the analysis.
- Observed patterns are treated as findings within this dataset, not as universal supply chain rules.

# 🏁 Conclusion

This project demonstrates how Python-based exploratory data analysis can be used to examine supply chain and inventory operations.

The analysis explored product revenue, manufacturing costs, shipping expenses, supplier lead times, order quantities, stock levels, route usage, and numerical correlations.

The findings highlight areas that may benefit from further investigation, including manufacturing cost variation, transportation expenses, supplier lead times, and inventory planning.

Overall, the project strengthened practical skills in data inspection, exploratory analysis, visualization, and business insight generation.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Supply Chain Analytics and Inventory Management  
**Language:** Python  
**Environment:** Google Colab

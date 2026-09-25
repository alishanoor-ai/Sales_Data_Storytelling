# 📊 Sales Data Storytelling

This project presents an end-to-end **Sales Data Analysis and Storytelling** workflow using Python. The analysis focuses on identifying sales trends, understanding category and product performance, exploring pricing patterns, and generating meaningful business insights.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## 📁 Project Files

* `Sales_Data_Storytelling_Final_Project.ipynb` — Complete analysis notebook
* `sales_data (1).csv` — Dataset used for the analysis
* `graph 1.png` — Monthly revenue analysis
* `graph 2.png` — Revenue by category
* `graph 3.png` — Units sold by category
* `graph 4.png` — Units sold by product
* `graph 5.png` — Actual vs predicted revenue

## 🔍 Analysis Performed

The project covers:

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Monthly revenue analysis
5. Category-wise revenue analysis
6. Category-wise sales volume analysis
7. Product performance analysis
8. Average price analysis
9. Price and revenue correlation
10. Data visualization
11. Business insights and recommendations
12. Linear Regression modeling
13. Model evaluation

## 📈 Visualizations

### 1. Monthly Revenue Trend

![Monthly Revenue](graph%201.png)

### 2. Revenue by Category

![Revenue by Category](graph%202.png)

### 3. Units Sold by Category

![Units Sold by Category](graph%203.png)

### 4. Units Sold by Product

![Units Sold by Product](graph%204.png)

### 5. Actual vs Predicted Revenue

![Actual vs Predicted Revenue](graph%205.png)

## 💡 Key Findings

* **December** recorded the highest monthly revenue, while **April** recorded the lowest.
* **Electronics** was the highest revenue-generating category.
* Electronics also recorded the highest sales volume.
* **Wireless Earbuds** were the highest-selling individual product, with more than 600 units sold.
* Electronics had the highest average product price, at more than 80.
* Price and revenue showed a strong positive relationship, with a correlation of approximately **0.78**.

## 🤖 Predictive Modeling

A **Linear Regression** model was used to estimate revenue based on:

* Units Sold
* Price

### Model Performance

* **R² Score:** 0.91
* **Mean Absolute Error (MAE):** 493.49
* **Mean Squared Error (MSE):** 361,404.31

The model demonstrates the machine learning workflow and the relationship between the selected variables and revenue. Since revenue is directly related to price and units sold in this dataset, the model should be interpreted as a demonstration rather than an independent future-sales forecasting system.

## 💼 Business Recommendations

### 1. Focus on High-Performing Categories

Electronics generates high revenue and sales volume. The business should continue monitoring demand and maintain sufficient inventory.

### 2. Monitor High-Performing Products

Wireless Earbuds have the highest sales volume. The business can analyze the factors contributing to their strong performance.

### 3. Investigate Lower-Performing Products

Products with comparatively lower sales and revenue can be reviewed based on pricing, customer demand, product variety, and marketing activity.

### 4. Plan Around Monthly Trends

Monthly revenue trends can help with inventory planning and marketing activities during periods of higher demand.

### 5. Consider Both Price and Sales Volume

Revenue depends on both product price and units sold. Pricing decisions should therefore be evaluated together with sales volume.

## 🎯 Conclusion

This project demonstrates how Python can be used to transform raw sales data into meaningful business insights.

The analysis combines **data cleaning, exploratory data analysis, visualization, statistical analysis, business recommendations, and predictive modeling** to provide a complete sales data storytelling workflow.

---

**Author:** Alisha Noor
**Field:** Software Engineering | Aspiring Data Analyst

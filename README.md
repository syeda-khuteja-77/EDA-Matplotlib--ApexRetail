# 📊 Sales Data Analysis Using Python & Matplotlib

## 🚀 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** using Python to analyze retail sales data and uncover meaningful business insights through data visualization.

Using the Apex Retail US dataset, I explored sales performance across different regions, product categories, cities, and payment methods. With **Pandas and Matplotlib**, I transformed raw sales data into visual insights that help understand business performance and customer payment preferences.

## 🎯 Project Objectives

- 📍 Identify the region generating the highest sales.
- 🛍️ Determine which product category contributes the most revenue.
- 📈 Understand the distribution of sales values.
- 💳 Analyze the distribution of different payment methods.
- 🏙️ Compare sales performance across cities.
- 📊 Present findings through clear and easy to understand visualizations.

## 🛠️ Tools & Technologies

- 🐍 **Python** – Data analysis and programming
- 🐼 **Pandas** – Data loading, grouping, and aggregation
- 📉 **Matplotlib** – Data visualization and chart creation
- ☁️ **Google Colab** – Cloud based coding and execution
- 📁 **Excel** – Source dataset

## 🔍 Project Workflow

1. **Import Libraries:** Imported Pandas and Matplotlib.
2. **Load the Dataset:** Uploaded and loaded the Excel dataset into a Pandas DataFrame.
3. **Explore the Data:** Examined the initial records and dataset structure.
4. **Analyze Sales:** Grouped sales data by region, category, and city.
5. **Visualize Results:** Created bar charts, a histogram, and a pie chart.
6. **Interpret Findings:** Used the charts to answer business related questions.

## 📊 Key Analysis & Insights

### 1️⃣ Sales by Region

**Visualization:** Bar Chart

Compared total sales across the East, Midwest, South, and West regions.

💡 **Key Insight:** The West region generated the highest sales, followed by the East region.

### 2️⃣ Sales by Product Category

**Visualization:** Bar Chart

Analyzed sales across Electronics, Furniture, and Office Supplies.

💡 **Key Insight:** Office Supplies generated the highest revenue among the three product categories.

### 3️⃣ Sales Distribution

**Visualization:** Histogram

Examined how sales values are distributed across the dataset.

💡 **Key Insight:** Sales values are unevenly distributed, with more observations at lower sales values and fewer observations at higher values.

### 4️⃣ Payment Mode Distribution

**Visualization:** Pie Chart

Analyzed the proportion of transactions made using Cash, Debit Card, Credit Card, and PayPal.

💡 **Key Insight:** Cash accounted for 27% of transactions, PayPal for 26%, Credit Card for 24%, and Debit Card for 23%. The distribution is relatively balanced, with Cash being the most frequently used payment method.

### 5️⃣ Sales by City

**Visualization:** Bar Chart

Compared total sales across Chicago, Houston, Los Angeles, New York, and Phoenix.

💡 **Key Insight:** New York generated the highest sales among the five cities, while Houston generated the lowest.

## 📚 Python Concepts Practiced

- Importing Python libraries
- Loading Excel files using `pd.read_excel()`
- Exploring datasets using `df.head()`
- Grouping data using `groupby()`
- Aggregating sales using `sum()`
- Counting categories using `value_counts()`
- Creating bar charts using `plot(kind="bar")`
- Creating histograms using `plt.hist()`
- Creating pie charts using `plot(kind="pie")`
- Adding chart titles and axis labels
- Interpreting visualizations to answer business questions

## ▶️ How to Run This Project

You can run this project using Google Colab without installing Python on your computer.

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the project notebook (`EDA-Matplotlib.ipynb`) if you have it saved.
3. Upload the Excel dataset named `Apex_Retail_Business_US_Clean.xlsx`.
4. Run the notebook cells in sequence.
5. Explore the generated charts and business insights.

### 📦 Required Libraries

```python
import pandas as pd
import matplotlib.pyplot as plt
```

These libraries are commonly available in Google Colab.

## 💼 Business Value

This project demonstrates how Python can be used to turn retail sales data into actionable business insights.

The analysis helps identify high performing regions, understand category level revenue, compare city performance, and explore customer payment preferences. These findings can support further investigation into sales strategy and business performance.

## 🌱 Learning Journey

This project is part of my journey in learning **Python for Data Analytics**. It helped me practice Pandas operations, build visualizations with Matplotlib, and connect technical analysis with real business questions.

I am continuing to strengthen my skills in data analysis, visualization, and insight generation through hands on projects.

## 🤝 Connect With Me

I welcome feedback, suggestions, and opportunities to learn from the data analytics community.

⭐ If you find this project useful, feel free to star the repository!

#Python #DataAnalytics #Pandas #Matplotlib #EDA #DataVisualization #LearningByDoing

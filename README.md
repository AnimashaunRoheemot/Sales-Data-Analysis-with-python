# 🛒 Sales Data Analysis with Python  

## 📑 Table of Contents  
1. [Project Overview](#-project-overview)  
2. [Objectives](#-objectives)  
3. [Dataset Description](#-dataset-description)  
4. [Data Cleaning Steps](#-data-cleaning-steps)  
5. [Exploratory Data Analysis](#-exploratory-data-analysis)  
6. [Business Questions & Solutions](#-business-questions--solutions)  
7. [Tools & Libraries](#-tools--libraries)   
8. [Project Files](#-project-files)  
9. [Conclusion](#-conclusion)
10. [Author](#-author)  

---

## 📌 Project Overview  
This project demonstrates my Python data analysis skills using Pandas and Matplotlib.  
The dataset contains random sales records, and the goal is to simulate the responsibilities of a data analyst by cleaning messy data, performing exploratory data analysis (EDA), and extracting actionable business insights.  

---

## 🎯 Objectives  
- Import the dataset into a Pandas DataFrame and explore its structure.  
- Clean the data by handling missing values, removing duplicates, fixing formatting issues, and converting columns to appropriate data types.  
- Perform exploratory analysis with descriptive statistics and aggregation.  
- Answer key business questions using Python and Pandas.  

---

## 📂 Dataset Description  
The dataset contains sales transaction records with details such as:  
- Order ID  
- Product Name  
- Quantity Sold  
- Revenue  
- Payment Method  
- City  
- Manager  
- Date  

---

## 🧹 Data Cleaning Steps  
1. Imported the dataset into a Pandas DataFrame.  
2. Checked for missing values and handled them.  
3. Removed duplicates to ensure accuracy.  
4. Fixed formatting issues (extra spaces).  
5. Converted columns to their appropriate data types.  

---

## 🔍 Exploratory Data Analysis  
Performed descriptive statistics and group-wise summaries to understand:  
- Distribution of revenue and quantity  
- Preferred payment methods  
- Top-selling products  
- Revenue trends across time and regions  

---

## 💡 Business Questions & Solutions  

Q1. What was the most preferred payment method?  
- Answer: Credit Card (120 records)  
- ![Payment Method](images/q1_payment_method.png)  

Q2. Which was the most selling product?  
- By Quantity → Beverages  
- By Revenue → Burgers  
- ![Top Products](images/q2_top_products.png)  

Q3. Which City and Manager earned maximum revenue?  
- City: Lisbon  
- Manager: Joao Silva  
- ![City and Manager Revenue](images/q3_city_manager.png)  

Q4. What was the Average Revenue?  
- 3029.58 (rounded to 2 decimal places)  
- ![Average Revenue](images/q4_avg_revenue.png)  

Q5. What was the Average Revenue for November & December?  
- November → 2939.05  
- December → 3102.12  
- ![Nov Dec Revenue](images/q5_nov_dec_revenue.png)  

Q6. What is the Standard Deviation of Revenue and Quantity?  
- Revenue → 2420.1  
- Quantity → 214.8  
- ![Standard Deviation](images/q6_std_dev.png)  

Q7. What is the Variance of Revenue and Quantity?  
- Revenue → 5,857,001.1  
- Quantity → 46,177.5  
- ![Variance](images/q7_variance.png)  

Q8. Was the Revenue Increasing or Decreasing Over Time?  
- Revenue starts relatively low in early November, with a big spike in mid-November.  
- It fluctuates afterward but gradually increases through December, ending on an upward trend.  
- ![Revenue Trend](images/q8_revenue_trend.png)  

Q9. What is the Average Quantity Sold & Average Revenue per Product?  
- ![Avg per Product](images/q9_avg_product.png)  

Q10. What was the Total Number of Orders?  
- 254 Orders  
- ![Total Orders](images/q10_total_orders.png)

  ## 🛠 Tools & Libraries  
- Python  
- Pandas – for data cleaning, manipulation, and analysis  
- Matplotlib – for data visualization  

---

## 📂 Project Files  
- sales_analysis.ipynb → Full Jupyter Notebook with code & outputs  
- sales_dataset.csv → Dataset (if shareable)  
- README.md → Project documentation  
- requirements.txt → Python dependencies  
   
   ---
   
## 📌 Conclusion
This project highlights how Python can be used to:
	•	Clean messy data
	•	Perform descriptive & statistical analysis
	•	Answer business questions
	•	Visualize insights for decision-making

 ---

 ## 👩 Author
 Animashaun Roheemot 
 
 🔗linkedln : https://www.linkedin.com/in/animashaun-roheemot

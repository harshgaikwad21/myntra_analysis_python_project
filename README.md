# myntra_analysis_python_project
![image](https://etimg.etb2bimg.com/photo/99462008.cms)
[CLICK HERE FOR KAGGLE CODE](https://www.kaggle.com/code/harshgaikwad1211/myntra-analysis?scriptVersionId=267019443)
# 🧾 Project Overview

Myntra Sales Data Analysis explores the pricing, discount, brand, and rating trends across fashion products on Myntra, one of India’s top e-commerce fashion platforms.
The project performs data cleaning, exploratory analysis, and visualization to uncover how brands price their products, how discounts are structured, and what patterns exist in customer ratings.

# 🗂️ Dataset Details

The dataset contains product-level details scraped from Myntra’s website, including:

- **Brand name**

- **Product type**

- **Price**

- **MRP (Maximum Retail Price)**

- **Discount percentage**

- **Ratings** and **Number of ratings**

The analysis helps in identifying:

- Popular brands and product categories

- Pricing behavior across brands

- Discounting strategies used on the platform

 # 🧹 Data Cleaning Process

The notebook includes a step-by-step cleaning pipeline:

1. **Removing Duplicates** – Ensures unique product listings.  
2. **Handling Missing Values** – Drops or imputes incomplete records.  
3. **Outlier Detection (IQR method)** – Removes extreme `price` and `MRP` values for realistic insights.  
4. **Data Type Conversion** – Converts columns like `price` and `ratings` into proper numeric formats.  

# 📊 Data Visualization & Insights

## 💰 Price Distribution

- The price distribution is **right-skewed**, meaning most products are **low-to-mid range**.  
- **Typical cluster:** ₹800–₹2,000 → Myntra’s **mass-market pricing zone**.  
- A small portion of **high-priced items (>₹10,000)** represents **premium brands**.
 
<img width="987" height="490" alt="image" src="https://github.com/user-attachments/assets/005a1599-d72c-4eb3-b8a3-bdbdde2f1e6b" />


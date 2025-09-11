# Amazon-Fashion-Sales - EDA-Analysis
---

## Executive Summary
[View the full Business Summary (PDF)](reports/Amazon_Fashion_Analysis_Summary.pdf)

This project applies Exploratory Data Analysis (EDA) to an Amazon Fashion Products dataset (~13,000 products, cleaned to 1,787 usable rows).  

The goal for this project is to uncover key trends in brands, pricing, categories, and ratings to help Amazon fashion sellers and buyers make data-driven decisions.

---

## 🔑 Key Findings (Brief Preview)
- **Ratings per Brand** – 
- **Most-Loved Fashion** – This category holds the highest average rating
- **Price Distribution** – 75 % of products are priced below \$188; one \$26k item is a clear outlier.  
- **Price vs. Rating** – Correlation ≈ 0.03, indicating no meaningful relationship between price and rating.

> Full details are in the  
> [Executive Summary PDF](reports/Amazon_Fashion_Analysis_Summary.pdf).

---

## 💡 Business Strategies (Highlights)
- Prioritize **bag-related products** as a primary Amazon sales channel.  
- Focus on the **Most-Loved Fashion** category to capture strong consumer demand.  
- Maintain **competitive, mid-range pricing** since higher prices do not drive higher ratings.  
- Protect and **maintain high customer ratings**, as the marketplace is already saturated with well-rated competitors.

---

## 🖼️ Visual Highlights
Key charts supporting these findings are stored in the [`/images`](images) folder and shown below:

| Chart | Description |
|-------|------------|
| ![Top Categories by Average Rating](images/top_categories_by_rating.png) | Ten highest-rated product categories |
| ![Top Brands by Average Rating](images/top_brands_by_rating.png) | Leading brands by average rating |
| ![Price Distribution](images/price_distribution_boxplot.png) | Market dominated by mid-range pricing |
| ![Price vs Rating Correlation](images/price_rating_correlation.png) | Minimal relationship between price and ratings |

*(More plots are available inside the notebook.)*

---

## 🧮 Data & Methods
- **Dataset** – Cleaned to 1,787 rows and 4 key variables: `brand`, `price`, `category`, and `rating`.  
- **Cleaning Steps** – Standardized column names, converted numeric fields, and removed missing or invalid values.  
- **Tools** – Python, Pandas, NumPy, Matplotlib, Seaborn.  
- **Notebook** – See [`notebooks/amazon_fashion_eda.ipynb`](notebooks/amazon_fashion_eda.ipynb) for full EDA workflow.

---

## 🔜 Next Steps
- **Quantify key metrics** – Extract KPIs such as category growth rates, review volumes, and price–rating relationships to measure the trends discovered in the initial EDA.  
- **Cross-platform comparison** – Perform EDA on other e-commerce platforms (e.g., Walmart, eBay) to benchmark category and brand performance as well as pricing strategies.

---

## 📂 Repository Structure


**Author:** Jakob Sarmiento  
**Date:** September 10, 2025  

## Overview
This project applies Exploratory Data Analysis (EDA) to an Amazon Fashion dataset (~13,000 original rows, cleaned to 1,787 usable rows).  
The goal is to uncover key trends in product brands, pricing, categories, and ratings to provide actionable insights for both Amazon fashion sellers and buyers.

---

## Key Findings
- **Ratings Per Brand** – Six of the ten highest-rated brands are bag companies, confirming that bags consistently earn stronger customer reviews than other fashion products.  
- **Product Pricing** – The majority of products are priced below the high-end mark; only one product reaches \$26,000, making it a clear outlier.  
- **Rating Distribution** – Most fashion products receive high ratings, between 4.0 and 5.0 stars.  
- **Price vs Rating** – Correlation ≈ 0.03, indicating no meaningful relationship between price and customer rating.

---

## Business Strategies for Amazon Fashion Sellers
- **Prioritize Bag-Related Products** – Bag companies should treat Amazon as a primary sales channel, given their consistently strong customer reviews and growing popularity.  
- **Focus on the *Most-Loved Fashion* Category** – This category holds the highest average customer rating on Amazon and offers strong growth potential.  
- **Maintain Competitive, Mid-Range Pricing** – Since non-luxury products dominate and higher prices do not drive higher ratings, competitive pricing is key.  
- **Protect Customer Ratings** – Fashion sellers should maintain consistently high ratings in a marketplace already saturated with well-rated competitors.

---

## Visual Highlights
Key charts supporting the findings are stored in the [`/images`](images) folder and displayed below:

| Chart | Description |
|-------|------------|
| ![Top Categories by Average Rating](images/top_categories_by_rating.png) | Shows the 10 highest-rated product categories |
| ![Top Brands by Average Rating](images/top_brands_by_rating.png) | Highlights bag brands leading in customer satisfaction |
| ![Price Distribution](images/price_distribution_boxplot.png) | Displays market dominance of mid-range pricing |
| ![Price vs Rating Correlation](images/price_rating_correlation.png) | Confirms negligible relationship between price and ratings |

*(Additional visualizations are available in the Jupyter notebook.)*

---

## Data & Methods
- **Dataset** – Cleaned to 1,787 rows and 4 key variables: `brand`, `price`, `category`, and `rating`.  
- **Data Cleaning** – Standardized column names, coerced `price` and `rating` to numeric, and removed missing or invalid values.  
- **Tools & Libraries** – Python, Pandas, NumPy, Matplotlib, Seaborn.  
- **Notebook** – See [`notebooks/amazon_fashion_eda.ipynb`](notebooks/amazon_fashion_eda.ipynb) for full EDA workflow.

---

## Next Steps
- **Quantify Key Metrics** – Extract KPIs such as category growth rates, review volumes, and price–rating relationships to measure the trends discovered in the initial EDA.  
- **Cross-Platform Analysis** – Perform EDA on other e-commerce platforms (e.g., Walmart, eBay) to compare category performance, brand performance, and pricing strategies.

---
# Amazon Fashion Product & Sales Analysis

**Author:** Jakob Sarmiento  
**Date:** September 10, 2025

---

## 📄 Executive Summary (PDF)
[➡️ View/Download the full Executive Summary](reports/Amazon_Fashion_Analysis_Summary.pdf)

This PDF contains the complete business summary, key findings, business strategies, and next steps.

---

## 📝 Quick Project Overview
This project applies Exploratory Data Analysis (EDA) to an Amazon Fashion dataset (~13,000 original rows, cleaned to 1,787 usable rows).  
The goal is to uncover key trends in product brands, pricing, categories, and ratings to guide fashion sellers and buyers on Amazon.

---

## 🔑 Key Findings (Brief Preview)
- Six of the ten highest-rated brands are bag companies, confirming strong customer preference for bags and luggage.  
- *Most-Loved Fashion* is the highest-rated category (~4.42 stars).  
- 75 % of products are priced below \$188; one \$26k item is a clear outlier.  
- Correlation between price and rating is negligible (~0.03).

*(Full details and visuals are in the [Executive Summary PDF](reports/Amazon_Fashion_Analysis_Summary.pdf) and the notebook.)*

---

## 🚀 Repository Structure

## Repository Structure

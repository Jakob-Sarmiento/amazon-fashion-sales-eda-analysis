# Amazon Fashion Sales - EDA Analysis
---

## Executive Summary
[Full Business Summary (PDF)](amazon_product_business_summary.pdf)

This project applies Exploratory Data Analysis (EDA) to an Amazon Fashion Products dataset.

The goal for this project is to uncover key trends in brands, pricing, categories, and ratings to help Amazon fashion sellers and buyers make data-driven decisions.

---

## Preview of Key Findings 
- **Categories** – The Most-Loved Fashion category holds the highest average rating and one of the largest numbers of product listings in the dataset.
- **Price Distribution** – The majority of Amazon fashion products fall in the lower- to mid-price range and are not considered high-end.
- **Price vs. Rating** – Correlation ≈ 0.03, there is no relationship between price and rating.
  
<sub>[Link to full PDF here](https://docs.google.com/document/d/1aAeRWxviAThdUz9Ko7ORaX9TiR3n9DybboqM-VBc42M/edit?usp=sharing)</sub>

--- 

## Business Strategies and Recommendations (Preview)

- **Pricing** - Sellers on Amazon should prioritize low to mid end prices, considering most fashion products are not high-end on Amazon, in terms of pricing.
- **Prioritization** - Companies selling bags should prioritize Amazon as one of their main channels, as bags are highly rated on Amazon.

---

## Visual Highlights

| Type of Visualization | Description |
|-----------------------|-------------|
| [Correlation Heatmap](images/correlation_heatmap_price_rating.png) | Minimal relationship between price and ratings |
| [Price Distribution Histogram](images/price_distribution.png) | Market dominated by low to mid-range pricing |
| [Ratings per Category Boxplot](images/rating_distribution_per_cat.png) | Most categories are rated between 4.0 and 5.0 stars |




## Data & Methods
- **Dataset** – Cleaned around 1,800 rows
- **Tools** – Python, Pandas, NumPy, Matplotlib, Seaborn.  
- **Notebook** – See [`03_amazon_fashion_sales_eda_analysis.ipynb`](03_amazon_fashion_eda.ipynb) for full EDA workflow.

---

## Next Steps
- **Track exact numbers** – Extract KPIs including category growth rates, review volumes, and price–rating relationships to measure the trends discovered in the initial EDA.  
- **E-commerce platform comparison** – Perform EDA on other e-commerce platforms to compare category and product performance.


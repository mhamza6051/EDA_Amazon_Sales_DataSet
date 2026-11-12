# EDA — Amazon Sales Dataset

Exploratory analysis of an Amazon product-sales dataset (**1,465 products × 16 features**), centred on pricing, discounts and ratings: **what gets discounted, what gets rated well, and do the two meet?**

## What the notebook explores

- **Data quality** — dimensions, dtypes, missing-value audit and resolution, summary statistics
- **Pricing** — distribution of discounted vs. actual price; discount-percentage distribution
- **Categories** — product distribution by category; average discount, average rating and average discounted price **per category**
- **Ratings** — rating distribution, average rating and rating-count patterns; the most common rating counts
- **Correlations** — rating vs. rating count vs. discounted price
- **Product rankings** — top-rated products with high rating counts, and top-rated products with the **highest discounts**
- One question is flagged honestly in the notebook: true "top-selling" products can't be ranked because the dataset has **no units-sold column**

## Dataset

Amazon product listings: product name, category, actual and discounted price, discount percentage, rating, rating count and product details (1,465 rows; 1,463 after cleaning).

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn

## Run it

```bash
jupyter notebook EDA_Amazon_Sales_Dataset.ipynb
```

## Author

**Muhammad Hamza** — Data Scientist · [GitHub @mhamza6051](https://github.com/mhamza6051)

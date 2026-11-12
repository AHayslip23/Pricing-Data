# Pricing Data

Cleaning, exploration and modeling of an electronics product pricing dataset with products sold by merchants such as Walmart and Best Buy. It looks at prices, weights, sale status, availability and shipping.

## Repository Contents

| File | Description |
|---|---|
| `Pricing Data.ipynb` | Full analysis: cleaning, EDA, linear regression and logistic regression |

## Commit History

### `8986002`: Upload of the pricing analysis notebook (2025-12-14)
- **Cleaning:**
  - dropped unneeded columns and renamed columns
  - removed "pounds" from the weight values and converted them to numbers
  - standardized inconsistent availability values
- **Feature engineering:** added flags for whether a product's weight, minimum price and maximum price are above average.
- **EDA:**
  - product availability
  - the top 10 merchants and shipping types
  - average min and max price and weight by sale status
  - the top 10 manufacturers by price and weight
  - Walmart's top products, categories and manufacturers
  - a Best Buy vs. Walmart comparison
- **Linear regression on weight:**
  - weight vs. max price: R² = 0.35
  - weight vs. min price: R² = 0.35
- **Logistic regression:** three classifiers that predict whether a product's weight, minimum price or maximum price is above average.

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

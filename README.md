# Instacart Market Basket Analysis

This repository contains an exploratory data analysis (EDA) notebook focused on the **Instacart Market Basket Analysis** dataset. The goal of this notebook is to understand customer purchasing behavior and extract useful insights to support recommendation systems and market strategy.

## 📘 Notebook Overview

The notebook `EDA.ipynb` includes:

* Data loading and inspection
* Summary statistics and missing value analysis
* Customer ordering patterns
* Product and aisle popularity
* Visualizations using `matplotlib` and `pandas`

## 📦 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib
```

Imports used:

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## 📂 Data

The dataset used is the **Instacart Market Basket Analysis** dataset. You can find it on [Kaggle](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data).

Typical files include:

* `orders.csv`
* `order_products_prior.csv`
* `products.csv`
* `aisles.csv`
* `departments.csv`

Make sure these files are available in the expected directory when running the notebook.

## 📈 Sample Visuals

The notebook generates plots to illustrate:

* Distribution of orders by day of week and hour of day
* Most commonly reordered products
* Frequency of purchases per department and aisle

## 🧠 Insights

Initial EDA reveals trends in consumer shopping habits, such as:

* Peak ordering hours
* Frequently reordered items
* Category-wise product preferences

These insights can be foundational for machine learning applications like personalized recommendations.

## 🔧 How to Use

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/instacart-eda.git
   ```

2. Navigate to the folder and open the notebook:

   ```bash
   jupyter notebook EDA.ipynb
   ```

3. Run all cells to reproduce the analysis.

## 📝 License

This project is open-source and available under the MIT License.

# U.S. Treasury Yield Curve Analysis & PCA

## 📌 Overview

This project analyzes historical **U.S. Treasury yields** to understand yield curve behavior, model the term structure of interest rates, and identify the major sources of variation in Treasury yields.

The analysis combines **financial data analysis, statistical modeling, and Principal Component Analysis (PCA)** using Python.

---

## 🎯 Objectives

The main objectives of this project were to:

* Explore historical U.S. Treasury yield data
* Analyze yield curves across different dates
* Calculate yield curve slopes and spreads
* Identify normal, flat, and inverted yield curves
* Model the yield curve using the **Nelson-Siegel model**
* Construct and analyze the covariance matrix
* Apply **Principal Component Analysis (PCA)**
* Determine the percentage of variance explained by each principal component
* Visualize patterns and relationships across Treasury maturities

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Nelson-Siegel Model**
* **Principal Component Analysis (PCA)**
* **Statistical & Financial Analysis**

---

## 📊 Project Analysis

### 1. Treasury Yield Curve

The project examines Treasury yields across different maturities and analyzes how the relationship between short-term and long-term interest rates changes over time.

The yield curve provides a useful way of understanding the market's expectations around interest rates and economic conditions.

### 2. Yield Curve Slope

The analysis uses the difference between Treasury maturities to measure the slope of the yield curve.

For example:

```text
Yield Curve Slope = 10-Year Yield − 2-Year Yield
```

The slope is used to classify the curve as:

* **Normal** — upward sloping
* **Flat** — yields are approximately equal
* **Inverted** — downward sloping

### 3. Nelson-Siegel Model

The **Nelson-Siegel model** was used to model the term structure of interest rates.

The model represents the yield curve using parameters associated with:

* **Level**
* **Slope**
* **Curvature**

This provides a mathematical framework for understanding how Treasury yields vary across maturities.

### 4. Principal Component Analysis

PCA was applied to standardized Treasury yields to identify the major factors driving variation across the yield curve.

The results showed:

| Component | Variance Explained |
| --------- | -----------------: |
| PC1       |             83.84% |
| PC2       |             14.85% |
| PC1 + PC2 |         **98.69%** |

The first two principal components therefore explained approximately **98.69% of the total variation** in the dataset.

---

## 🔎 Key Findings

* Treasury yield curves change considerably over time.
* The difference between short- and long-term yields provides an important measure of yield curve shape.
* The Nelson-Siegel model provides a useful framework for representing the term structure of interest rates.
* PCA significantly reduced the dimensionality of the Treasury yield dataset.
* The first two principal components captured approximately **98.69% of the total variation**.

---

## 💡 Key Skills Demonstrated

This project demonstrates my ability to:

* Work with financial time-series data
* Perform exploratory data analysis
* Calculate financial indicators
* Apply statistical techniques to financial data
* Implement mathematical models in Python
* Perform dimensionality reduction using PCA
* Interpret quantitative results
* Communicate financial insights using data visualization

---

## 📈 Future Improvements

Future extensions of this project could include:

* Forecasting Treasury yield movements
* Rolling-window PCA analysis
* Implementing the Nelson-Siegel-Svensson model
* Comparing Treasury yields with equity market performance
* Building an interactive financial dashboard
* Using PCA factors in financial forecasting or risk analysis

---

## 📂 Project Structure

```text
us-treasury-yield-curve-analysis/
│
├── US_Yields.csv
├── treasury_yield_curve_analysis.ipynb
├── README.md
│
└── images/
    ├── yield_curve.png
    ├── yield_spread.png
    ├── nelson_siegel.png
    └── pca_variance.png
```

---

## 👤 Author

**Dimien Brasana**

Data Analyst | Data Science | Financial Engineering

This project is part of my portfolio development at the intersection of **Data Analytics, Data Science, and Financial Engineering**.

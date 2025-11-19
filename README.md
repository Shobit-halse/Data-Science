# Practical 2 - Data Loading and Wrangling

## Overview
This practical covers fundamental data science skills including loading datasets from various sources and performing essential data wrangling operations using pandas and scikit-learn.

## Contents

### 2A - Loading Datasets
**Notebook:** `2A.ipynb`

Learn different methods to load and create datasets for machine learning projects.

**Topics:**
- Loading built-in datasets from scikit-learn (Digits dataset)
- Creating simulated datasets for regression, classification, and clustering
- Loading real-world data from CSV files
- Visualizing clustered data with matplotlib

**Key Libraries:** `sklearn.datasets`, `pandas`, `matplotlib`

---

### 2(B, C) - Data Wrangling
**Notebook:** `2(B, C).ipynb`  
**Dataset:** `Plane-Crashes.csv`

Master essential pandas operations for cleaning, transforming, and analyzing data.

**Topics:**
- **DataFrame Basics:** Creating, loading, exploring (head, tail, shape, describe)
- **Navigation:** Selecting rows/columns with iloc, conditional filtering
- **Data Manipulation:** Replacing values, renaming columns, setting index
- **Aggregation:** Min, max, sum, mean, count, unique values
- **Missing Data:** Identifying, filling, and dropping missing values
- **Grouping:** GroupBy operations, time-based resampling
- **Advanced Operations:** Looping, applying functions, concatenating, merging DataFrames

**Key Libraries:** `pandas`, `numpy`

---

## Datasets Used

| File | Description | Size |
|------|-------------|------|
| `Plane-Crashes.csv` | Historical aviation accident data | 28,536 records |
| Built-in datasets | Scikit-learn's digits, iris, etc. | Varies |
| Simulated data | Synthetically generated for practice | Custom |

---

## Learning Outcomes

By completing this practical, you will:
- ✅ Load data from multiple sources (CSV, built-in, simulated)
- ✅ Understand DataFrame structure and navigation
- ✅ Clean and preprocess messy real-world data
- ✅ Handle missing values effectively
- ✅ Perform grouping and aggregation operations
- ✅ Transform and reshape data for analysis
- ✅ Merge and combine multiple datasets

---

## Key Skills Developed

### Data Loading
- Working with different data formats
- Understanding dataset structure
- Creating synthetic data for testing

### Data Wrangling
- Filtering and selecting data
- Handling missing values
- Transforming data types
- Aggregating and summarizing
- Combining multiple data sources

---

## Files in This Practical

```
Practical2/
├── 2A.ipynb                    # Loading datasets
├── 2(B, C).ipynb              # Data wrangling
├── Plane-Crashes.csv          # Dataset
├── README_2A.md               # Detailed 2A documentation
├── README_2BC.md              # Detailed 2BC documentation
└── README_Practical2.md       # This file
```

---

## Quick Start

1. **Install required libraries:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```

2. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Start with 2A** to learn data loading, then move to **2(B, C)** for wrangling

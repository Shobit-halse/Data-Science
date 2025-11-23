# Data Science Practicals

A comprehensive collection of hands-on Python exercises covering fundamental to advanced data science concepts using real-world datasets.

## Overview

This repository contains practical implementations of essential data science techniques. Each practical demonstrates industry-standard approaches to data manipulation, analysis, preprocessing, and machine learning using Python and popular libraries.

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **scikit-learn** - Machine learning and preprocessing
- **Matplotlib** - Data visualization

## Repository Structure

```
Data-Science-Practicals/
├── Data Frames and Basic Data Pre-processing/
│   └── Data loading, wrangling, and basic preprocessing
├── Feature Scaling and Dummification/
│   └── Numerical preprocessing and categorical encoding
├── Logistic Regression and Decision Tree/
│   └── Classification models and evaluation
├── Principal Component Analysis (PCA)/
│   └── Dimensionality reduction techniques
└── README.md
```

Each practical folder contains:
- Jupyter notebooks with implementations
- Datasets (CSV files)
- Code demonstrating real-world applications

## Topics Covered

### 1. Data Frames and Basic Data Pre-processing
- Loading built-in datasets from scikit-learn
- Creating synthetic datasets for testing
- Reading CSV files and handling various data formats
- DataFrame operations and navigation
- Filtering and selecting data based on conditions
- Handling missing values (detection, deletion, imputation)
- Data transformation and cleaning
- Grouping and aggregation operations
- Time series resampling
- Merging and concatenating datasets

### 2. Feature Scaling and Dummification
- Feature scaling (MinMaxScaler, StandardScaler)
- Robust scaling for outlier handling
- Normalization (L1 and L2 norms)
- One-hot encoding for nominal features
- Ordinal encoding for ordered categories
- Multilabel encoding techniques
- Dictionary vectorization
- Missing categorical value imputation
- Handling imbalanced classes (weighting, sampling)

### 3. Logistic Regression and Decision Tree
- Building logistic regression models for binary classification
- Evaluating model performance (accuracy, precision, recall)
- Constructing decision tree models
- Interpreting decision rules for classification
- Confusion matrix and ROC curve analysis
- Model pruning and optimization
- Feature importance analysis

### 4. Principal Component Analysis (PCA)
- Dimensionality reduction techniques
- Feature extraction and transformation
- Variance analysis and component selection
- Visualizing high-dimensional data

## Datasets

The practicals use diverse real-world datasets including:
- Housing and demographic data
- Historical event records
- Music and entertainment data
- Apple quality assessment data
- Scikit-learn built-in datasets
- Synthetically generated data for testing

## Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

### Running the Notebooks

```bash
jupyter notebook
```

Navigate to the desired practical folder and open the notebook.

## Key Concepts

### Data Preprocessing Pipeline

1. **Load** - Import data from various sources
2. **Explore** - Understand structure, types, and distributions
3. **Clean** - Handle missing values and outliers
4. **Transform** - Scale numerical features, encode categorical variables
5. **Prepare** - Create ML-ready feature matrices

### When to Use What

**Scaling Techniques:**
- Use **MinMaxScaler** when you need bounded values (0-1)
- Use **StandardScaler** for normally distributed features
- Use **RobustScaler** when data contains outliers

**Encoding Techniques:**
- Use **One-hot encoding** for nominal categories (no order)
- Use **Ordinal encoding** for ordered categories (low/medium/high)
- Use **Label encoding** for target variables

**Missing Data:**
- **Delete** when data is abundant and missingness is random
- **Impute** when data is limited or missingness is systematic

## Learning Path

Follow the practicals in numerical order for a structured learning experience. Each practical builds upon concepts from previous ones, progressing from basic data operations to advanced preprocessing and machine learning techniques.

## Skills Developed

- Data manipulation with pandas
- Feature engineering and transformation
- Handling real-world messy data
- Preparing data for machine learning
- Understanding preprocessing best practices
- Working with different data types and formats
- Building and evaluating classification models
- Dimensionality reduction and feature extraction

## Applications

These techniques are fundamental for:
- Machine learning model preparation
- Data analysis and exploration
- Feature engineering for predictive models
- Data cleaning and quality improvement
- Handling production datasets
- Model evaluation and optimization

## Notes

- All notebooks include working code with real datasets
- Each practical builds upon previous concepts
- Code follows industry best practices
- Techniques are applicable to any dataset

---

**Author:** Shobit Halse
  
**Institution:** Sheth L.U.J. & Sir M.V. College Of Arts, Science & Commerce

---

## License

This project is for educational purposes.

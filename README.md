# Data Mining Project

This project focuses on applying data mining techniques including association rule mining, clustering, and classification.

## Overview

### Part 1: Association Rule Mining

- Analyzed frequency distribution of categorical features.
- Selected categorical columns with manageable unique values.
- Continuous features were considered for discretization.
- Applied **one-hot encoding** to convert data into binary format.
- Used **Apriori algorithm** for frequent itemset mining.

#### Minimum Support:
- Initial value: **5%**
- Adjusted based on number of generated patterns.

---

### Part 2: Clustering

#### Feature Selection:
- Used **correlation matrix** to select features with low correlation.

#### Methods Used:
- **K-Means Clustering**
- **Hierarchical Clustering**

#### Choosing Number of Clusters:
- Applied **Elbow Method**

#### Evaluation:
- Used **boxplots** to analyze distribution uniformity across clusters.

---

### Clustering Results

#### K-Means Summary:

| Cluster | Reviews | Size | Installs | Price |
|--------|--------|------|----------|-------|
| 0 | 2.19e+05 | 2.17e+07 | 7.12e+06 | 0.42 |
| 1 | 2.17e+02 | 4.90e+06 | 1.00e+04 | 389.99 |
| 2 | 1.99e+07 | 6.55e+07 | 4.94e+08 | 0.00 |

#### Hierarchical Clustering Summary:

| Cluster | Reviews | Size | Installs | Price |
|--------|--------|------|----------|-------|
| 0 | 1.60e+07 | 7.88e+07 | 1.00e+08 | 0.00 |
| 1 | 1.59e+07 | 5.64e+07 | 6.07e+08 | 0.00 |
| 2 | 2.17e+02 | 4.90e+06 | 1.00e+04 | 389.99 |
| 3 | 4.25e+05 | 5.80e+07 | 1.37e+07 | 0.28 |
| 4 | 1.01e+05 | 1.25e+07 | 4.90e+06 | 0.45 |

---

### Classification

- Selected features based on clustering results.
- Focused on features with **better distribution**.
- Compared different models to select the best performing classifier.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Mlxtend (Apriori)
- Matplotlib / Seaborn

---

## Author
Mehrsa Dehnavi

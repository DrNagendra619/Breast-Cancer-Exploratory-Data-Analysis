# Breast-Cancer-Exploratory-Data-Analysis
Breast Cancer Exploratory Data Analysis
# Breast Cancer Exploratory Data Analysis (EDA) 🎗️📊

## Overview

This repository contains a Jupyter Notebook dedicated to performing comprehensive **Exploratory Data Analysis (EDA)** on a breast cancer dataset. This project is foundational for any subsequent machine learning classification task, as it aims to understand the structure, distributions, and inter-feature correlations within the data related to cancer diagnosis.

The dataset typically includes features computed from digitized images of fine needle aspirate (FNA) of a breast mass, which describe characteristics of the cell nuclei present in the image.

### Project Goals
1.  **Load and Clean** the raw breast cancer dataset.
2.  Perform **univariate and multivariate analysis** to understand the statistical properties of the features.
3.  Visualize the **distribution of features** across the two target classes (Malignant vs. Benign).
4.  Identify highly **correlated features** and those that offer the best separation between the diagnostic classes.

---

## Repository Files

| File Name | Description |
| :--- | :--- |
| `Breast Cancer Exploratory Data Analysis.ipynb` | The main Jupyter notebook detailing the entire EDA workflow, including data loading, cleaning, visualization, and statistical summaries. |
| `[DATASET_NAME].csv` | *Placeholder for the raw dataset file (e.g., the original CSV containing the cell metrics).* |

---

## Technical Stack

The analysis is performed using Python within a Jupyter environment, leveraging the following libraries:

* **Data Handling:** `pandas`, `numpy`
* **Visualization (EDA):** `matplotlib`, `seaborn` (used heavily for scatter plots, histograms, box plots, and heatmaps).
* **Environment:** Jupyter Notebook

---

## Key EDA Steps and Insights

The notebook likely performs the following crucial analytical steps:

1.  **Initial Inspection:** Checking for missing values, data types, and unique values in the diagnosis column.
2.  **Target Distribution:** Visualizing the balance (or imbalance) between the **Malignant** and **Benign** samples.
3.  **Feature Correlation:** Generating a **heatmap** to visualize the correlation matrix between all features, often revealing strong relationships between parameters like 'radius', 'perimeter', and 'area'.
4.  **Univariate Visualization:** Using **box plots or violin plots** to compare the mean and distribution of key features (e.g., 'mean radius', 'worst texture') directly against the diagnostic outcome.
5.  **Data Preprocessing for ML (Preview):** Initial steps like dropping unnecessary columns (e.g., ID) and converting the categorical diagnosis (M/B) into numerical labels (1/0).

**Expected Insights:** The EDA should confirm that features representing **size and complexity** (like mean perimeter or worst area) show the most significant difference between benign and malignant tumors, making them strong candidates for a predictive model.

---

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **Ensure the Data is Present:**
    Place your raw data file (`[DATASET_NAME].csv`) in the repository's root directory.

3.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

4.  **Launch Jupyter:**
    ```bash
    jupyter notebook
    ```
    Open the `Breast Cancer Exploratory Data Analysis.ipynb` file to view and execute the analysis steps.

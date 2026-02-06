# assignmentDataSet

# Principal Component Analysis (PCA) from Scratch – Population and GDP Africa

## Project Overview
This project implements **Principal Component Analysis (PCA) from scratch** using Python and NumPy.  
The implementation was completed in **Google Colab** as an individual academic assignment.

The objective of the project is to reduce the dimensionality of an African-based dataset while retaining as much variance (information) as possible.

No high-level PCA libraries (such as `sklearn.PCA`) were used. All PCA steps were implemented manually.

---

## Dataset Description
**Dataset name:** population-and-gdp-africa

The dataset contains population and economic indicators for African countries.

### Key characteristics:
- African-focused (non-generic dataset)
- Contains **missing values** in the `GDP (USD)` column
- Contains **non-numeric columns** (`Country`, `Continent`)
- Suitable for demonstrating data preprocessing and PCA

### Data preprocessing:
- Non-numeric columns were excluded before PCA
- Missing values in GDP were handled using **mean imputation**

---

## Project Objectives
- Implement PCA from scratch using NumPy
- Compute covariance matrix, eigenvalues, and eigenvectors
- Dynamically select the number of principal components using explained variance
- Visualize data before and after PCA
- Optimize performance using vectorized operations

---

## Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## How to Run the Project (Google Colab)

1. Open the Google Colab notebook using the link below
2. Click **Runtime → Run all**
3. Ensure all outputs (tables and plots) are visible

 **Google Colab Notebook:**  
PASTE YOUR COLAB LINK HERE

---

## Results Summary
- PCA successfully reduces the dataset into a lower-dimensional space
- Principal Component 1 (PC1) captures the highest variance
- Data structure is preserved after PCA transformation
- Explained variance is used to dynamically select optimal components

---

## Repository Contents

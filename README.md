# Stroke_Data_Analysis

## Overview
This repository contains a complete end-to-end workflow for analyzing stroke-related healthcare data. The project includes data cleaning, exploratory data analysis (EDA), predictive modeling using logistic regression and random forest classifiers, handling class imbalance with SMOTE, and the creation of a visual dashboard to summarize key insights.

The professional documentation PDF (`Stroke_Data_Analysis.pdf`) includes all the R code and outputs from each step of the analysis.

---

## Repository Structure
Stroke_Data_Analysis/
├── data/healthcare-dataset-stroke-data.csv # Kaggles Dataset
├── data/stroke_cleaned.csv # Cleaned dataset after preprocessing
├── .gitignore
├── 01_data_cleaning.ipynb # Data cleaning and preprocessing
├── 02_EDA.ipynb # Exploratory Data Analysis with visualizations
├── 03_modeling.ipynb # Predictive modeling and dashboard creation
├── Stroke_Data_Analysis.pdf # Compiled documentation with code and outputs
└── README.md 


---

## Data Source
The dataset used for this analysis was obtained from Kaggle:

[Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

- **Description:** Contains patient-level information including demographics, health metrics, and stroke occurrence.  
- **Usage:** The dataset was cleaned, missing values imputed, outliers removed, and new features created before analysis.  

---

## Usage

### Running the Notebooks
1. Open the `.ipynb` files in Google Colab or Jupyter Notebook.  
2. Run the notebooks in the following order:
   1. `01_data_cleaning.ipynb`  
   2. `02_EDA.ipynb`  
   3. `03_modeling.ipynb`  
3. Each notebook produces outputs including plots, statistical summaries, and models.  

### Documentation
- The full analysis is already compiled in the PDF `Stroke_Data_Analysis.pdf`.  
---

## Project Highlights
- Comprehensive data cleaning with missing value imputation and outlier removal.  
- Exploratory Data Analysis (EDA) with detailed visualizations and statistical summaries.  
- Predictive modeling using logistic regression and random forest classifiers.  
- Handling class imbalance with SMOTE for improved model performance.  
- Creation of an integrated stroke risk dashboard with ggplot2 and cowplot.  
- Professional documentation in PDF format covering all code and outputs.

---

## License
This project is for educational purposes. Please cite the source dataset if reused in research or publications.

---

## Author
**Nush Ojha**  
Documentation, data analysis, and modeling.

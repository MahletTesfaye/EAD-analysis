# EDA Analysis of Titanic Dataset

This repository contains a Jupyter Notebook that performs Exploratory Data Analysis (EDA) on the Titanic dataset, which is available from seaborn's sample datasets. The analysis includes various steps to understand the structure, relationships, and patterns in the data using descriptive statistics and visualizations.

## Files

- `EDA_Analysis.ipynb`: The main notebook file that walks through the steps of analyzing and visualizing the Titanic dataset.

## Dataset

The Titanic dataset, included in seaborn's sample datasets, contains information about the passengers on the Titanic, including their survival status, class, gender, age, and more.

### Features of the Dataset:
- **survived**: Survival (0 = No, 1 = Yes)
- **pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **sex**: Sex
- **age**: Age in years
- **sibsp**: Number of siblings/spouses aboard the Titanic
- **parch**: Number of parents/children aboard the Titanic
- **fare**: Passenger fare
- **embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- Additional columns like `deck`, `embark_town`, `alone`, etc.

## Analysis Overview

The EDA process includes the following steps:
1. **Loading the Dataset**: Importing the dataset using seaborn.
2. **Data Cleaning**: Handling missing values, and removing or imputing them as necessary.
3. **Descriptive Statistics**: Calculating key statistics for each column to summarize the dataset.
4. **Data Visualizations**:
   - Distribution of age, fare, and other numeric variables.
   - Survival rates by different categories such as gender, class, and age groups.
   - Correlation heatmaps to understand relationships between variables.
   - Bar plots, box plots, and histograms to visualize key insights.
5. **Conclusions**: Key takeaways and patterns discovered during the analysis.

## Requirements

To run the notebook, you will need the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install the necessary libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn
```
## Run in Google Colab
In this version, the **Colab badge** is included to provide a direct link to open the notebook in Google Colab, which is a convenient option for running Jupyter notebooks without any local setup. You can adjust the Colab link accordingly if needed, based on where the notebook is hosted.



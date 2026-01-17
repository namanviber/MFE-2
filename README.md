# COVID-19 Statistical Analysis Project

A statistical analysis project using R to investigate and compare COVID-19 mortality data across different continents.

## 🚀 Overview

This project utilizes R for performing statistical hypothesis testing on COVID-19 datasets. It focuses on analyzing "new deaths" and comparing the mean mortality rates between continents (e.g., North America vs. South America) to draw statistically significant conclusions.

## ✨ Key Features

- **Data Cleaning**: Preprocesses raw COVID-19 CSV data for analysis.
- **Hypothesis Testing**: Performs T-tests to compare mean mortality rates.
- **Visual Analysis**: Generates statistical plots to visualize test results and distributions.
- **Multivariate Analysis**: Scripts designed for comparative analysis across different geographic regions.

## 🛠️ Project Structure

```text
MFE-2/
├── covid_data_cleaned1 (1).csv  # Cleaned COVID-19 dataset
├── Report 1.R                   # R script for T-test and basic analysis
├── Report 2.R                   # Additional R analysis script
└── README.md                    # Project documentation
```

## 💻 Tech Stack

- **Language**: R
- **Libraries**: `webr`, `stats`
- **Data Tools**: CSV processing

## ⚙️ How to Run

1. **Install R**: Ensure you have R installed on your system.
2. **Install Libraries**:
   ```R
   install.packages("webr")
   ```
3. **Execute Scripts**: Run the `.R` files using an R environment like RStudio or from the terminal:
   ```bash
   Rscript "Report 1.R"
   ```

## 📊 Analysis Details

The project primarily focuses on:
- **Null Hypothesis ($H_0$):** Mean mortality in Region A is less than or equal to Region B.
- **Alternative Hypothesis ($H_a$):** Mean mortality in Region A is significantly greater than Region B.
- **Confidence Level:** 95% ($ \alpha = 0.05 $)

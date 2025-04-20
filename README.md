# Diabetes Statistical Analysis Project

This repository contains an R-based statistical analysis of a diabetes dataset, exploring various factors related to diabetes occurrence, risk factors, and relationships between health metrics.

## 📋 Project Overview

This project performs a comprehensive statistical analysis on a diabetes dataset to identify patterns, relationships, and risk factors associated with diabetes. The analysis includes exploratory data analysis, hypothesis testing, and statistical simulations to better understand the characteristics of diabetic and non-diabetic individuals.

## 🔍 Dataset

The analysis uses the "diabetes_dataset.csv" which contains several health metrics for individuals including:

- Glucose levels
- Blood pressure
- BMI (Body Mass Index)
- Insulin levels
- Age
- Number of pregnancies
- Skin thickness
- Diabetes Pedigree Function (DPF)
- Outcome (Diabetic or Non-Diabetic)

## 📊 Analysis Components

### 1. Exploratory Data Analysis
- Average glucose levels among patients with and without diabetes
- Average age of diabetic vs. non-diabetic patients
- Blood pressure measurements across groups
- BMI distribution analysis
- Diabetes rate in the dataset
- Distribution of BMI, DPF, and other metrics
- Relationship between pregnancies and diabetes occurrence
- Correlation between glucose levels, BMI, and age

### 2. Key Questions Addressed
- Association between glucose levels and diabetes likelihood
- Relationship between BMI and glucose concentrations
- Impact of pregnancy count on diabetes risk
- Age-related patterns in insulin and glucose levels
- Risk profiles for diabetic patients based on key metrics
- Relationship between glucose and diabetes across blood pressure levels
- Age-related trends in blood pressure
- Pregnancy count and diabetes proportion
- Skin thickness distribution impact on diabetes
- BMI categories and pregnancy numbers for diabetic women

### 3. Hypothesis Testing
- Testing significant differences in glucose levels between diabetic and non-diabetic patients
- Testing significant differences in BMI between the two groups

### 4. Statistical Simulation
- Random sampling with different sample sizes (n=10, n=15, n=100)
- Confidence interval calculations and analysis
- Investigation of sample size impact on interval width and accuracy
- Coverage proportion analysis across different sample sizes

## 🛠️ Requirements

To run this analysis, you need:

- R (version 4.0.0 or higher recommended)
- The following R packages:
  - dplyr
  - ggplot2
  - tidyr
  - scales
  - gridExtra

## 🚀 How to Run

1. Clone this repository to your local machine
2. Ensure you have R and RStudio installed
3. Place the "diabetes_dataset.csv" file in the project directory
4. Open the `.R` or `.Rmd` file in RStudio
5. Install required packages if not already installed:

```R
install.packages(c("dplyr", "ggplot2", "tidyr", "scales", "gridExtra"))
```

6. Run the entire script or execute code chunks sequentially

## 📝 Key Findings

- Higher glucose levels are strongly associated with diabetes diagnosis
- BMI shows a weak association with glucose levels, but stronger for diabetic individuals
- Higher pregnancy numbers tend to correlate with increased diabetes likelihood
- Age shows a slight upward trend with glucose levels
- Most significant risk factors for diabetes are glucose levels and insulin, while BMI, age, and blood pressure are less distinctive
- Statistical testing confirms significant differences in glucose levels between diabetic and non-diabetic individuals
- Larger sample sizes in statistical simulation lead to more precise confidence intervals and better coverage of the true population mean

## 📈 Visualizations

The project includes numerous visualizations to help understand the data:

- Bar charts comparing means between diabetic and non-diabetic groups
- Density plots showing distributions of key metrics
- Scatter plots exploring relationships between variables
- Box plots comparing distributions across groups
- Histogram and density plots of sample means in simulations

## 👥 Contributing

Feel free to fork this repository and contribute by:

1. Improving the analysis
2. Adding new visualization techniques
3. Incorporating additional statistical methods
4. Enhancing the documentation

## 📚 Resources

- [R Graph Gallery](https://r-graph-gallery.com/)
- Additional statistical resources and references used in the project

# Polynomial Regression in UX: Modeling Non-Linear Behavior

This project demonstrates how to apply **polynomial regression** to UX research data using R. It shows how simple linear models can miss important patterns in behavior - like when a variable increases, peaks, and then declines - and how a polynomial model can capture these curves more effectively.

The simulated dataset explores the relationship between **font size** and **readability**, reflecting a common UX scenario where increasing a design element improves user experience only up to a point.

## 📊 What This Code Does

- **Simulates realistic UX data** with variability and outliers  
- **Visualizes the raw relationship** between font size and readability  
- **Fits a linear regression model** and shows its limitations  
- **Fits a second-degree polynomial regression model** that better captures the curve  
- **Compares both models** using visual plots and model summaries  
- **Runs a robust regression model** to reduce the influence of outliers

## 📦 Packages Used

- `tidyverse`  
- `ggplot2`  
- `broom`  
- `MASS` (for robust regression)  
- `performance` (for optional model diagnostics)

## 📁 Output

The following plots are saved as PNG files:

- `font_size_readability_scatter.png` - Raw data visualization  
- `linear_model_fit.png` - Linear model overlay  
- `linear_model_residuals.png` - Residual plot  
- `polynomial_model_fit.png` - Polynomial model overlay

These can be used in presentations or shared on platforms like LinkedIn to illustrate the value of non-linear modeling in UX research.

## ▶️ How to Run

1. Open the R Markdown file in RStudio.
2. Install the required packages (if not already installed).
3. Click **Knit** to run the code and generate the HTML output and saved plots.




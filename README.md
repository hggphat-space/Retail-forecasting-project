# Retail Forecasting Project - Business Analysis Portfolio

## 📊 Project Overview

This project demonstrates advanced time series forecasting techniques applied to real-world Australian retail trade data from the Australian Bureau of Statistics (ABS). The project showcases expertise in statistical modeling, data analysis, and business forecasting—essential skills for business analysis roles.

**Author:** Hoang Gia Phat  
**Course:** ETC3550/ETC5550 Applied Forecasting  
**Date:** May 2025

## 🎯 Key Highlights

- **Real-World Application**: Analysis of Queensland Household Goods retail turnover data spanning 40+ years (1982-2022)
- **Advanced Statistical Methods**: Implementation of ETS (Exponential Smoothing) and ARIMA models
- **Model Validation**: Comparison with actual ABS data to validate forecast accuracy
- **COVID-19 Impact Analysis**: Examination of structural disruptions in retail patterns
- **Professional Reporting**: Comprehensive analysis using Quarto and R

## 🛠️ Technical Skills Demonstrated

### Data Analysis & Statistics
- Time series decomposition (STL)
- Box-Cox transformation for variance stabilization
- Unit root testing for stationarity
- Seasonal and regular differencing
- Model diagnostics and residual analysis

### Forecasting Methods
- **ETS Models**: Exponential Smoothing State Space models
- **ARIMA Models**: AutoRegressive Integrated Moving Average models
- Model selection using AIC values
- Forecast accuracy evaluation (RMSE, MAPE, MAE)

### Tools & Technologies
- **R Programming**: Statistical computing and analysis
- **Quarto**: Reproducible research and reporting
- **fpp3**: Forecasting principles and practice
- **tidyverse**: Data manipulation and visualization
- **ggplot2**: Advanced data visualization

## 📈 Project Structure

The project follows a systematic approach to forecasting:

1. **Exploratory Data Analysis**: Visual analysis of trends, seasonality, and patterns
2. **Data Transformation**: Box-Cox transformation to stabilize variance
3. **Stationarity Testing**: Unit root tests to determine required differencing
4. **Model Selection**: Comparison of multiple forecasting models
5. **Model Diagnostics**: Residual analysis and validation
6. **Forecast Generation**: Out-of-sample predictions with prediction intervals
7. **Model Validation**: Comparison with actual data to assess performance

## 📊 Key Results

- Successfully identified optimal Box-Cox transformation parameter (λ = 0.199)
- Determined appropriate differencing requirements through statistical testing
- Selected ETS model as preferred forecasting method based on test-set performance
- Achieved strong forecast accuracy with MAPE < 5% on validation data
- Captured seasonal patterns and trends effectively over 27-month forecast horizon

## 💼 Business Value

This project demonstrates:

- **Data-Driven Decision Making**: Ability to extract insights from complex time series data
- **Statistical Rigor**: Proper application of advanced forecasting methodologies
- **Critical Thinking**: Analysis of external factors (COVID-19) and their impact
- **Communication Skills**: Clear documentation and explanation of technical methods
- **Practical Application**: Real-world forecasting applicable to retail planning and inventory management

## 🚀 How to Run

### Prerequisites
- R (>= 4.0)
- Quarto (>= 1.3.0)
- Required R packages: `fpp3`, `tidyverse`, `readxl`

### Execution
```r
# Render the Quarto document
quarto render "Forecast_project_Hoang Gia Phat.qmd"
```

The project will generate an HTML report with all analyses, visualizations, and forecasts.

## 📁 Files

- `Forecast_project_Hoang Gia Phat.qmd` - Main Quarto document with analysis code
- `Retail Project – ETC3550_ETC5550 Applied forecasting.pdf` - Project requirements/instructions
- `README.md` - This file

## 🎓 Learning Outcomes

This project showcases proficiency in:
- Time series analysis and forecasting
- Statistical model selection and evaluation
- Data visualization and interpretation
- Business forecasting applications
- Reproducible research practices

## 📝 Notes

- Data sourced from Australian Bureau of Statistics (ABS) Table 11
- Models trained on historical data (1982-2022)
- Forecasts validated against actual ABS data (2023-2025)
- All code is reproducible and well-documented

---

**Portfolio Project** | Demonstrating expertise in business forecasting and statistical analysis for internship applications.


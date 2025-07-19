
# Survival Analysis of Titanic Passengers

## Description

This project conducts a comprehensive **survival analysis** on the Titanic dataset using R. The objective is to identify how various factors - including age, gender, passenger class, fare, family size, and port of embarkation - influenced the survival probability of passengers aboard the RMS Titanic.

Through detailed **exploratory data analysis (EDA)**, **statistical summarization**, **visualization**, and **regression modeling**, we extract meaningful patterns and provide clear interpretations with each statistical inference.

## Statistical Techniques Used

The analysis includes a wide range of statistical methods:

### Descriptive Statistics
- Frequency distributions  
- Measures of central tendency (mean, median, mode)  
- Measures of dispersion (range, variance, standard deviation)

### Measures of Location
- Quantiles, percentiles, deciles  

### Shape of Distribution
- Skewness  
- Kurtosis  

### Visualization
- Histograms  
- Bar plots  
- Boxplots  
- Scatter plots  
- Correlation matrix

### Regression and Correlation
- Simple linear regression (e.g., Fare vs Age)  
- Multiple linear regression (with categorical and numerical predictors)  
- Pearson correlation coefficient  

### Inferential Statistics
- Confidence intervals  
- Hypothesis testing (t-tests and p-values)  
- Interpretation of statistical significance  

Each statistical result is followed by a clear, concise **interpretation** to support data-driven conclusions.

## Libraries Used

The following R packages were used throughout the project:

```r
library(ggplot2)     # For visualizations
library(dplyr)       # For data manipulation
library(corrplot)    # For correlation matrix plotting
library(moments)     # For skewness and kurtosis
```

## Note on R Markdown Files

The analysis is written in **R Markdown (`.Rmd`) format**, which allows combining code, results, and narrative in a single document.

### To open and run `.Rmd` files:

1. Open [RStudio](https://www.rstudio.com/products/rstudio/download/).
2. Load the `.Rmd` file from the repository.
3. Make sure all required libraries are installed beforehand:
   ```r
   install.packages(c("ggplot2", "dplyr", "corrplot", "moments"))
   ```
4. The project is divided into 3 main sections:
   - **Exploratory Data Analysis (EDA)**: Initial data exploration and visualization.
   - **Statistical Summarization**: Detailed statistical analysis and interpretation.
   - **Regression Modeling**: Building and evaluating regression models to predict survival.

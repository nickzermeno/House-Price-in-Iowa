# House Price in Iowa

This is a machine learning project that aims to predict house prices in Iowa based on various features of the houses. The project is built using R and various libraries, such as caret, tidyverse, and ggplot2.

## Getting Started

To get started with this project, you will need to clone this repository to your local machine and install the required libraries.

### Prerequisites

The following are the prerequisites to run this project:

- R (version 4.0.0 or higher)
- RStudio (version 1.4.1717 or higher)

### Installing

To install the required libraries, you can run the following command:

```R
install.packages(c("caret", "tidyverse", "ggplot2"))
```

## Dataset

The dataset used in this project is the Iowa House Price dataset, which contains information about 2,930 houses sold in Ames, Iowa between 2006 and 2010. The dataset consists of 79 features and a target variable, SalePrice, which is the price at which each house was sold.

The dataset can be found in the `Datasets` directory.

## Exploratory Data Analysis

Exploratory data analysis was performed on the dataset to gain insights into the features and their relationships with the target variable. Since we are predicting a numerical value, we have to be careful for heteroscedasticity. The exploratory data analysis can be found in the Report.pdf and line-by-line comments can be found in the R Markdown file.

## Machine Learning Models

Various statistical methods were used to predict house prices in Iowa. The methods used are:

- Linear Regression
- Random Forests
- Forward Selection, Stepwise Selection, and Backward Selection
- Cramer's V
- Multivariate Imputation By Chained Equations

## Results

The results of the machine learning models are presented in the `HousePriceInIowaReport.pdf` report.

## Authors

- Nick Zermeno - [GitHub](https://github.com/nickzermeno)

## Acknowledgments

- The Iowa House Price dataset was obtained from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

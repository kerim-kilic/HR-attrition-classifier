# HR attrition classifier

The R and R Markdown code in this respository covers several supervised machine learning algorithms to predict if an employee of a company is likely to leave (attrition). It includes logistic regression and a random forest algorithm and compares the performance of both models.

The **HR-attrition-classifier.Rmd** Markdown file in this repository analyzes the **ibm_attrition** dataset from the **BAdatasets** library, trains several machine learning models and crossvalidates and tunes them for the optimal performance.

## Requirements

The R script requires the following packages and their requirements:

```r
library(tidymodels)
library(BAdatasets)
```
The **BAdatasets** library can be downloaded by running the following line in RStudio:

```r
devtools::install_github("jmsallan/BAdatasets")
```

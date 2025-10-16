# Statistical Tests Lecture 2025

This repository contains practical exercises and materials for learning statistical hypothesis testing. The materials cover both parametric and non-parametric tests for continuous and categorical outcomes.

## Contents

### 1. Continuous Tests (`continuous_tests.Rmd`)
This R Markdown file covers statistical tests for continuous outcomes:

**Parametric Tests:**
- Independent Samples t-Test - Compare means of two independent groups
- Paired Samples t-Test - Compare means of two related groups  
- One-Sample t-Test - Compare sample mean to a known population mean

**Non-parametric Tests:**
- Mann-Whitney U Test - Non-parametric alternative to independent samples t-test
- Wilcoxon Signed-Rank Test - Non-parametric alternative to paired samples t-test

### 2. Categorical Tests (`categorical_tests.Rmd`)
This R Markdown file covers statistical tests for categorical outcomes:

- **Chi-Square Test of Independence** - Test association between two categorical variables (for large samples)
- **Fisher's Exact Test** - Alternative test for small samples or when Chi-Square assumptions are violated

### 3. Homework (`homework.Rmd`)
Comprehensive homework assignment with practical exercises covering all tests:
- 5 exercises on continuous outcomes (one for each test)
- 2 exercises on categorical outcomes
- Comprehensive analysis section with test selection and real-world application

## Getting Started

### Prerequisites
- R (version 4.0 or higher recommended)
- RStudio (optional but recommended)
- Required R packages:
  - `tidyverse` - For data manipulation and visualization
  - `knitr` - For rendering R Markdown documents

### Installation
Install required packages in R:
```r
install.packages("tidyverse")
install.packages("knitr")
```

### Usage

1. **Open any .Rmd file** in RStudio or your preferred R Markdown editor

2. **Render the document** by clicking "Knit" in RStudio or running:
   ```r
   rmarkdown::render("continuous_tests.Rmd")
   rmarkdown::render("categorical_tests.Rmd")
   rmarkdown::render("homework.Rmd")
   ```

3. **For homework**: Fill in the solution code chunks and render to see your results

## Learning Objectives

After completing these materials, you will be able to:
- Choose appropriate statistical tests based on data type and study design
- Understand assumptions of parametric and non-parametric tests
- Perform and interpret t-tests, Mann-Whitney U test, and Wilcoxon signed-rank test
- Perform and interpret Chi-Square test and Fisher's exact test
- Calculate and interpret effect sizes
- Visualize data appropriately before and after analysis
- Communicate statistical findings effectively

## Test Selection Guide

### For Continuous Outcomes:
- **Two independent groups, normal data** → Independent Samples t-Test
- **Two independent groups, non-normal data** → Mann-Whitney U Test
- **Two related groups, normal data** → Paired Samples t-Test
- **Two related groups, non-normal data** → Wilcoxon Signed-Rank Test
- **One sample vs. known value, normal data** → One-Sample t-Test

### For Categorical Outcomes:
- **Large sample (n>40), expected frequencies ≥5** → Chi-Square Test
- **Small sample or expected frequencies <5** → Fisher's Exact Test

## Contributing
This is a lecture repository. If you find errors or have suggestions for improvements, please open an issue.

## License
See LICENSE file for details.

## Author
Stats Tests Lecture 2025
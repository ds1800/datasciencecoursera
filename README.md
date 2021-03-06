# DEVELOPING DATA PRODUCTS
# COURSE PROJECT - REGRESSION MODELS IN SHINY
# Introduction

**Regression models**  are very important in data science for being:

- The most well described, practical and theoretically understood models in statistics
- Able to solve a large array of problems
- Produce highly interpretable model fits
- Simple, parsimonious and interpretable


**A simple example of a linear regression model**, computed in R, is

```{r eval=TRUE, echo=TRUE}
summary(lm(mpg ~ sqrt(wt), data=mtcars))
```

**This shiny application allows to**

1. Select the database to be used.
2. Pick the resulting variable of the regression.
3. Choose one of the regressors
4. Define one of the several predefined linear models
5. Define some characteristics of the resulting plot.

**References**

1. Brian Caffo, [ Regression Models for Data Science in R](https://leanpub.com/regmods)

2. Francis Smart, [ A Shiny App for Playing with OLS](http://www.econometricsbysimulation.com/2013/11/a-shiny-app-for-playing-with-ols.html)

3. The shiny application can be found in: [Regression Models in shiny](http://ds1800.shinyapps.io/courseProject_DDP)

4. Code and presentation at: [Code and presentation](https://github.com/ds1800/datasciencecoursera)

5. Presentation at: [Rpubs](http://rpubs.com/ds1800/112287)

**This repository contains:**
- The present README.md file,
- The RegressionModels.Rpres file,  
- The respective RegressionModels.md file,
- The server.R and ui.R files for the application


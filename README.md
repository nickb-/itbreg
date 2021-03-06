# Introduction to Bayesian GLM Regression Methods

The intention here is to provide minimal examples of these methods which will serve as a reference for keen bayesian practitioners!

To keep things simple, uninformed priors are used. Methods are compared to their frequentist alternatives where possible.

## Simple Linear Regression

A single continuous target variable and a single continuous predictor variable.

### R

#### JAGS

```
R/slr.R
```

### Python

#### PyMC3

```
python/notebooks/slr.ipynb
```

## Multiple Linear Regression

A single continuous target variable and more than one continuous predictor variable.

### R

#### JAGS

```
R/mr.R
```

### Python

#### PyMC3

```
python/notebooks/mr.ipynb
```

## Logistic Regression

A single binary target variable and more than one continuous predictor variables.

### R

#### JAGS

```
R/glm.R
```

### Python

#### PyMC3

```
python/notebooks/glm.ipynb
```

## Required Software

### R

Relevant lines from `utils::sessionInfo()`

```
R version 3.5.2 (2018-12-20)
Platform: x86_64-apple-darwin15.6.0 (64-bit)
Running under: macOS Mojave 10.14.2

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] forcats_0.3.0   stringr_1.3.1   dplyr_0.7.6     purrr_0.2.5    
 [5] readr_1.1.1     tidyr_0.8.1     tibble_1.4.2    ggplot2_3.0.0  
 [9] tidyverse_1.2.1 rjags_4-8       coda_0.19-2
```

### Python

Create a conda environment featuring `numpy pandas statsmodels seaborn pymc3`

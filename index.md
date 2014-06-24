---
title       : Slidify Slides for Iris Data App
subtitle    : HTML5 SLides 
author      : Sachi Pradhan
job         : Tech Tinkerer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: sabyapradhan
  repo: SlidifyProject

---

## Iris Data Set App

App Functions

1. Select one of the four parameters
2. View the respective Histogram
3. View the initial 6 rows of the data set

---

## Iris Data Set Paramenters

Following are the 4 parameters that can be selected

1. Sepal Length
2. Sepal Width
3. Petal Lenght
4. Petal Width

---

## Iris Data Set


```r
library(datasets)
head(iris)
```

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
## 4          4.6         3.1          1.5         0.2  setosa
## 5          5.0         3.6          1.4         0.2  setosa
## 6          5.4         3.9          1.7         0.4  setosa
```

---

## Future Plans

1. Add more input types
2. Add a scatter plot which can show correlation, etc. 

---

## Thank You 

--

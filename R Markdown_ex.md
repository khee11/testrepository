---
  title: "Rmarkdown Test"
author: Il-Youp Kwak
date: "Mar 5, 2021"
output: html_document
---
  
  ## Rmarkdown Test
  
  This is a test script for rmarkdown.

```{r global_option, include=FALSE} 
knitr::opts_chunk$set(fig.width=8, fig.height=8, fig.path='Figs/', fig.keep='high',
                      warning=FALSE, message=FALSE)
set.seed(123123)
```


```{r  }
1+1
```


```{r}
data(iris)
library(knitr)
kable(iris[1:10,])
```

iris data have `r nrow(iris)` obersvations with `r ncol(iris)` columns. 

option include=FALSE will not show results. 
```{r, include = FALSE}
1+1 
```

option echo = FALSE will not show codes. 
```{r, echo=FALSE}
1+1 
```

To include a figure with specific size: 
  ```{r fig1, out.width = "500px", fig.align="center", echo=FALSE}
plot(iris[,1], iris[,2], col = iris[,5])
```

## Latex math equations

Here is a math equation
$$ \sum_{i=1}^n X_i $$
  
  ## Include graphs
  
  ```{r fig_ex1, out.width = "350px", fig.align="center", echo=FALSE}
knitr::include_graphics("Figs/TreeA.png")
```

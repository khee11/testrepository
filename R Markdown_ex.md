# R Markdown

## Introduce

#### 1. Markdown 변형, Rstudio에서 개발됨
  > https://yihui.name/knitr/options/#chunk options

#### 2. Markdown + knitr + ...

### 3. LateX equations with $$


## Chunk options
![image](https://user-images.githubusercontent.com/87646049/138608161-8ec9a0ad-e2e9-4f68-a188-3097bc800e9e.png)

    R markdown에서는 header가 필요함



# Example

## Header 부분

### YAML (Yet Another Markup Language) header
  > date를 자동으로 업데이트되게 하려면 `r Sys.Date()`를 사용할 수 있음

    ---
    title: "Rmarkdown Test"
    author: Il-Youp Kwak
    date: "Mar 5, 2021"
    output: html_document
    ---

## Text 부분
  > Markdown 언어로 작성하면 됨

    ## Rmarkdown Test
  
      This is a test script for rmarkdown.


## Code Chunk 부분
  > R 코드로 작성됨 (코딩셀 -> code chunk options 사용)
  > 
  > 코드 청크 이름 : r global_options

### Global chunk options
  > 보통 R Markdown 시작할 때 지정해주고 시작하는 편
  > 
  > default 옵션 set up
  > 
  > 중복 옵션 지정을 최소화하기 위해 설정

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

### In-line code

  > Text 중간에 R code를 사용할 수 있다.
  > 
  > 숫자를 자동으로 업데이트할 때 좋음

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

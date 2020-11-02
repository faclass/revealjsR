---
title: "Example Presentation"
subtitle: <h2>Subtitle</h2>
          <h1>Author</h1>
author: <br><br>
        Seminar <br>
        LMES
output: 
  revealjs::revealjs_presentation:
    self_contained: false
    keep_md: true
    reveal_plugins: ["notes", "chalkboard", "menu"]
    reveal_options:
      chalkboard: 
        theme: zenburn
        toggleNotesButton: true
      menu:
        numbers: true
---



## R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document.

## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

<aside class="notes">
Here are some notes.
</aside>

## Slide with R Output


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Slide with Plot

![](index_files/figure-revealjs/pressure-1.png)

## MathJax

$$(X'X)^{-1} X'y$$

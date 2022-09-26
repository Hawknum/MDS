New_lab4
================
Renzo Wijngaarden
2022-09-26

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](new_lab4_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

## Added material:

Next we look at the cars data set and see if we can just look at the
speed column.

``` r
summary(cars$speed)
```

       Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
        4.0    12.0    15.0    15.4    19.0    25.0 

Similarly, we can look at the distance column as well!

``` r
summary(cars$dist)
```

       Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
       2.00   26.00   36.00   42.98   56.00  120.00 

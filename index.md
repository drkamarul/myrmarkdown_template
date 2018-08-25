---
title: "my RMarkdown template to write a book"
author: "Kamarul Imran Musa"
date: "8/25/2018"
output: 
  html_document: 
    keep_md: yes
---



# start with one # hashtag

This is the chapter

## prerequisite

Setting -> Output Option -> Keep markdown file


## create a `index.Rmd` file


```r
library(tidyverse)
```

```
## -- Attaching packages -------------------------------- tidyverse 1.2.1 --
```

```
## v ggplot2 3.0.0     v purrr   0.2.5
## v tibble  1.4.2     v dplyr   0.7.6
## v tidyr   0.8.1     v stringr 1.3.1
## v readr   1.1.1     v forcats 0.3.0
```

```
## -- Conflicts ----------------------------------- tidyverse_conflicts() --
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

```r
mtcars %>% ggplot(aes(mpg)) + geom_histogram()
```

```
## `stat_bin()` using `bins = 30`. Pick better value with `binwidth`.
```

![](index_files/figure-html/unnamed-chunk-1-1.png)<!-- -->


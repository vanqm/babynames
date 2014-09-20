---
title       : Baby Names by Birth Year
subtitle    : Shiny Application
author      : Kevin Markham
job         : 
framework   : revealjs      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone    # {standalone, draft}
knit        : slidify::knit2slides
---

# Baby Names by Birth Year

A Shiny Application by Kevin Markham

---

## What's Your Name?

Have you met a lot of people with the same name as you?

Are they older or younger than you?

Do you know someone of the opposite gender with your name?

---

## Would you like to learn more about your name?

With my [Shiny Application](https://justmarkham.shinyapps.io/babynames/), now you can!

* Input your name
* View a plot of the number of males and females born with your name in the US from 1880 to 2013
* Find out in which year your name was most popular, and how many children have been born with your name!

---

## Data Source

The data for this application was provided by the [United States Social Security Administration](http://www.ssa.gov/oact/babynames/limits.html), and was converted into an [R package](https://github.com/hadley/babynames) by Hadley Wickham.

Here are the number of unique names in the dataset:


```r
library(babynames)
length(unique(babynames$name))
```

```
## [1] 92600
```

---

## Links

* Created by [Kevin Markham](http://dataschool.io)
* [Shiny Application](https://justmarkham.shinyapps.io/babynames/)
* [Application Source Code](https://github.com/justmarkham/babynames)
* [Presentation Source Code](https://github.com/justmarkham/babynames/tree/gh-pages)
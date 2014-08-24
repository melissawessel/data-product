---
title       : BMI Calculator
subtitle    : Quick and easy health indicator
author      : Melissa Wessel
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is a BMI?

- BMI stands for body mass index
- a quick and easy rule of thumb for defining weight categories
- not a definitive measure of health

--- .class #id 

## Weight Categories

The BMI includes 4 weight categories
- Underweight
- Normal
- Overweight
- Obese

---

## Why use a BMI?

- No invasive procedures
- Fastest quantitative measure
- Works for most people

---

## My BMI calculator

- Guaranteed accurate formula
- Leave the frills behind
- Straightforward answers

---

## Calculation example

Say you have a weight of 145 pounds and height of 70 inches.


```r
weight <- 145
height <- 70
703*weight/(height*height)
```

```
## [1] 20.8
```
and you have your BMI


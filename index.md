---
title       : BMI App
subtitle    : BMI Calculator
author      : Gaurav Bansal
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is Body Mass Index (BMI)

1. BMI is a measure of the amount of tissue mass (muscle, fat, and bone) in an individual
2. using this measure, BMI quantifies whether an individual is underweight, normal weight, or overweight
3. BMI is one measure of health but it is not and end-all!

--- .class #id 

## How is BMI calculated?

BMI calculated using a simple equation: 
$$BMI = \frac{W}{H^2}$$

--- .class #id

## Why is BMI important?
1. BMI provides a good proxy for body fat percentage in the absense of advanced body fat percentage measurement equipment.
2. Though a low or high BMI doesn't automatically indicate poor health, it is a good indicator that further testing might be necessary. 

--- .class #id

## Example calculation

Let's see how BMI is calculated in the app. For this example, let's assume we have a 2 meter tall individual who weights 90 kg. Let's figure out this person's BMI. 


```r
height <- 2
weight <- 90
BMI <- weight/(height^2)
print(BMI)
```

```
## [1] 22.5
```

--- .class #id

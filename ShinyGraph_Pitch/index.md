---
title       : ShinyGraphPitch
subtitle    : Trigonometry Learning Tool
author      : Real Numbers
job         : Coursera - Developing Data Products project, July 2014
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     :  [mathjax, bootstrap, quiz]           # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &radio

## Trigonometry Quiz
 
### Question 1

What effect does the value of A have on the graph of A*sin(x)?

1. Shifts the sine wave to the right or left
2. Stretches or compresses the wave horizontally
2. _Stretches or compresses the wave vertically_
3. Shifts the sine wave up or down

*** .hint

Try my [Shiny app](https://real-numbers.shinyapps.io/ShinyGraph/) to find out!



*** .explanation

The sin(x) wave is bounded below and above by -1 and 1. The value of A changes those boundaries, stretching or compressing it vertically.  A is called the amplitude of the wave.

--- .class #id 

## The General Sinusoidal Function

$y = A\sin(B\theta-C)+D$

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 
What if A or B is 2? Or if D $\ne$ 0?

The value of each parameter, A, B, C, and D has a unique effect on the shape or location of the sine wave.  The best way to learn what happens when you change each value is to try it!  My [Shiny app](https://real-numbers.shinyapps.io/ShinyGraph/) lets you change one or more of the parameter values with sliders so you can fully explore how the function changes as the parameter values change.

--- .class #id

## Fun Facts About My Shiny App

   
   
* I'm a math teacher, so I can actually use it
* The hardest part was dealing with the Greek letter $\theta$
* The second hardest part was labeling the x-axis with $\pi$ symbols
* I did the whole thing in one lonnnnnggg day

--- .class #id

## Try it!  Enjoy!
   
   
### [Trigonometry Learning Tool](https://real-numbers.shinyapps.io/ShinyGraph/)
   
   
# Thanks!



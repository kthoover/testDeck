---
title       : How Long Will It Last?
subtitle    : Calculating the Lifetime of Your Retirement Savings
author      : kthoover
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Why you need "How Long Will It Last?  
<br>
1.  Planning for retirement is important, but often hard and scary. 
<br>
<br>
2.  People need easy tools to help quickly understand where they are and where they are going. 
<br>
<br>
3.  They need to include inflation and investment return rate in their planning. 
<br>
<br>
4.  Future inflation and return rates are uncertain.  When thinking about retirement, people need tools for dealing with the uncertainty. 
<br>
<br>
5.  Many people are not comfortable with numbers and formulas.  A picture is worth a thousand words.  
<br>

### This is a simple and fun tool to help with retirement planning.

[How Long Will It Last?](https://kthoover.shinyapps.io/Shiny1/)


--- .class #id 



## Here it is -- How Long Will It Last?


<img src="assets/fig/DB1.png" style="width: 1000px;"/>  


1.  Enter you current savings and investments in the top scroll box and how much you think you will spend in your first year of retirement in the second scoll box.

2.  Use the sliders to enter estimates for rate of return on your investments and inflation rate.

3.  The model will tell you how long your retirement nest-egg will last.


--- .class #id 

## Improve Your Future

<img src="assets/fig/IB1.png" style="width: 1000px;"/>  


1.  Change the setting to see how to make your nest egg last longer.

2.  You can see what it will take to reach your goals.

3.  With good planning, you may even be able to grow you nest-egg in retirement.

[How Long Will It Last?](https://kthoover.shinyapps.io/Shiny1/)


--- .class #id 




## Possible Improvements and Next Steps  
<br>
1.  Allow for defined contributions, including Social Security and pensions. 
<br>
<br>
2.  Allow future expenses to vary other than increasing with inflation. 
<br>
<br>
3.  Allow a delay between today and the time when retirement spending starts. 
<br>
<br>
4.  Allow users to input a number of years and have the required nest-egg calculated. 
<br>
<br>
5.  Allow users to save past scenarios in some way.



```r
d <- Sys.Date()
t <- paste(weekdays(d), months(d), as.numeric(format(d, "%d")), as.numeric(format(d, 
    "%Y")))
```



### Today is Sunday June 22 2014, start planning for your retirement now.

[How Long Will It Last?](https://kthoover.shinyapps.io/Shiny1/)



--- .class #id 




```
## Error: Cannot open file.
```

```
## Error: argument must be matrix-like
```




---
layout: null
---

## Class 6-7: Simple regression

Regression is the main tool used by quantitative researchers.
This class will focus on simple regression, which is used to estimate the relationship between a dependent variable and one independent variable.

### Readings
- Kellstedt and Whitten, Chapter 8.

### Slides
- Slides for the class are available [here](https://github.com/nicrivers/uo_api_6319/raw/master/class_6.pdf).

### Lab
- We will review the t-test using data on [murder rates in the US](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/murderrates.csv) and [active transport](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/active_trans.csv)
- We will [illustrate simple regression](http://htmlpreview.github.io/?https://github.com/nicrivers/uo_api_6319/blob/master/R_session_6.html) with a [data set](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/summer_2015_ontario_elec.csv) on electricity demand and temperature in Ontario.
- Additional data sets used in class on [class sizes](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/schoolSizes.xlsx) and [fertility rates](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/fertility-contraception.csv)

### Homework for class 6: Research design
- Economists and others have long been interested in understanding the effectiveness of official development aid (ODA).
- You will find [data](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/aid_stunting.csv) on ODA receipts (in millions of US dollars), population (in thousands of people), and the rate of stunting (the percentage of children under 5 that are more than two standard deviations below median height for age -- this is an indicator of malnutrition) on the course website.  Use the data to make an informative plot showing the relationship between ODA and stunting.  Think carefully about what to plot. (Data are from the UN and OECD).
- Explain whether the type of data you have can be used to estimate a causal relationship between ODA and malnutrition/stunting.  The four hurdles we discuss in class are a useful framework for answering this question.
- Read the [paper](https://pubs.aeaweb.org/doi/pdfplus/10.1257/aer.104.6.1630) "US Food Aid and Civil Conflict" by Nunn and Qian.  Explain the research design that underlies their approach to understanding the impact of ODA in developing countries.  Try to explain how the paper selects comparisons to try to explain the causal effect of ODA. Explain whether their research design can tell us about the causal impact of food aid on conflict.  Again, the four hurdles are a useful framework for thinking about causality.  (Don't worry about not understanding every part of the paper; focus on explaining the intuition for how they arrive at their conclusions.)

### Homework for class 7: Simple regression
- Obtain the data file vote_data.csv, available [here](https://raw.githubusercontent.com/nicrivers/uo_api_6319/master/vote_data.csv).  (Right click the link and save it to a /data directory in your homework folder for this week).  The file has three variables:
    * *dist_no* is the number of the federal electoral district.
    * *liberal_vote_share* is the share of the vote (from 0 to 1) that the Liberal party of Canada received in that electoral district in the 2015 federal election.  For example, a value of 0.25 means that the Liberal party received 25% of the votes cast in that district.  This variable is obtained from Elections Canada
    * *immigrant_share* is the share of immigrant out of the total population in that electoral district.  This variable is obtained from the 2016 Canadian Census.  For example, a value of 0.43 means that 43% of the population in that electoral district are immigrants.
- Your job is to explain the Liberal party vote share by the immigrant population share.
    1. Make a plot that explains this relationship.  Label it properly.
    2. Conduct a linear regression of vote share on immigrant share.  Explain the results (i.e., what do the coefficients mean?  What do the t-statistics and p-values mean? How well does the model fit the data?)
    3. Does a higher immigrant share *cause* higher Liberal party vote share?
Answer these questions by creating an RMarkdown file and submitting the resulting HTML or Word document, in which both your script and results are visible.

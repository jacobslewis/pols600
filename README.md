# POL S 600 - Advanced Quantitative Methods

# Meeting time
We will meet on select Fridays (starting the 26th of August) from 10 AM to 11:30 AM. I am hoping to use Slack, but we may use Zoom if I can't make Slack work.

# Introduction
Welcome to **POL S 600**! This semester, we will build on the methods that were learned in the introductory stats course offered to PPPA graduate students. We should plan to meet about 8 times or so (every other week, approximately), probably on Fridays via Zoom or Slack.

Over the course of the semester, we are going to spend time going over the following quantitative issues, both theoretically and in an applied setting:
1. Really trying to understand data and regressions beyond a coefficient table
2. Understanding the theoretical and applied reason to use maximum likelihood models
3. Understanding standard error clustering and multilevel modeling
4. Providing core skills in data management and visualization

This course is designed to introduce you to the core theories and practice of advanced quantitative methods in the social sciences. This is largely an applied course – while we will cover some basic mathematics associated with the skills and techniques that we are learning, we will not spend much time focusing on the advanced calculus or matrix algebra that underpin these models. Of course, it is important to have a fundamental understanding of how these work, but in general, it is rarely necessary to dig that deep when conducting these analysis. Think of it like this: I am teaching you how to drive a manual transmission car – I am not teaching you how to engineer a car.

## Course objectives
1. To provide students with a foundational knowledge of the theoretical reasons to run maximum likelihood and multilevel models.
2. To provide students with the core skills needed to run these models using R in R Studio.
3. To provide students with the ability to generate predictions (via packages and bootstrapping), to beautifully visualize data, and to understand how to use core packages to manage, clean, and manipulate data (in a good way, not a devious way!).
4. To force you to think more clearly about what your data and models actually mean!!!!

It is my hope that at the end of this semester, students will feel empowered to really begin producing publication-quality research using quantitative methods.

## Slack channel
Participants in the class should feel free to join the Slack channel to facilitate communication with each other throughout the semester.
https://join.slack.com/t/slack-2jk5009/shared_invite/zt-1esujxlld-gXFC7D1cMHtGkxUOGi3uGw

## Readings
I highly recommend that you buy the following book, since we will read a chapter from it. It's not required, but frankly I think everyone should read it.
E. Bueno de Mesquita & A. Fowler (2021) Thinking Clearly with Data: A Guide to Quantitative Reasoning and Analysis. Princeton University Press.

There are also several resources online that I highly recommend:
1. R for Data Science by Hadley Wickham et al. This is the best way to learn about core data science using R and the tidyverse. The online version is completely free and available here: https://r4ds.had.co.nz/introduction.html
RDocumentation. Documentation for R and R packages notoriously suck. They’re written by nerds for other nerds. The RDocumentation website is a decent way to explore the functions of packages. Available here: https://www.rdocumentation.org/
2. Geocomputation with R by Robin Lovelace et al. This is sort of the “core” textbook for understanding how to do basic spatial stuff in R. We probably won’t cover much of this, but it’s a great tool! Available online: https://geocompr.robinlovelace.net/index.html 
3. Spatial Data Science. If you’re feeling saucy, the R Spatial Data Science page is a great way to learn the core functions of the raster and terra packages. Availablne online: https://rspatial.org/

## Required software
You are going to need to install several pieces of software in order to succeed in this class!

1. **R statistical software** - Available via the core website: https://www.r-project.org/
2. **R Studio IDE** - Available online via: https://www.rstudio.com/products/rstudio/download/

# Class meetings
(Firstly, this may change!)

## Week 1 - The basics of working with R
1. R, R Studio, and R Markdown
2. Packages: `Tidyverse`, `Here`
3. Data sources: ACLED, V-Dem, World Bank, ANES.
4. Workspaces, loading data, etc.

## Week 2 - Data: thinking about it, interpreting results, and visualizing predictions.
**Reading** - Achen, TCWD Chapter 2
1. Thinking about Data: why does it matter, what is it
2. Data generation
3. Cleaning data
4. Visualizing data (`ggplot2` vs. R Base)

## Week 3 - Maximum Likelihood Estimation (MLE)
**Reading**
1. Why use Max. Likelihood Models?
2. Differences from OLS
3. Connection to “real world” – data generation, collection, etc.
4. How much math do we really need to know?

## Week 4 - Binary Response Models
1. Logits & Probits
2. Transformations(invlogit via arm)
3. Predictions
4. CDF vs. PDF

## Week 5 - Ordinal Response Models
1. When do we use ordinal response models?
2. Why are they important to understand?
3. Why can’t we just use OLS?
4. Using the `Ordinal` package

## Week 6 - Count models
1. What is a count model? Why not just use OLS?
2. Poisson distributions
3. How the heck do we make predictions?

## Week 7 - Multilevel / Hierarchical models
1. `LME4` package
2. What are the advantages of hierarchical modeling?
3. Why not just cluster your standard errors?
4. What do we structure our levels at? (Hint: theory, theory, theory! Data, data, data!)
5. Why not just use fixed effects models?

## Week 8 - Random slopes and intercepts
1. What are the advantages of random slopes and intercepts?
2. What are the disadvantages?
3. Which variables to include in the mixed effects portion of the model?






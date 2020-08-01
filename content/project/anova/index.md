---
image:
  caption: Screen shot of my app
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: See the app!
  url: https://twitter.com/georgecushen
summary: Learn more about the ANOVA test process including which assumptions the test makes and the meaning behind the test conclusion.
tags:
- regression
title: Exlporing ANOVA (Analysis of Variance)
url_code: "github.com/duke-shiny-ed"
---

This app utilizes a series of tabs to guide the user through a step-by-step exploration of the ANOVA test.

The first tab, the About Page, introduces the learning objectives the app seeks to address and offers a brief introduction to ANOVA. In the following three tabs the user will have the opportunity to conduct their very own ANOVA test.

STEP 1
The next tab, title "Step 1", kicks off the ANOVA testing process. Here the user is introduced to the null and alternative hypotheses of the ANOVA test. The user can then manipulate the population datasets that will be used for the rest of the exploration. From there the user can progress to the next tab, "Step 2".

STEP 2
On the "Step 2" tab random samples have been taken from the population data identified by the user on the previous ("Step 1") tab. Here, users can manipulate the size of the samples drawn from each population. This tab also introduces that assumptions of the ANOVA test, and users are told whether or not these assumptions have been met and why under "ANOVA Assumptions" section. This is dependent on the user's manipualtion of the population data during "Step 1" and their manipulation of the sample size.

The random samples are displayed graphically on this tab as boxplots. Users may interact with the graph to visulaize the boxplots in full, a visual representation of the within groups variances of the samples, or a visual representation of the between groups variance of the samples. The relevance of these are explored further on the next tab, "Step 3".

STEP 3
The "Step 3" tab is concerned with reviewing the conclusion made by the ANOVA test regarding the population data identitfied by the user on the "Step 1" tab. Before receiving the conclusion, users are reminded of the hypotheses tested by ANOVA. Once again, the random samples from Step 2, whose variances are being analyzed by the ANOVA test on this tab, are displayed graphically as boxplots. Under the "What is the F-statistic" section users are introduced to the F-stat, its relationship to the within groups and between groups variances visualized on the "Step 2" tab, and how it will be used by ANOVA to reach the conclusion. 

Finally, the conclusion of the ANOVA test performed on the population data identified during Step 1 is highlighted. The conclusion is put in terms of the hypotheses (present on the Step 1 and Step 3 tabs), and users are also provided with a copy of the ANOVA test output you would expect when using the R programming language to conduct the same ANOVA test.


The next tab, titled "Resources", provided users with a copy of the equations relevant to ANOVA. Knowledge of these equations was not necessary in order to complete steps one through three. This page also gives more insight into how to interpret the R ANVOA test output seen on the Step 3 tab.

The final tab provides a short quiz for users practice some of the concepts reviewed throughout the app and to practice running an ANOVA test in R.






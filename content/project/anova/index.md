---
image:
  caption: Screen shot of Exploring ANOVA app
  focal_point: Smart
links:
- icon: share
  icon_pack: fa
  name: See the app!
  url: https://samanthaowusu.shinyapps.io/ANOVA-app/
summary: Learn more about the ANOVA test process including which assumptions the test makes and the meaning behind the test conclusion.
tags:
- regression
title: Exploring ANOVA (Analysis of Variance)
url_code: "github.com/duke-shiny-ed"
---

*This app utilizes a series of tabs to guide the user through a step-by-step exploration of the ANOVA test. To acces the Exploring ANOVA app click [See the app!](https://samanthaowusu.shinyapps.io/ANOVA-app/)*

## About Page
This first tab introduces the learning objectives the app seeks to address and offers a brief introduction to ANOVA. In the following three tabs users are given the opportunity to conduct their very own ANOVA test.

## **Step 1**
The next tab, titled "Step 1", kicks off the ANOVA testing process. Here users are introduced to the null and alternative hypotheses of ANOVA. They may then choose the population data that will be used for the rest of the exploration by interacting with the various manipulators present. Once satisfied with their choices users may progress to the next step.

## **Step 2**
On the Step 2 tab, random samples have been taken from the population data chosen during Step 1. Here, the user may manipulate the sample size drawn from each population. 

This tab also introduces the assumptions of the ANOVA test. Depending on the sample size and population data selected on the previous tab, users are told whether or not the assumptions have been met.

The random samples are displayed graphically on this tab as boxplots. Users may interact with the graph to visulaize the boxplots in full, a visual representation of the within groups variances *of the samples*, or a visual representation of the between groups variance *of the samples*. The relevance of these variances are explored further during the next step.

## **Step 3**
The Step 3 tab is concerned with reviewing the conclusion made by the ANOVA test on the population data selected by users during Step 1. Before receiving the conclusion, users are reminded of the hypotheses examined by ANOVA. 

Under the "What is the F-statistic" section users are introduced to the F-stat, its relationship to the within groups and between groups variances visualized on the "Step 2" tab, and how it is used by ANOVA to reach the conclusion. Once again, the random samples from Step 2, are displayed graphically as boxplots for reference.

Finally, the conclusion of the ANOVA test is presented. It is put in terms of the hypotheses users have examined, but users are also provided with a copy of the ANOVA test output they would expect were they to conduct the same test using the R programming language.

## Resources Page
This next tab provids users with a copy of some equations relevant to ANOVA. This page also gives more insight into how to interpret the ANVOA test output from R encountered during Step 3.

## Quiz Page
This final tab provides a short assessment for users to practice running an ANOVA test in R snd review some of the concepts touched on throughout the app.

---
*The Exploring ANOVA app was created by Samantha Owusu-Antwi for Duke University's Creating Interactive Learning Tools Project, Summer 2020.*






---
image:
  caption: Screen shot of Exploring ANOVA app
  focal_point: Smart
links:
- icon: atom
  icon_pack: fa
  name: See the app!
  url: https://samanthaowusu.shinyapps.io/ANOVA-app/
summary: Learn more about the ANOVA test process including which assumptions the test makes and the meaning behind the test conclusion.
tags:
- regression
title: Exploring ANOVA (Analysis of Variance)
url_code: "https://github.com/duke-shiny-ed/ANOVA-app"
---

## Overview
In this particular app you will be able to explore ANOVA, or Analysis of Variance. ANOVA is a method used in statistical analysis to question whether there is a meaningful difference between groups being studied. *To access the Exploring ANOVA app click [See the app!](https://samanthaowusu.shinyapps.io/ANOVA-app/)*

Learning Goals:
1. Examine how violations of the assumptions of ANOVA affect the ANOVA test output

2. Understand the relationship between the F-statistic and the ANOVA test output

3. Predict how manipulation of between and within group variances will affect the F-statistic and the ANOVA test output

## Instructions
This app is designed to gradually introduce you to the different aspects of ANOVA. To do this, the app utilizes a series of tabs. Interact with them in order, from left to right, to be guided through a step-by-step exploration of the ANOVA test. *The app is optimally viewed in full screen web browser.*

### **About Page**
This first tab introduces the learning objectives the app seeks to address and offers a brief introduction to ANOVA. In the following three tabs users are given the opportunity to conduct their very own ANOVA test.

### **Step 1: Identifying the Population**
The next tab, titled "Step 1", kicks off the ANOVA testing process. Here, users are introduced to the null and alternative hypotheses of ANOVA. They may then choose the population data that will be used for the rest of the exploration by interacting with the various manipulators present. Once satisfied with their choices users may progress to the next step.

### **Step 2: Draw the Samples**
On the Step 2 tab, random samples have been taken from the population data chosen during Step 1. Here, the user may manipulate the sample size drawn from each population. 

This tab also introduces the assumptions of the ANOVA test. Depending on the sample size and population data selected on the previous tab, users are told whether or not the assumptions have been met. If the assumptions are met green text will be rendered. For a vaild ANOVA test conclusion, users should aim to select manipulations on the Step 1 and Step 2 tabs so that all the text under this section turns green.

The random samples are displayed graphically on this tab as boxplots. Users may interact with the graph to visualize the boxplots in full, a visual representation of the within groups variances *of the samples*, or a visual representation of the between groups variance *of the samples*. The relevance of these variances are explored further during the next step.

### **Step 3: ANOVA Test**
The Step 3 tab is concerned with reviewing the conclusion made by the ANOVA test on the population data selected by users during Step 1. Before receiving the conclusion, users are reminded of the hypotheses examined by ANOVA. 

Under the "What is the F-statistic" section users are introduced to the F-stat, its relationship to the within groups and between groups variances visualized on the "Step 2" tab, and how it is used by ANOVA to reach the conclusion. Once again, the random samples from Step 2, are displayed graphically as boxplots for reference.

Finally, the conclusion of the ANOVA test is presented. It is put in terms of the hypotheses users have examined, but users are also provided with a copy of the ANOVA test output they would expect were they to conduct the same test using the R programming language.

### **Step 4: Quiz**
This final tab provides a short assessment for users to practice running an ANOVA test in R snd review some of the concepts touched on throughout the app.

### **Resources Page**
This next tab provides users with a copy of some equations relevant to ANOVA. This page also gives more insight into how to interpret the ANVOA test output from R encountered during Step 3.

---
*This app was developed by Samantha Owusu-Antwi as part of the Summer 2020 Duke Shiny Ed program.*






---
image:
  caption: Logistic Regression and ROC Curves App
  focal_point: Smart
links:
- icon: atom
  icon_pack: fas
  name: See the app!
  url: https://choojoe.shinyapps.io/logreg_roc/
summary: Learn the basics of logistic regression, when is it used and what does the model look like. Explore the effects of changing the threshold on the Confusion Matrix and ROC Curves in context of logistic regression.
tags:
- regression
title: Logistic Regression and ROC Curves
url_code: "https://github.com/duke-shiny-ed/ROCCurves"
---

## Overview

*For best view, please use Google Chrome with maximum width!*

In regression analysis, logistic regression is an important statistical model that can help model/predict binary dependent variables. An important step in creating logistic regression models is choosing the appropriate threshold, which is done through the ROC Curve. 

In this app you will: 

- Identify the function of logistic regression
- Select and understand ROC/AUC curves in logistic regression models
- Interpret a confusion matrix


## Instructions

The Logistic Regression and ROC Curves App is best experienced through sequentially following the tabs on the left side bar, and from left to right within tabs that have that capability ('Logistic Regression' and 'ROC Curve' tabs).

### Step 1: Welcome Tab
  - Overview of the app with learning objectives
  - Quick description of the dataset being used 

### Step 2: Logistic Regression
  - *Info*: First introduction to logistic regression, the situation one would use it in, and basic discussion of the output. 
  - *Data*: Scroll through entries in a table view!
  - *Model*: Observe see the data points from the previous tab in a graph with balance on the x axis and if the observation was default (1) or not default (0). Toggle the checkbox to see how the logistic model with a threshold of .5 categorizes the observation. Which observations are correctly predicted? How can you tell?
  
### Step 3: ROC Curve
  - *What is ROC*: This tab serves as an overview for the elements of an ROC Curve including axes and AUC. Notice where the threshold of .5 (which was used previously) is on the ROC Curve. Go to the next tab to see how the threshold from the model graph relates to the ROC Curve graph.
  - *Interaction*: Scroll manually on the Threshold bar to change where the threshold lies on the model.See these predicted outcomes in real time with the confusion matrix on the bottom and how accurate the model is with the table on the right. You can also click the small green arrow on the Threshold button to animate the change of threshold and how it affects the confusion matrix and points on the ROC Curve!
  
### Step 4: Confusion Matrix
  - Now what does the confusion matrix actually show?
  - See both the text definitions and the data points related to each types of predictions. Play with different thresholds in the previous tab and notice how it affects different calculations related to the strength of the model including: accuracy, misclassification, sensitivity, and specificity. Use the buttons on the bottom to see how these values are calculated! Also notice trends between the ROC Curve and the rest of the table of values on this tab.
  
### Step 5: Quiz
  - Review your new knowledge with this multiple choice quiz! You can redo each question after submitting an answer individually.
  
### Step 6: Glossary/Resources
  - *Glossary*: A good reference of all the definitions from key vocab in this app. Refer back and forth between these definitions and the parts of the app or concepts you have found confusing.
  - *Resources*: Need more info? Check out the video that inspired this app! There is also a link to the code for the R Shiny app as a resource.
  
---
*The Logistic Regression and ROC Curves app was created by [Joe Choo](https://www.linkedin.com/in/joe-choo/) as part of the Summer 2020 Duke Shiny Ed Program.*

  
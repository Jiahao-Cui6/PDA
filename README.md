# PDA

## Exploring the Relationship between environmental factors and marathon performance

### Background
The purpose of this study is to investigate how environmental factors, temperature, humidity,
 solar radiation, and wind, impact marathon performance across the lifespan in both men and
 women, with the hypothesis that older individuals will experience more pronounced slowing in
 high WBGT conditions compared to younger individuals, and similar trends will be observed
 in both men and women.

### Results
 This study examines how environmental factors, including temperature, humidity, solar radia
tion, wind, and WBGT,air quality impact marathon performance across ages and genders. We
 introduced the adjusted percentage current course record (Adjust_X.CR) to normalize finish
 times for a more accurate comparison. Performance generally improves from ages 15 to 30,
 followed by a steeper decline in females than in males. Environmental conditions significantly
 influence performance, with stability in good weather but a more pronounced decline with
 age in bad weather. Older individuals are especially sensitive to adverse conditions, and solar
 radiation and air quality were identified as the most influential factors, showing a complex,
 non-linear relationship with performance.


## Files

### report
`EDA_report.Rmd`: The Rmarkdown version of the Exploratory Data Analysis report, which includes both written text interpretations and raw code used in the analysis. 

`EDA_report.pdf`: The PDF version of the Exploratory Data Analysis report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis. 


## Dependencies

The following packages were used in this analysis: 

 - Data Manipulation: "tidyverse"
 - Data Visualization: "ggplot2"
 - Model: "randomForest"


## Effects of Behavioral Treatment on EOT Smoking Abstinence

### Background
The goal of this project is to use data from a randomized trial to examine baseline variables as potential moderators of the effects of behavioral treatment on end-of-treatment (EOT) abstinence. Additionally, we will evaluate baseline variables as predictors of abstinence, controlling for both behavioral treatment and pharmacotherapy.

### Results
This study underscores the complexity of treatment effects in smoking cessation interventions and the importance of considering baseline variables as moderators. By analyzing four distinct treatment configurations and applying multiple variable selection methods, we identified key predictors of EOT abstinence for each group. The use of interaction terms in logistic regression models further revealed significant moderating effects, with variables like FTCD score and Pleasurable Events Scale score. These findings highlight the need for personalized treatment approaches that account for individual baseline characteristics, particularly in populations with co-occurring conditions such as major depressive disorder.

## Files

### report
`project_2.Rmd`: The Rmarkdown version of the Exploratory Data Analysis report, which includes both written text interpretations and raw code used in the analysis. 

`project_2.pdf`: The PDF version of the Exploratory Data Analysis report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis. 


## Dependencies

The following packages were used in this analysis: 

library(dplyr)
library(janitor)
library(ggplot2)
library(tidyr)
library(reshape2)
library(mice)
library(VIM)
library(MatchIt)
library(survey)
library(glmnet)
library(caret)
library(gtsummary)
library(kableExtra)
library(e1071)
library(MASS)
library(DescTools) 
library(ltm)
library(epitools)

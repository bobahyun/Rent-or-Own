# Rent or Own?
## Author: Ava Delanty 
## Predicting if a Dwelling is Occupied by Owners or Renters

This project investigates factors associated with variables regarding people and their housing situations, using a selection of data from Washington State which was imported by the US Census and was accessed through IPUMS USA. The study uses support vector models for classification to predict based if a dwelling is occupied by owners or renters on factors about education, age, marital status, number of rooms, and number of families. Results indicated that marital status, education, number of rooms, and number of families were the strongest predictors. The study emphasizes the importance of considering people and housing factors when studying renting and owning properties in Washington.



## Table of contents
- [Table of contents](#table-of-contents)
- [Dataset](#dataset)
- [Modeling Question](#modeling-question)
- [Methods Used](#methods-used)
- [Technologies](#technologies)
- [Required Packages](#required-packages)

## Dataset
Steven Ruggles, Sarah Flood, Matthew Sobek, Danika Brockman, Grace Cooper,  Stephanie Richards, and Megan Schouweiler. IPUMS USA: Version 13.0 [dataset]. Minneapolis, MN: IPUMS, 2023. https://doi.org/10.18128/D010.V13.0


## Modeling Question
Predicting if a Dwelling is Occupied by Owners or Renters



## Methods Used
- Support Vector Classifiers (SVM)
- Receiver Operating Characteristic curve (ROC curve) 

## Technologies
- R
- RStudio

## Required Packages
- dplyr
- ggplot2
- haven
- e1071


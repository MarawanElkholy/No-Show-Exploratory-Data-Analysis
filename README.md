# No-Show-Exploratory-Data-Analysis

This Project Explores No Show Doctor Appointments Data From Brazil 

## What was the goal :
# I Was Exploring the data trying to find patterns and answering several questions:

  #a- which variables affect the no show rate 
  #b- which variables affect each other
  
  
## Observations and data wrangling :


1- we have null values in the age column also some ages are in the negative values which makes no sense

2- we also notice that the max value for handicap column is 4 which makes no sense since the value should either be 0 as not handicapped or 1 as handicapped (classifier indecator) not an actual value

3- patient id , appointment id won't really matter to our data analysis as they are very specific or non relatable or correlatable data or can't cause a differance in the patients ability to show or not

4- we also notice that the handcap column need to be renamed from handcap to handicap

## Limitations:
1- data has no description of how it was aqquired

2- data was not clean enough and some values made no sense indicating there was either an error with systems or in the gathering process

3- some data would of made it easier to get conclusions like if the patient has ever been to that hospital before or the quality of the hospital it self

## we conclude from patterns , heatmaps, and histograms and some statistical analysis that :

1- showing or not showing depends on : a-Age. b-waiting time. c-hospital

2-waiting time affects hospitals show/noshow rates

# **Hackathon**

## **Introduction**
> Introduction of ourselves (Netherlands - connect to NextWAIve)
> Why floods (the topic) are relevant to us
> Introduce how global warming is related to our topic as well as natural disasters
> Goal of this dashbaord (in which we could implement CRISP-DM)

> Mention taht we're are incapable of saving humanity from global warming but, we are trying to provide insights/prevention for future catastrophic events


## **EDA**
Collection and selection

The most time-consuming part of this project was finding data that was cross compatible, mainly because of our unfamiliarity with navigating databases and an unfeasible concept to begin with. All data used was publicly available. Our initial concept required a lot of complete datasets on every country. We mainly used datasets from OurWorldInData, these sets can be found in the references list. Some tables were found online but not downloadable, these sets often were limited but contained valuable information. We directly copied these and entered the data manually.



Cleaning and transforming

The data sets had to be cleaned a bit for our use, we seperated tables to reflect either just individual countries or the entire world, any other larger entities based on income or geolocation were removed to give representative visualisations (i.e. counts of natural disasters or people affected by those). Columns that were not relevant to our topic were removed from the set. To make the data set of climate change and natural disasters compatible we had to group the years in decades to match each other. At some points the data types had to be changed from text to decimal numbers.


Visualisation
The goal of this entire dashboard was to address global warming in a more serious way and to make it accesible to people that are not familiar with data or climate change. We made sure to explain each graph in a setp-by-step approach, slowly narrowing down on our topic. The main visualisations that were picked are meant to show an upwards trend in temperature and frequencies of natural disasters, as well as ratios and comparisons.


**Concept**
Our original concept unfortunately, was out of our expertise. But we wanted to showcase this concept nevertheless, for our experience as well as discovering its potential. As floodings are the most common natural disaster, which seems directly linked to the increase in temperature we focused on that. We want to propose a prediction model that takes into account different factors.
* Rainfall
* HDI
* Island, landlocked, coastal
* River and mountain landscape
* Drought
* Temperature
* Elevation of population / population exposed to flooding
* Frequency of floodings
We want to asses weight to each of these factors in relation to each other to make a prediction model, which could save time to evacuate people depending on the climate, decerasing the amount of casualties.

## **Findings**



## **THEME**
Sea Level Rise  
Global warming  
Floods


## **FORMULA**
> **Factors**
> Geolocation: landlocked, coastal, island
> income (HDI): low, mid, high
> Elevation - population/land:
> Frequency: 
> River:
> Rainfall: volume?
> other: discussion? - temperature, atmosphere moisture and soil moisture not considered due to time restraints, more in discussion. can act as a base-model for data experts. 

## **State the problem**
As greenhouse gases trap more energy from the sun, the oceans are absorbing more heat, resulting in an increase in sea surface temperatures and rising sea level.
Is there a relationship between rising sea level and global warming? (What causes global warming? What causes sea level rising the most? How is it connected to the nature, coastal areas, underwater life? Does rising sea level represent a threat in form of flooding?

## **Problem Statement**
> How can we assess the risk of flooding per country? (how to find countries that are endangered by floods)
> *how to test accuracy of the model? (maybe by looking at the data before industrialization (pre-1954)? people didn't have as advance tech as we do now to build dikes and other tools that prevent floods, therefore we can measure the flood risk more accurately.)





## **Discussion**
> 
> 
> 
> 
> 
> After considering multiple factors, due to lack of time and resources many still remain unconsidered in our research.\
> Other factors may include temperature, atmoshpere moisture, soil moisture...
> There is a way to create model, where each factor of the formula would represent a variable. Of course each variable (factor) influences floods differently and also some are more distinctive than other. Therefore it's needed to assign weight to each factor depending on correlation found between certain factor and frequency of floods occured in the country.
> If we were to have the formula, it would be possible to assign risk of flooding for the country more precisely. This model could be deployed to help prevent disasters in future, and help lower number of people affected by floods by implementing precautionary systems, facilities.
> HOW TO TEST ACCURACY OF THE FORMULA?
> After thorough discussion with the team we decided to base testing on, obviously events that occured in past. Since our team is based on Netherlands and more than **70%** of population lives below sea level, therefore is more prone to one of the factors (elevation) and at last, flooding. Formula would be tested _from_ - first day in history we can collect data related to freqeuncy of flooding and other factors; to - 1954. In 1953 last significant flood took place. We can state that from this year industrialization in the field of flood prevention started to evolve rapidly, therefore if we consider frequency of floods in the country that are not from pre-industrialization period findings would have a tendency to be skewed. 



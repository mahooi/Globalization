<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#Questions-&-Hypotheses)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

<img src="https://preview.redd.it/ad5srjbso8q11.jpg?width=960&crop=smart&auto=webp&s=d69d84972365233e2f918ecc4e5d11eba3f48a97" alt="Global Slavery Index 2018" width="600"/>

Modern slavery is a truly global issue. In this analysis we attempted to discover possible correlations from an existing Modern Slavery Index containing data for 2017 and other datasets containing rankings by country such as GDP or Acces to Education. 

# Questions & Hypotheses
<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/World%20Slavery%20Map.png" width="400">
1. Does the Acces to Education influence the prevalence of Modern Slavery (victims per 1.000 people) accross the worlk? 

<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/access%20to%20education.png" width="400">

2. Is the GDP per capita a strong factor in determining the prevalence? 

<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/biggest%20contributors%20to%20modern%20slavery.png" width="400">
<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/biggest%20contributors%20to%20modern%20slavery%202.png" width="400">

3. Do the Criminal Justice System and the Effects of Conflicts and War in a country play a significant role in determining the number of victims per 1.000 people? 

<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/conflict%20map.png" width="400">
<img src="https://github.com/NekPel/visualizing_real_world_data/blob/master/Visualisations/criminal%20justice%20system.png" width="400">

4. What is the best model to describe the Index? 

## Workflow
- Choosing the topic
- Finding the relevant data sets
- Deciding on the focus for the project
- Defining tasks to be done
- Created [Trello](https://trello.com/b/5O7coURN/modern-slavery) board in order to keep track of tasks.
- Data cleaning and wrangling
- Deletion of rows with Null Values 
- Creating final merged dataset
- Visualizations
- Analysis
- [Conclusions](https://docs.google.com/presentation/d/17P5jbXlvgWv5qvLXZOgitLfhtC6prKgK/edit#slide=id.g8bebe9fff5_1_36)

## Organization

### Data Cleaning

Recommended Order:

- [GDP per Capita Analysis](https://github.com/NekPel/visualizing_real_world_data/blob/master/Notebooks/GDP%20per%20Capita%20Analysis.ipynb)
- [Access to Education Analysis](https://github.com/NekPel/visualizing_real_world_data/blob/master/Notebooks/Access%20to%20Education%20Analysis.ipynb)
- [Modern Slavery Analysis](https://github.com/NekPel/visualizing_real_world_data/blob/master/Notebooks/Modern%20Slavery%20Analysis.ipynb)

### Analysis

- There is a statistically significant effect of the Criminal Justice System, Access to education and the Effects of conflict on the number of victims of modern slavery (per 1.000 people).

- However, they do not accurately predict the number of victims, as the R squared value of the OLS analysis is just 0,30.

## Links 
- [Global Slavery Index]()
- [The World Bank - GDP Ranking](http://api.worldbank.org/v2/en/indicator/NY.GDP.MKTP.CD?downloadformat=csv)
- [Access to Education Index](http://hdr.undp.org/en/content/education-index)
- [Google Slides](https://docs.google.com/presentation/d/17P5jbXlvgWv5qvLXZOgitLfhtC6prKgK/edit#slide=id.g8bebe9fff5_2_0)
- [Tableau](https://public.tableau.com/profile/cezar2951#!/vizhome/ModernSlaveryAnalysis/Story1?publish=yes)
- [Trello](https://trello.com/b/EC0kcusx/module-2-board)

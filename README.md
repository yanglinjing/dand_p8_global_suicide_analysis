# Suicide Trend Analysis (1985-2016)
## -- By  Economy, Gender, Age, Generation, Countries
(Tableau Project)


## Introduction
This is a Tableau Project published on [my Tableau Public](https://public.tableau.com/profile/linjing7424#!/vizhome/SuicideRateAnalysis2/1).

The goal of this project aims at improving suicide prevention. The age, gender, generation, nationality of people who died by suicide have been analysed, as well as the economy of the countries.

## Data

The data for this project consists of one data file (comes originally from [Kaggle](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016)):

- `suicide.csv`: 27820 data points (rows) with 12 columns

The columns include:

1. country
- year
- sex
- age
- suicides_no
- population
- suicides/100k pop
- country-year
- HDI for year
- gdp_for_year (USD)
- gdp_per_capita (USD)
- generation

## Summary

From the graphs, it can be seen that different age, gender, generation groups have a signifcate impact on the suicide rates. People who belong to the groups of males, older people, or earlier generation have a higher suicide rate.

GDP also significantly affect them - as the global GDP per Capita (USD) increases, the global suicide rate decreases.

Besides, the rates largely vary among countries.



## Design


- This dataset includes geographic data, so I used the world map to show the different suicide rates among countries and regions.

- It also include years, which makes it easy to present how the rates change with time among people of different age, gender, generation groups.

- Bar charts are used to compare the differences of rates between different age, gender, generation groups.

- To compare the trends of world economy and suicide rates, I used bars for the economy indicators and lines for the rates to separate them visually.

- It might be worth for readers to find the trends of some specific countries, so I put the multiple  selector beside the graphs.


## Feedback

*@Eileen* gave me some feedbak on [my first sketch](https://public.tableau.com/profile/linjing7424#!/vizhome/SuicideRateAnalysis/1):

> A very interesting story! For the different generations, you should explain the terms "Generation Z", "Millenials", ... etc. with years. You cannot assume that all readers now when to place them.

> For the last slide, it might be nice to additionally see the global statistics divided by gender.

### Changes after collecting feedback
In the original sourch, I did not find the specific start / end year of each generation. Thus, I checked it online. However, for most of the generations (except baby boomers), there is no specific specific start / end year, and only decades are available. Finally I used decades to describe the generations for those who might not familiar with them.

In my initial sketch, I did include the global statistics divided by gender, but I put the graph at the beginning of the story, far from the dashboard of gender difference among countries. Now I put them next to each other, so readers can easily compare them.


## Resources
N/A

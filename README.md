# Determining the Effect of Racial Demographics and Incarceration Rate on Household Income

## Background

Over the past few decades, America's prisoner population has skyrocketed to over [2.2 million inmates](https://www.prisonpolicy.org/reports/pie2020.html), the highest per capita imprisonment rate in the entire world. This trend of mass incarceration, which began in the 1970s, has disprortionately affected poor, black communities such as the Fairfield Area in Baltimore, and the housing projects of Southeast D.C. Many of these areas already face the obstacles of an underprivileged schooling system and high-risk neighborhoods - higher incarceration rates serve to further perpetuate the lack of social mobility experienced by these communities.

The cities of Baltimore, Maryland and Washington, D.C. present similar examples of underprivileged, metropolitan communities. Using data provided by [The Opportunity Atlas](https://www.opportunityatlas.org/), this project will analyze the relationship between incarceration rates and household incomes in different areas in both cities, and compare the resulting data. In particular, I'll be examining whether the expected negative relationship is visibile in the data, and if there are any discrepancies between the imprisonment trends of the two cities.

I chose to examine this particular metric because I recently finished Michelle Alexander's _The New Jim Crow_, which provides a detailed recount of the caste-like imprisonment system instituted by the U.S. Government over the last few decades. My hometown is technically Potomac, MD, but the data from my area wasn't significant enough to compare with Baltimore, so I decided to use D.C. instead since I only live 15 minutes away.

## Business Question
What, if any, is the correlation between incarceration rates/racial demographics and household income in Baltimore and D.C.

## Data Question - Open Data

All of the data used in this project was gathered from [The Opportunity Atlas](https://www.opportunityatlas.org/).
The original data files can be found in the repository [here](https://github.com/a31kim/baltimoredc-male-incarceration-income/tree/master/originaldata).

1. [originaldata_balti_incarceration](https://github.com/a31kim/baltimoredc-male-incarceration-income/blob/master/originaldata/originaldata_balti_incarceration.xlsx) contains the data for incarceration rates in various areas within Baltimore city.
2. [originaldata_balti_income](https://github.com/a31kim/baltimoredc-male-incarceration-income/blob/master/originaldata/originaldata_balti_incarceration.xlsx) contains the data for household incomes in various areas within Batlimore city.  
3. [originaldata_dc_incarceration](https://github.com/a31kim/baltimoredc-male-incarceration-income/blob/master/originaldata/originaldata_dc_incarceration.xlsx) contains the data for incarceration rates in various areas within Baltimore city.
4. [originaldata_dc_income](https://github.com/a31kim/baltimoredc-male-incarceration-income/blob/master/originaldata/originaldata_dc_income.xlsx) contains the data for household incomes in various areas within Batlimore city.

## Data Question - Analysis

Microsoft Excel was used to answer:
* **What is the relationship between household income and incarceration rates in Baltimore and D.C.?** Examining the trends of area-based data, comparing the fluxes between the two metrics
* **Do Baltimore and D.C. demonstrate similar characteristics regarding the income/incarceration relationship?** Comparing data between the two cities to determine if one city displays significantly different trends

## Data Answer

The data is best summarized with a combination graph displaying both metrics.

#### Washington, D.C. Graph

![](.gitbook/assets/dc_chart.png)

This graph clearly displays a negative relationship between incarceration rates and household income. Communities like Georgetown and the Naval Observatory have significantly higher incomes and much lower incarceration rates than areas like Barry Farm and the Capitol Riverfront.

#### Baltimore, MD Graph

![](.gitbook/assets/baltimore_chart.png)

Much like the previous chart (except harder to read), this combination graph clearly shows a negative relationship between incarceration rates and household income. Neighborhoods like Greenmount West face incarceration rates as high as 25%, with household incomes barely reaching $15,000. Meanwhile, areas like Mount Washington experience incarceration rates as low as 0.05%, while benefitting from household incomes in the range of $70,000 a year.

#### Other Data

Looking at each neighborhood/area individually and examining its relationship between these two metrics was very interesting. The large data set is a little too large and unruly to display in this brief report, but you can view the data and the graphs yourself [here](https://github.com/a31kim/baltimoredc-male-incarceration-income/blob/master/comparison.xlsx).

## Data Application

The data analysis presented in this project adequately demonstrates the widely assumed negative relationship between household income and incarceration rates. The data does not seem to indicate any difference between Baltimore and D.C. in this regard, as the cities displayed very similar relationships. Upon researching some of the more prominent examples, such as those mentioned above, the vast majority of the low-income, high-incarceration communities were in low-educated, underprivileged areas. This is not particularly surprising, but the direct correlation is very interesting in regards to the issue of social mobility and community betterment.

It may have been helpful to have some additional data on the number of crimes committed annually in each area, to get a sense of the relative risk in each community as context for the incarceration data. It would also be interesting to compare this data with the relative primary/secondary education opportunities provided in each area.

As a resident of both cities, I think that it's important to remain cognizant of the entire city's populace, rather than just focusing on your own little bubble. Being a college student in Baltimore is a unique privilege, and analyzing data like this is a reminder of how amazing and rare an opportunity like this is.


# Does tree density influence the number of crimes in San Francisco?
PLOTS HOWTO:
  - short introduction why to we show this plot
  - title, axes, colors, labels, ticks, caption
  - observations written under the plot

## Introduction
TODO
- introduce the structure of the page
- provide link to the notebook

### Motivation
TODO
- why this topic is interesting
- how trees influence our lives
- what do we want to investigate
- what questions do we want to answer

### Datasets
TODO
- why did we choose SF data
- link to the notebook

#### Tree dataset
TODO
- link to the data
- short introduction
##### Overview of data
TODO
- basic infos about the data
  - number of rows, columns
  - size
  - date range
  - plot: map of trees
##### Fundamental aspects of the data
Categories
- number of trees in the dataset
- various types of trees, how many are there
- plot: map of trees per type
- number of trees in each category
- most commonly occuring type of tree
- least commonly occuring type of tree
- plot: bar plot over tree type occurences

Trees over the years
- plot: animation of planted trees over the years
- number of trees planted per year
- year with the least planted trees
- year with the most planted trees
- average number of planted trees per year
- plot: bar plot over average number of planted trees per year by type and adding its standard deviation
- define 'focus trees'?
- plot: bar charts displaying the year-by-year development of each tree types in the range X-Y
- comment on 3 interesting trends in the plot

Trees per area
- which area has the most trees (based on zip code)
- plot: plot zip code areas and color based on the number of trees? (we have done it for vehicle thefts on Sundays in PDDistricts)

#### Crime dataset
TODO
- link to the data
- short introduction

##### Overview of data
TODO
- basic infos about the data
  - number of rows, columns
  - size
  - date range
  - map of crimes?

##### Fundamental aspects of the data
Categories
- number of crimes in the dataset
- various types of crimes, how many are there
- number of crimes in each category
- most commonly occuring type of crime
- least commonly occuring type of crime
- plot: bar plot over crime type occurences
- define and explain groups: violent, non-violent, non-crime
- plot: heatmap of each group

Crimes over the years
- number of crimes per year
- year with the least number of crimes
- year with the most number of crimes
- average number of crimes per year
- plot: bar plot over average number of crimes per year by type and adding its standard deviation
- define 'focus crimes'
- plot: bar charts displaying the year-by-year development of each crime types in the range X-Y
- comment on 3 interesting trends in the plot

Crimes per area
- which area has the most crimes (based on PDDistrict)
- discuss stereotypes of certain neighbourhoods and compare with results
- plot: plot PDDistricts and color based on the number of crimes? (we have done it for vehicle thefts on Sundays in PDDistricts)

## Analysing the correlation between tree density and crime occurences
- what are we expecting
- what questions do we want to answer
  - connection between number of trees and number of crimes in general? (in 100mx100x areas on heatmap)
    - plot: heatmap of crimes
    - plot: heatmap of trees
    - calculate correlation
    - draw conclusion
  - is there an area where the more trees are the less crimes happen and vica versa?
    - plot: heatmap of crimes per pddistrict
    - plot: heatmap of trees per pddistrict
      - define zip codes for each pddistrict
    - calculate correlation for each area
    - draw conclusion
  - is there a drop in crimes as trees are planted over time?
    - animation of planting trees over the year + crimes in the same animation with different color?
    - make observations
    - support observations with calculations and data
  - prediction of number of crimes in area if X number of trees are planted
    - machine learning model
    - linear regression
    - checking the trees after the last planting date, so we consider "all" trees that can influence the number of crimes
    - do linear regression for tree types vs crime types as well
    - check correlation between tree types and crimes types

## Conclusion
- write conclusion of findings
- what could have we done better
- mention any areas with missing data (e.g. the park where no trees are listed in the dataset)

## References

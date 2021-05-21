# The Impact of Socioeconomic and Demographic Factors on Electoral Performance.

## Abstract 
This paper will focus on analysing the 2016 and 2020 US election results attempting to uncover the relationship between socioeconomic/demographic factors and the Republican electoral performance. Firstly, the extent these factors effect electoral performance is determined by using a combination of scatterplots and OLS. Secondly, regional variation was explored by modelling electoral performance using a regression framework and analysing the resulting residual choropleth map. Lastly, demographic shifts in the Republican voter base was determined by modelling the electoral performance of the 2016 and 2020 elections and comparing coefficient values. This paper aims to emphasise the benefits of iterative computational and visualisation techniques to derive and refine inferences made. All computational and visualisation techniques were conducted using different libraries from Python notably ‘sklearn’, ‘geopandas’, ‘altair’ and ‘seaborn’.


## Introduction

During 2016, the world stood in shock as Donald Trump was declared the president of the US. Since then, his presidency has been plagued with controversies making his loss in the recent 2020 elections unsurprising. However, the degree of loss was considerable trailing behind by 7 million in the popular vote and 74 in the electoral votes1. The republican loss has largely been credited to an increase turn out of youth voters and many minorities during this election term, seeing higher voter turnout when compared to similar timepoints in the 2016 election2.
This paper aims to investigate the relationship between the demographic makeup of counties and the way they voted in the 2020 election. This can be achieved by answering the following questions:

1. To what extent is the Republican electoral performance related to socioeconomic and demographic factors of the counties?
2. Can a similar relationship be seen across the country?
3. What were the key demographic shifts in Republican support during the 2020 elections?

Datasets used in this research paper is suitable in answering the research questions as it contains key socioeconomic and demographic features of each county which will be of use in determining the effects of electoral performance. Election results also come from well-known news outlets which provide confidence in its reliability. Measurement on the county level will also help sufficiently capture the heterogeneity of the US population, avoiding the overshadowing of minority classes.

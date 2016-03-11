# The way we look next: Mining past and future census data to predict diversity in race, income and aging

*Thursday, 10 March 2016, 9 a.m.*

The idea of a melting pot nation has gotten a lot of attention over the years, but is it really true? Whether it’s race, ethnicity, income, gender or other issues that separate us, how do we measure whether (and where) we are growing apart or together over the next few decades? Three experts will walk you through how to find the right detailed tables in the Census, how to build an index that can be used to compare nearly anything, and what the Census categories really mean (including whether we will really be majority-minority by mid-century).

* Joe Germuska, Northwestern University Knight Lab, [Censusreporter.org](https://censusreporter.org/)
* Paul Overberg, WSJ, formerly USA Today
* Jodi Upton, USA Today
* Stephanie Ewert, chief of the Foreign-Born Population Branch at the U.S. Census Bureau

## Changing face of America

*Paul Overberg*
 
[tipsheet](http://bit.ly/1W4N33k)

USA Today-Gannett project ([link](http://www.usatoday.com/topic/c9aea8ab-939a-4e71-b601-fe7164498251/changing-face-of-america/))

### Measuring a century of change

* Data on race/Hispanic ethnicity
* States and Counties, 1960-2060
* Neighborhoods and cities/towns, 2000-10
* Public schools, 1991-2011

#### [USA Today Diversity Index](http://bit.ly/1JmUpXt)

Simple description: How likely are 2 people to be different?

Measures everyone's relationship to everyone else. Able to compare times and places.

Can do diversity index for _any given area_, including neighborhoods, high schools, etc.

Picked one school, mapped which countries all the students are from.

### What next

Adapt it. Use neighborhoods? Asian/Hispanic diversity indexes? What else?

* Birthplace
How local are the people around you? Born in the state, region, rest of US, abroad.

* Housing
By units or age?

* Business size
How many employees?

## Using indices for complex comparison

*Joe Germuska*

**Index** is a composite statistic that **aggregates multiple indicators**.

* [Dissimilarity Index](https://en.wikipedia.org/wiki/Index_of_dissimilarity)
* Gini Index of income inequality (pre-computed in ACS)
* Simpson Index, aka Herfindah-Hirschman Index
* USA Today Diversity Index
* [Integration-Segregation Index](http://fivethirtyeight.com/features/the-most-diverse-cities-are-often-the-most-segregated/) (FiveThirtyEight)
* Black/White Income Gap/Black Income (FiveThirtyEight)

[How to compute the diversity index using python pandas](http://bit.ly/nicar16-diversity-index-pandas)

## US Population Trends by Race and Hispanic Origin: 2000 to 2060

*Stephanie Ewart*

Race/Hispanic breakdown for under 18 vastly different from population as a whole. In 2010, nearly half identified as a minority.

In 2010, 348 counties where population was at least half minority, east coast, Gulf Coast, Southwest border, pacific coast, AK and HI.

Overall pop: 43% growth in Hispanic/Latino 2000-2010. Non-Hispanic Asian grew 42.9%. White alone grew by 1.2%. Total pop grew by almost 10%.

Under 18: Total pop grew by 2.6%. 10% decline in non-Hispanic white. 46.3% growth in more than one race.

### Future trends

ARSH (age, race, sex, hispanic origin). Census Bureau only produces projections nationally. Historically had produced states. Some states produce their own.

Total pop projected to increase from 316 million in 2013 to 420 million in 2060 (33% increase).

Pct change between 2013 and 2016 (projected):

White alone, non-Hispanic; decrease by 9.5%. Two or more races, not-Hispanic, 226.9% increase.

By 2060, almost 1/3 of the population will be Hispanic.

For under 18:

White alone, Non-Hispanic: decrease by 23.8%, all other groups increase. Represent 32.9% of total pop in 2060. Two or more race, 8.3%; Hispanic, 38.0%.

Percent minority: 37.4% in 2013, 57.4% in 2060.

## Questions

Q: Growth in multi-racial population attributable to more self-reporting vs. actual growth in population?

A: Research ongoing. Hard to measure. Change in categories is coming.

Q: What changes are coming in categorization?

A: Census is conducting tests. May combine race/Hispanic origin into one question. May add Middle-Eastern/North Africa category. No decisions have been made. Collapsing two categories into one would make the data cleaner.
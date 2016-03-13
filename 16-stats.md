# Stats primer: Making sense of data

*Sunday, 13 March 2016, 9 a.m.*

Statistics are powerful measurement tools that enhance understanding and presentation of data. This session identifies key terms and applications (e.g., error, dispersion, probability, and tests for statistical significance) that unleash the power of statistics and your ability to tell stories with numbers.

* Peter Gade, University of Oklahoma

"There are liars, damn liars and statisticians."

Probably because people who understand stats hold a lot of power.

You don't have to be a math genius to understand statistics. You don't even have to understand the formulas. Concepts, and applications of concepts. Logic.

## Statistics

Tools that help us understand the world by describing, organizing and interpreting data. Allow us to reason mathematically about the meaning of data.

Can help understand:

* Errors in measurement
* Probabilities (likelihood of outcomes)
* Relationships between variables (correlations)
* Group differences (tests of significance)

### Sampling

To make inferences from a sample to a population, you want a sample that's representative. Sampling introduces sampling error. To control for sampling bias, researchers allow the "process of pure chance" to work.

#### Random samples

Randomness means totally left to chance.

To ensure randomness:

1. Sample selected in a way only chance operates, and
2. Every member of the population has an equal chance of being chosen.

Non-random samples (convenience, volunteer, purposive, quota) are unlikely to produce data that can be generalized to populations.

#### Polls and sampling error

Margin of error = sampling error

Sampling error is a measure of how much a sample varies from other samples we could draw from the same population. AKA, if we drew additional samples of the same size from the same population, how similar/different would they be?

#### Normal curve

Central limit Theorem indicates that 95% of additional theoretical samples would fall within ±2 standard errors of the percentages in the sample.

Republican primary example: Error was 3.7%, so if you took the poll again, you can say that with 95% confidence if you took another poll, you can be 95% sure that the results would fall within 3.7% of the previous results. If intervals overlap, you can't say with certainty (or at all) that one candidate is leading.

### Variable Relationships: Confidence Level and Probability

Researchers want a high confidence level in their tests. Most use 95% for determining statistical significance. This is indicated by statistical probability ("p"). Thus, when p < .05, we can say with at least 95% confidence that a relationship did not occur by chance (something caused it).

#### Correlations

Pearson product-moment correlation (aka Pearson "r")

The most common way of expressing the relationship between two variables.

* The range is from -1.0 to +1.0
* Positive correlation means that as one variable increases or decreases (or varies) the other variable varies in the same direction.
* A negative correlation means that as one variable increases or decreases, the other variable varies in the opposite direction.

Pearson r tells us two basic things:

1. estimate of the strength of the relationship (number)
2. direction of relationship (sign)

±.5 and above is high, but depends on the extent the variables vary and sample size. Look at the probablility ("p"): the lower the p, the higher the confidence level that the relationship did not occur by chance.

##### Sample problem

State department of education data set includes:

* State aid per district (per student/year)
* Demographics per district (ethnicity, gender, income)
* District size (number)
* Urban/rural (students/sq. mi.)
* High school graduation rates (by district)

Some questions we can answer:

1. Relationship between state aid and grad rates (correlation)
2. Differences between two groups' graduation rates (t-test)
3. Differences between more than two groups' graduation rates (ANOVA — analysis of variance)
4. Which variables are most important predictors of graduation (multiple regression)

##### 1. Interpreting correlations

Variables in test: State aid and graduation rates.

Pearson r = .418; Confidence level p = .007

Is correlation significant?  Yes, p < .05.

Interpretation: Statistically significant positive correlation that as state aid increases/decreases, high school graduation rates move in the same direction. The decrease is as important as the increase.

##### 2. Difference between two groups: independent samples t-test

Are there differences by gender and graduation rates?

Variables in test: gender (independent variable) and graduation rates (dependent variable)

Male: .71 (71% graduate); Female: .74

Results: t value = -.2036, df = 511, p = .042

Interpretation: Females are statistically significantly more likely than males to graduate high school AND males are statistically significantly less likely than females to graduate high school.

##### 3. Differences between more than two groups: ANOVA

Are there differences between ethnicity and graduation rates?

Variables in test: ethnicity (African-American, Latino/Latina, Native American, White, Other — independent variable), graduation rate (dependent variable)

Results: F = 3.692, p = .003

If ANOVA finds significance, must run a post hoc test (e.g. Tukey's Scheffe, Bonferroni) to see where (between which groups) differences are significant.

Post hoc results: Homogeneous subsets

##### 4. Predictors of conditions/outcomes: Multiple regression

Which variables are most important predictors of high school graduation?

Multiple regression calculates the relationship between multiple independent variables  and a dependendent variable. The coefficients produced are called "beta weights".

Variables in test: state aid, demographics, district size, urban/rural — all independent variables, and graduation rates (dependent variable).

Multiple regression results: Beta weights and significance level (p)

## Q&A

Q: Where do you draw the line for p values?

A: Usually 95%, but can vary based on topic — exploratory, small sample size, etc. You almost never hear a confidence level reported with a poll.

Q: Change over time?

A: ANOVA.

## Resources

Salkind, Statistics for people who (think they) hate statistics.

Williams & Monge, Reasoning with statistics: How to read Quantitative research

Wimmer & Dominick, Mass Media Research

SPSS, PSPP
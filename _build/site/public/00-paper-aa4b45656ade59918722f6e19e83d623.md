---
title: Analysis on the Life Expectancies of Countries (1990-2021)

authors:
  - name: Neel Date & Pranav Nair
    affiliations:
      - NCSSM

date: 2024-01-22

subtitle: An in-depth study into the varying life expectancies of countries from 1990 to 2021

abbreviations:
  USA: United States of America
  USSR: Soviet Union
  UK: United Kingdom
---

+++ {"part": "abstract"}
From 1990 to 2021, the world generally celebrated a consistent increase in average life expectancy. This increase was likely a result of numerous key factors, including: the expansion of medical infrastructure across the world (hospitals, vaccines, proper nutrition), the lack of major wars, and the overall increase in human happiness due to economic prosperity. However, not all countries attained an equitable increase in life expectancy, largely due to their pre-existing human development groups. A pandemic in 2020 was also responsible for the abrupt decline in life expectancy across the world, leading to speculation that the meteoric rise in life expectancy may not recover.
+++

## Average Life Expectancy of the World (1990-2021)

![](#LifeExpectancy)

#### Consistent Growth
As detailed in the line graph above, the average life expectancy of the world **consistently grew** from 1990-2019. Our team hypothesizes that the increase in life expectancy can be directly correlated with the economic and lifestyle advancements during this time period. The initial rise in the 1990s likely stemmed from more countries embracing free market capitalism after the collapse of the USSR, increasing the purchasing power of millions of people. Furthermore, the effects of the Green Revolution were also present, with bountiful agricultural yields also increasing life expectancy by reducing the rate of famine.

#### A Year in Decline: The COVID-19 Pandemic

The trend seen in the line graph came to an abrupt end in 2020, when the COVID-19 pandemic swept the world and killed millions of people. Although the actual causes of life expectancy decrease remained somewhat constant, the overall uptick in deaths across the world served to decrease average life expectancy considerably. Notably, the decrease affected all human development groups evenly, even countries that had access to better medical infrastructure.

## Comparing Life Expectancies Across Human Development Groups

![](#BarGraph)

#### Context

As extrapolated from the bar graph above, countries can be divided into 4 Human Development Groups: Low, Medium, High, and Very High. The criteria for these Development Groups is based on a variety of factors, including quality of life, economic prosperity, and access to medical infrastructure. A majority of countries are placed into either the High or Very High groups, suggesting that they should also yield higher average life expectancies, whereas Low and Medium countries will generally have lower life expectancies. This conclusion is supported in the graph below:

![](#LifeExpectancyHumanDevelopment)

## Sample Data Set

![](#Table)

## Linear Regression

![](#LinearRegresssionComparisonGraph)

:::{list-table} Average Growth In Life Expectancy by Human Development Level
:widths: 15 10
:header-rows: 1

*   - Human Development Level
    - Average Growth in Life Expectancy per annum
*   - Low Development
    - 0.469 years
*   - Medium Development
    - 0.306 years
*   - High Development
    - 0.204 years
*   - Very High Development
    - 0.218 years
:::

Using the graph, we can derive equations that project and model the growth of life expectancy per annum of a group of countries.

```{math}
:label: my-equation
\text{Low Development: } l = 0.469x + 47.487 \\
\text{Medium Development: } l = 0.306x + 58.552 \\
\text{High Development: } l = 0.204x + 67.775 \\
\text{Very High Development: } l = 0.218x + 73.432 \\


\\Where
\\
\\
\text{l = average life expectancy}\\
\text{x = years since 1990}\\
```


Upon examining the overall linear regressions of each Human Development Group, two trends emerge: Firstly, despite an abrupt halt to life expectancy increase due to the COVID-19 Pandemic, all human development groups are still forecasted to grow their life expectancies into the future (perhaps at a decreased rate). Secondly, it is apparent that countries in the Low Human Development Group have undertaken a remarkable transformation in life expectancy increase, which is highlighted by the slope of the Low countries being the steepest. Our team suspects that this is due to the natural principle of diminishing returns: The higher a country starts out on the Human Development Index, the less potential it has for life expectancy growth, whereas countries designated as Low Development are destined to rapidly increase their life expectancies due to burgeoning technological and medical advancements.


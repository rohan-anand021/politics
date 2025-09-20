# The Effect of Unemployment on Democratic Vote Share: An Analysis of Swing States in the 2020 Presidential Election

## Project Overview

This project analyzes the relationship between county-level unemployment rates, age demographics, and the Democratic vote share in the 2020 U.S. Presidential Election. The analysis focuses on seven key swing states: Arizona, Georgia, Michigan, Nevada, North Carolina, Pennsylvania, and Wisconsin.

The primary research questions are:
1.  What is the relationship between county-level unemployment rates and Democratic vote share?
2.  Does this relationship vary across different age demographics?
3.  How do these patterns differ across the selected swing states?

## Methodology

The analysis uses regression models to examine the effect of unemployment on voting patterns. The key variables are:
* **Independent Variable**: County-level unemployment rate.
* **Dependent Variable**: Democratic vote share in the 2020 presidential election.

The project also incorporates age demographics by categorizing counties as predominantly young (18-35), middle-aged (36-55), or older (56+) and using interaction terms in the regression models.

## Key Findings

* Overall, there is a statistically significant, but weak, positive relationship between unemployment and Democratic vote share. A 1 percentage point increase in unemployment is associated with a 1.58 percentage point increase in Democratic vote share.
* The relationship between unemployment and Democratic votes varies by state. Georgia and Nevada showed strong positive relationships, while Michigan showed a negative relationship.
* Younger--dominant counties (ages 18-35) showed the strongest positive relationship between unemployment and Democratic support.
* The low R-squared values in the models suggest that other factors, such as education, urban-rural divides, and pandemic response, were also significant in determining voting patterns.

## Files in this Project

* `399poster.Rmd`: The R Markdown file containing the code for the analysis and the poster generation.
* `399_final_poster-2.pdf`: The final poster presenting the research question, analysis, and conclusions.
* `usa_county_shapefile.rds`, `unemployment_rate_by_county.rds`, `election_data_president_2012_2020.rds`, `age_data_by_county_2020.rds`: The data files used in the analysis.

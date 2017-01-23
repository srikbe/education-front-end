# education-front-end
As a policy student interested in income inequality--and how inequality is affected by local taxes, such as the property tax--I want to know how disparities in educational expenditure can vary across states.

As an education policy specialist, I want a baseline understanding of overall expenditures, and whether such expenditures are substantially correlated with education outcomes (such as test scores, graduation rates, etc).

***

I gathered my data from the National Center for Education Statistics (https://nces.ed.gov/nationsreportcard/naepdata/dataset.aspx). Specifically, I acquired data on state per-pupil spending, broken down by poverty quartile (see Table A-1).

Using the d3 Bubble Chart, I presented this data in "chart-jp-bubble." Four files show how the data was gradually manipulated. First, the raw data can be seen in "A-1_FY2012" (in the back end folder). From that file, I sorted the states according to the percent differences between low poverty and high poverty district funding (see "PerPupil Spending"). From there, I copied and pasted the cells into a new csv file modeled after the data.csv file provided on d3 (see "bubble-data.csv"). This file includes only state names and total funding values for each state.

Thus, in the visualization, the size of the state bubble depends on overall funding per pupil. The color of the state bubble depends on the ratio of per-pupil funding in low poverty districts to per pupil funding in high poverty districts. The darker blue states have better high-poverty district funding, while the redder/browner states have worse ratios.

NOTE: I should have added a legend showing what the colors correlate to interms of a disparity (e.g., red means that spending in low-poverty districts is more than 10% higher than in high-poverty districts).

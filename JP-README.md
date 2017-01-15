# education-front-end

I gathered my data from the following sources:

1) From the National Center for Education Statistics, I acquired data on student test scores across states in the year 2013: https://nces.ed.gov/nationsreportcard/naepdata/dataset.aspx. (From this link, an excel file with the relevant statistics can be exported)

2) Also from the NCES, I acquired data on state per-pupil spending, broken down by poverty quartile (see Table A-1).

So far, I've only used data from category (2). Using the d3 Bubble Chart, I presented this data in "chart-jp-bubble." Four files show how the data was gradually manipulated. First, the raw data can be seen in "A-1_FY2012." From that file, I sorted the states according to the percent differences between low poverty and high poverty district funding (see "PerPupil Spending"). From there, I copied and pasted the cells into a new csv file modeled after the data.csv file provided on d3 (see "bubble-data.csv"). This file includes only state names and total funding values for each state.

Thus, in the visualization, the size of the state bubble depends on overall funding per pupil. The color of the state bubble depends on the ratio of per-pupil funding in low poverty districts to per pupil funding in high poverty districts. The darker blue states have better high-poverty district funding, while the redder/browner states have worse ratios.

NOTE: We should add a key explaining the shades.

# education-front-end
User Stories and Data Information
------
2010 SCHOOL IMPROVEMENT GRANT 
As a researcher, I want to understand the distribution of SIGs nationally so that I can begin to detect and track trends and standards between states in funds disbursement.

As a central office leader, I want to know how many other schools in my state received SIGs so that I have a sense of how likely it is that a school in my district may receive a grant. 

As a education policy specialist, I want to be able to see where we are spending our grant money.

I downloaded my data from data.gov. I originally had been hoping to create a visualization capturing the amount of grant money that went to each state or the types of turnaround models that were adopted for each school, but when totaling the figures, I realized that a few states did not report financial information and did not indicate the model that was adopted. So, I counted the number of schools that received funding for each state and grouped states into the 4 U.S. census-recognized geographical regions. The data was in CSV format, so I did not have to transform the data for the visualization. However, the Javascript for the bubble chart template was originally a 20-color pallete, but with only 4 regions, I needed less color gradients, so I modified the Javascript file to use the 10-color pallete. 
-------
GRADUATION RATES
 
As a potential educational entrepreneur, I want to understand whether the areas with more money spend on education grants have better graduation rates.

As a citizen concerned about the disparities in education across the country, I want to know where the graduation rates are lowest.

I used a choropleth visualization to shade counties with higher dropout rates in dark blue.  I had to rescale the original visualization to show counties between 5 and 30% dropout rates.  I faced the most difficulty in getting the map to scale properly and appear withing the format of the home page.
-------
CHILDCARE COSTS
As a foreigner, I want to understand some of the different issues with the USA education system
As a person looking to move states, I want to understand what states have better and affordable education options

I started at ChildcareAware.org - http://www.usa.childcareaware.org/advocacy-public-policy/resources/reports-and-research/costofcare/
I downloaded their report on Parents and the High Cost of Childcare. 
I used tabula to convert the data from pdf into csv. I then used an online tool (http://state.1keydata.com/state-abbreviations.php) to add the state abbreviation to the data. Finally, I used an online CSV to JSON tool (http://www.csvjson.com/csv2json) to convert my data to JSON format.

As a potential educational entrepreneur, I want to understand whether the areas with more money spend on education grants have better graduation rates.

As a citizen concerned about the disparities in education across the country, I want to know where the graduation rates are lowest.

As a education policy specialist, I want to be able to see where we are spending our grant money.

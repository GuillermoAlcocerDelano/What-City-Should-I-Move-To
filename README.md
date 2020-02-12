# What-City-Should-I-Move-To
Comparing the cities I like the most in the US considering their employment rate and the earning I would have. For earning I have considered it as the income minus the median rent.

## Assumptions
    All other costs are the same in every city
    The employment rate is the same for graduate students than general population

    

Notice from this graph that the best choices are Pittsburgh and Boston since they have a high employment rate and a high income.


<img src= https://github.com/GuillermoAlcocerDelano/What-City-Should-I-Move-To/blob/master/Earnings_and_employment_graph.png />

## Methodology
1. I retrieved data that indicated the following (one file for each KPI)
    -Median Income per city
    -Average rent per city
    -Employment rate per city

2. I added all KPI in the same data sheet with VLOOKUP

3. For each row (each row has a city) I made the formula  (Income - Rent) to obtain the Earnings per month

4. I added a new column where I indicated with a 1 if it was one of the cities I like. 

5. I created a PivotTable and a Pivot Chart indicating my earning and the employment rate.
    The "cities I like" column was used as a filter
    I ordered from highest to lowest Earnings value
    
6. I edited the graph to use a secondary axes for percentages, which would then be indicated as a line.


## Sources 

The data was retrieved on February 10th, 2020 from https://www.opportunityatlas.org/





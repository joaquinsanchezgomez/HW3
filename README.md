# Homework 3
Team members: Jennifer Lavayen, Lauren Done, Hugo Pinto & 
Joaquin Sanchez Gomez

#Findings

Using the microdata for New York City, we decided to do a 
value imputation exercise through a KNN model, to estimate 
where people live according to a set of socioeconomic variables. 
To do this, we selected: total income, family size, and monthly rent payment. 
The hypothesis behind it's that the boroughs where people with higher 
incomes lives are characterized by more expensive housing spaces;
simultaneously, people with more children must seek housing in boroughs 
with more affordable prices.

According to statistical information, 13.8% of the population lives 
in the Bronx, 14.8% in Manhattan, 5.3% in Staten Island, 35.1% in Brooklyn
and, finally, 30.9% in Queens. This data does not matches with the KNN model
results, which indicates that the proportions are very similar between the different
boroughs, this suggests that the population is distributed in equal proportions.
To go deeper, we decided to do a regression for each of the borough, in order to see 
if these variables could confirm our hypothesis. 
The results of the OLS model tell us that 13.6% of the population lives in the Bronx,
13.2% in Manhattan, 5.2% in Staten Island, 35% in Brooklyn, and 30.3% in Queens. 
In conclusion, it is possible to estimate the district of residence of a person 
based on the selected variables, taking into account the results of the application 
of an OLS model for each of the cases.

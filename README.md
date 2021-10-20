# Diversity in NYC Schools

## Description 

Explores diversity and possible correlations in the New York City Public school system. I calculated diversity by using <b>Simpson's Diversity Index</b>, which results in a rating between 0 and 1.

<img src="https://github.com/julia-claira/NYC_Schools_Crime_Attendance/blob/main/Resources/formula.png" width="20%" height="20%">

High scores (close to 1) indicate high diversity.
Low scores (close to 0) indicate low diversity.


## Table of Contents
* [Run](#Results)
* [Tools](#Tools)
* [Data](#Data)
* [Graphs](#Graphs)
* [Contact](#Contact)



## Run

The below link takes you to the resulting dashboard on Tableau Public:

[Diversity in NYC Schools - Tableau Story](https://public.tableau.com/app/profile/julia4245/viz/NYC_School_Stats/NYC_Diversity_Story?publish=yes)



## Tools

Python, Jupyter Notebook, SQLAlchemy, pgAdmin, Tableau


  
## Graphs

Daily cases and deaths for entire pandemic. User can zoom in as well as see daily tallies by moving their cursor over the graph.  

![Sample Graph](Resources/graphs_1.jpg)



Shows the risk level, trend, and ICU capacity for the area presently. (I calculate trend by taking the total confirmed cases of the last seven days and comparing it the previous week.)

![Sample Graphs](Resources/graph2.jpg)

![Sample Graphs](Resources/graph3.jpg)




## Data
The Data was pulled from the following sources, cleaned in Jupyter Notebook, and joined in SQL:

High school directory: https://www.kaggle.com/new-york-city/nyc-high-school-director
School attendance: Data.cityofnewyork.us
School Safety report: https://www.kaggle.com/new-york-city/ny-2010-2016-school-safety-report?select=2010-2016-school-safety-report.csv
SAT scores: https://www.kaggle.com/nycopendata/high-schools

I focused on data from 2015 as that was the common denominator for the most recent year.


## Contact

Feel free to contact me with examples or any questions via the information below:

GitHub: [@julia-claira](https://api.github.com/users/julia-claira)

Email: julia-claira@gmail.com

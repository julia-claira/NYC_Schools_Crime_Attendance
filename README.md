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

The following graphs were generated in Tableau:  
([Diversity in NYC Schools - Tableau Story](https://public.tableau.com/app/profile/julia4245/viz/NYC_School_Stats/NYC_Diversity_Story?publish=yes))

Diversity in individual schools, and borough diversity comparison:
<img src="https://github.com/julia-claira/NYC_Schools_Crime_Attendance/blob/main/Resources/graphs_1.jpg" width="70%" height="70%">

Correlation between diversity and other school measurments, such as attendance, school crime, SAT scores, and enrollment:
<img src="https://github.com/julia-claira/NYC_Schools_Crime_Attendance/blob/main/Resources/graph_2.jpg" width="70%" height="70%">

Racial composition in the least diverse schools:
<img src="https://github.com/julia-claira/NYC_Schools_Crime_Attendance/blob/main/Resources/graph_3.jpg" width="70%" height="70%">



## Data
The Data was pulled from the following sources, cleaned in Jupyter Notebook, and joined in SQL:

High school directory: https://www.kaggle.com/new-york-city/nyc-high-school-director
School attendance: Data.cityofnewyork.us
School Safety report: https://www.kaggle.com/new-york-city/ny-2010-2016-school-safety-report?select=2010-2016-school-safety-report.csv
SAT scores: https://www.kaggle.com/nycopendata/high-schools

I focused on data from 2015 as that was the common denominator for the most recent year.

The following people, including myself, contributed to data cleaning:
* [@hamiltojogo](https://github.com/hamiltojogo)
* [@KDrummerGirlLB](https://github.com/DrummerGirlLB)
* [@Claira](https://github.com/julia-claira)
* [@KristaJoy](https://github.com/KristaJoy)




## Contact

Feel free to contact me with examples or any questions via the information below:

GitHub: [@julia-claira](https://api.github.com/users/julia-claira)

Email: julia-claira@gmail.com

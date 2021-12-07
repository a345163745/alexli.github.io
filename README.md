# Data_Science_Project

## Abstract

**Title:** Does the vaccine help lower the growing case of Covid 19 in New York?

**Theme:** Vaccination, Covid-19, Health

**Description:** The outcome I would like to see from this project is to show that the more people get vaccinated in NY would lower the growing number of covid cases in New York. For the data collection part, I collected daily vaccination and daily new covid cases from January 12, 2021, to November 4, 2021, and try to predict the covid cases based on the vaccination data using a Linear regression model and also double bar chart to compare both data groups and see if the vaccination data increase for each month helps lower the new covid cases monthly.

**Relavance:** The data are focused in NY state only.

**Data Sources:** 1. https://github.com/nytimes/covid-19-data/blob/master/rolling-averages/us-counties-2021.csv
2. https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/us_state_vaccinations.csv

## Visualizations
The Linear Model(Daily_Vaccination as a indepenent variable to predict the growth of new Covid-19 daily). This Model predict that when daily Vaccionation reach around 591,640, the daily Covid case would drop to zero.
![Figure_1](https://user-images.githubusercontent.com/44101210/144101668-a6ea8d3e-5e95-4f44-b2ae-2a602d6aabe7.png)



The Double-Bar Chart below shows the cumulative Vaccination and Covid cases from January to November in 2021.
![Figure_2](https://user-images.githubusercontent.com/44101210/144101681-6ff032ac-ae77-48ad-8dff-e9f80ff10531.png)

As we can see from the chart, there is tremendous growth in the amount of vaccination from January to April and we can see the total number of COVID cases decrease in that month as the vaccination number continues to go up. Between May and June we see a decreasing number in vaccination, but the COVID case seems not affected by the decreasing number in vaccination since the number of vaccination is large enough to lower the COVID case down. However, between July to September, the COVID case started to grow back up again as the vaccination number fell under 1.5 million. Until the vaccination number reached over 1.5 million in October, the COVID started to go back down again. Thus, we can assume that New York State required over 1.5 million people to be vaccinated each month in order to lower the growing number of COVID cases in each month. 

##Overview
My underlying hypothesis was that the more people in New York state get vaccinated, the lower the number of covid cases growing in New York state. I used covid case dataset and vaccination dataset from NYTimes and owid GitHub and I used DateTime to filter the date range in 2021 only then I filtered the data only in New York state. Then I can use it in a linear model to predict covid cases based on the vaccination data. Then I merged both covid cases and vaccination data together and aggregate them using group by date, and sum them up so I can use them in a bar chart to do a comparison by month in 2021.

##Citation
1. https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html
2. Textbook 
3. Homework assignment
4. https://github.com/nytimes/covid-19-data/blob/master/rolling-averages/us-counties-2021.csv
5. https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/us_state_vaccinations.csv


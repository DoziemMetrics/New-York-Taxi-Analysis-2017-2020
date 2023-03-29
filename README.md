# New-York-Taxi-Analysis-2017-2020

![alt text](https://github.com/DoziemMetrics/New-York-Taxi-Analysis-2017-2020/blob/main/Taxi%20Picture.jfif "Airline Analysis")

This repository contains a Power BI project focused on analyzing New York City taxi data from 2017-2020. Through this project, we explored various trends in taxi usage, including the number of trips taken, total revenue generated, and average fare per trip. Additionally, we analyzed other key metrics such as total passengers and popular pick-up and drop-off locations.

The project was created using Power BI, a data visualization tool that allows for interactive exploration of large datasets. The visualizations and insights generated from this project can be useful for anyone interested in transportation trends or data analysis.

In this repository, you will find the Power BI report and associated data files, as well as any relevant code used in the project. Please feel free to explore the report and use the insights gained from this project for your own research or analysis.
you can find a detailed video presentation of the project here: https://www.linkedin.com/posts/chiedoziem-inyama_project8-analytics-project-activity-7029748331408932865-IFRE?utm_source=share&utm_medium=member_desktop

## Getting Started
To get started with this project, you can download the Power BI report file from the report directory. The report file is in .pbix format and can be opened using Power BI Desktop.

## Data
The data used for this analysis was supplied by Quantum Analytics where I am currently doing my internship as a data analyst. The data is stored in the data directory in CSV format, the data contains 5 tables.

## Running the Analysis
In order for the analysis to be done and for actual results to be given some steps had to be taken such as Data Cleaning, Data Modelling etc was carried out.
### Data Cleaning
The data was preprocessed using power query that is found in Power Bi before it was loaded for the analysisi proper. 
The processing include some cleaning such as
- Replacing of some incorrectly spelt word
- Promoting the first column of a table to header
- Deleting of bogus columns etc
### Data Modelling
The data contained 4 tables so there was need for modelling to be done. The four tables are
- 2017 Trips
- 2018 Trips
- 2019 Trips
- 2020 Trips
- Taxi Zones
- Calender
To model it I started by appending the 4 trip(2017,2018,2019 and 2020) tables into one table called Append1 then I connected the appended table with
![alt text](https://github.com/DoziemMetrics/New-York-Taxi-Analysis-2017-2020/blob/main/Modelling%20Taxi.jpg "New York Trip")

## Results
The results of the analysis are presented in the form of charts and graphs, which can be found in the Power BI report. The report provides insights into delay and diversion trends among major airlines, including the average delay time of aircraft by airline, the number of flights operated by each airline, the total number of diverted flights, the total number of delayed flights, and the reasons for flight delays. The report also includes interactive visualizations that allow users to explore the data in more detail and identify specific patterns and trends.
### Most Pick Up Location
![alt text](https://github.com/DoziemMetrics/New-York-Taxi-Analysis-2017-2020/blob/main/Borough.jpg "Most Visited Area")
### Observation
From the Visualisation above you'll find out that manhattan had the highest pick up trips followed by Queens and Brooklyn and the least visited area is the EWR.

### Total trips by year
![alt text](https://github.com/DoziemMetrics/New-York-Taxi-Analysis-2017-2020/blob/main/Total%20trips%20by%20Year.jpg "Airline Analysis")
### Observation
The above graph lets us to know that as the year progressed the number of trips taken continued to decline this can be attributed to the fact that as we progressed the got competitions from Uber and Taxify.

### Dashboard Proper
Other results can be found on this dashboard below
![alt text](https://github.com/DoziemMetrics/New-York-Taxi-Analysis-2017-2020/blob/main/Taxi%20dashboard.jpg "Dashboard")

### Observation
A brief look at the dashboard will tell you that there was a total of 26 million trips within the said time frame and the average fare was $12.39.
The total passengers were 36 million passengers in the reporting time frame

## Recommendation
From the above analysis here are my recommendations.
- The NYC Taxi union should come up with a strategy to combat the declining volume of trips by customer this can be done by studying competitors such as Uber and Taxify and know where they can Improve
- The NYC Taxi could develop an app and make it easy for passengers to be able to be able to book trips from their comfort zones
- Airport taxis can reduce their fares a little

## Conclusion
In conclusion, this Power BI project provides a comprehensive analysis of New York City taxi data from 2017-2020. By exploring trends in trip volume, revenue, and other key metrics, we have gained valuable insights into how taxi usage has evolved over time.

The visualizations and interactive capabilities of Power BI have allowed us to easily explore and communicate these insights, making this project a useful resource for anyone interested in transportation or data analysis.

We hope that this project serves as a useful example for others looking to analyze large datasets using Power BI or other data visualization tools. Please feel free to fork this repository and build upon our work, or use the insights gained here for your own research or analysis.

Thank you for exploring this project with us!

## Contributing
If you would like to contribute to this project, please feel free to fork the repository and submit a pull request. Your contributions are greatly appreciated!



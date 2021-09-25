![jpg](https://pbs.twimg.com/media/D4Q5Gu9WAAEDDZ8.jpg)

I've always been a big fan of Formula 1 especially for its technological advancements shown by each team as time progresses. For starters, here is a brief introduction of Formula 1.

**Championships** - There are two different titles in F1, the World Driver's Championship (WDC), which goes to the driver with the most individual points at the end of the season, and the World Constructor's Championship (WCC), which goes to the team with the most points between their two drivers. Every team fields 2 cars in every race. There are generally ~18 races or so, but the amount changes frequently as races are added or dropped.

**Scoring** - Scoring is based purely off of where you finish the race. It used to be that only the top 6 placing drivers scored, then it was changed to 8, and more recently it was changed to 10. 1st place is worth 25 points, then 18, 15, 12, 10, 8, 6, 4, 2, and 1 respectively.

This project will be using SQL queries and data visualiztion with Python for data analysis. we will be using SQL for extracting and trandforming the data before doing visualization with python. 

# 1. Questions

This analysis will try to answer the following questions:

**Drivers**
1. Which driver had the most F1 World Driver's Champion title?
2. Which driver had obtained the most pole position?
3. Which driver had the most points throughout their career?
4. How many F1 drivers that actually won at least one race?
5. What are the nationality of most F1 drivers?

**Constructors**
1. Who are the all time winning teams since 1950? 
2. Which teams are the earliest to participate in F1? 
3. What are the F1 constructors nationality? 
4. Who are the winning teams since the Hybrid era? 
5. How are the performance of the 2021 teams before? 

**F1 circuits and races**
1. Where are most of the F1 tracks located? 
2. What are the the fastest lap time for each Grand Prix? 
3. How many F1 races are there for each season?

# 2. Measurement Priorities

For Drivers:

* Drivers with the maximum total points for each year.
* Count of drivers where located at grid position 1.
* Sum of points by each drivers for all year.
* Count of drivers where wins are more than 1.
* Sum of drivers nationality count.

For Constructors:

* Total race wins count for each teams.
* First race date by each team.
* Count of teams nationality.
* Total race wins for teams that participate in 2014 and onwards.
* Sum of points for each year for teams participating in the 2021 F1 season.

For F1 circuits and races:

* Geolocation of the F1 circuits.
* Minimum lap time for each Grand Prix
* Count of race for each year.

# 3. Data Collection

* Source
    * The data is obtained from the Kaggle.

* Storage
    * Data is loaded into local database thorugh Microsoft SQL Database.

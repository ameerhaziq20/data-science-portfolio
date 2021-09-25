![jpg](https://assets.weforum.org/article/image/large_Gt3_maI3Pg1p3LCdz686W_z41IEvOy6elJNQmu_oRLc.jpg)

# 1. Questions

This analysis will try to answer the following questions:
* What factor that most likely to cause an increases in the number of new cases?
* How Covid-19 affects differently in different states?
* When will we achieve herd immunity?
* Will new cases increases or decrease next month?

# 2. Measurement Priorities

* Correlation between each factor in the dataset using correlation matrix.
* The difference in the count of new cases and in the states.
* Percentage of fully vaccinated individuals angainst the total population.
* Number of forecasted new cases in the next 30 days using time series forecasting.

# 3. Data Collection

* Source
    * For this analysis, we will make use of the dataset from The Ministry of Health Malaysia GitHub page.
    * Since they don't provide data for vaccinations, we will obtain the data from other sources which in this case is from Our World in Data.
    * These sites frequently updates these data values, we will use programmatically automate this data collection process each time we restart the notebook

* Storage
    * The data collected from the sites will bw stored as a CSV file in the /dataset directory.
    * This allows the data can still be analysed localy when connectivity problems persists.

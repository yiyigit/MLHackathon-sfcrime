# MLHackathon-sfcrime
For this hackathon, we'll be using the a database of crimes reported in San Francisco over a number of years.

This is a supervised learning task, with the goal of predicting the *category* of crime a given report will fall into given the date, police district, address, and longitude/latitude of the report.

### Data Fields
**Dates** - timestamp of the crime incident\
**Category** - category of the crime incident (only in train.csv). This is the target variable you are going to predict.\
**Descript** - detailed description of the crime incident (only in train.csv)\
**DayOfWeek** - the day of the week\
**PdDistrict** - name of the Police Department District\
**Resolution** - how the crime incident was resolved (only in train.csv)\
**Address** - the approximate street address of the crime incident\
**X** - Longitude\
**Y** - Latitude\


## Data Exploration & Analysis

1. Number of crimes per category
2. Number of crimes per time of the day, day, week, month, Year, District, Resolved, zipcodes 
3. Heatmap of crimes by district 
4. Correlation of resolution with the area of occurrence, crime 
5. Correlation matrix of features
6. Wordcloud of Descriptions 
7. Data Munging with external holiday and event dataset (Pandas)
8. Most common crimes (Bar plot)
9. Districts with most crimes (Bar plot) 
10. Categorize crimes by price of housing (Optional)

## Preprocessing
1. Standardizing
2. Data cleaning
3. Make sure the date fields are datetimes.
4. Consider using the StandardScalar.
5. Try PCA.


## Feature Engineering
1. Cluster latitudes and longitudes
2. Probably NLP can be used to extract the description
3. Get hours, month, year from dates. 
4. Get holiday and event info
5. Extract street from address and infer Zip code



## Models to Try (And Tune Parameters )

Base Model - Assign probability of occurrence for a certain category



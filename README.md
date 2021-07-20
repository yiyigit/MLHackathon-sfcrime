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

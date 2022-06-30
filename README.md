# cyclistic-case-study

The Google Data Analystics Capstone Project using Divvy bike data.

This case study was completed as part of the Google Data Analytics Professional Certificate. 

The Mission Statement: The bike-sharing company (Cyclistic) wants to analyze their user's data to find the differences in behaviour between their two types of users, the "casual" riders who pay for each ride and the "annual" rider who pays a yearly subcription to the service. 

## PHASE 1: ASK 
### Key objectives:
1. Identify the business task: the company wants to increase their earnings by reaching out to "casual" riders, for that they would have to analyze in what aspects the "casual" and the "annual" customers differ, and to be able to create a successful marketing message to the "casual" customer that makes them convert to the "annual" subcription. 

2. Consider key stakeholders: the main stakeholders is Lily Moreno the director of marketing and my manager, the marketing analytics team, and the Cyclistic executive team. 

## PHASE 2: PREPARE
### Key objectives: 
1. The credibility of the data: The data was downloaded directly from Divvy Bikes website: https://ride.divvybikes.com/system-data 

The data was organized by months, and assumed to be credible since it was published and compiled by the organization. Within the data, there were some anomalies (these were highlighted in the presentation file).

2. Sort and filter the data: For the analysis I'm going to be focused on the 2020-2021 period as it's more relevant period to the business task, and it was a more complete data with types of bikes used and geo-location coordinates. 

3. We are using the dataset from Septmember 2020 to August 2021.

4. Organize the data in folders and subfolders, using proper naming conventions and saved the data as csv files.

5. Sort and Filter the Data: Data is too large for spreadsheets, Postgresql will be used for the data. 

Imported the data to Postgresql and sorted it by writing SQL querry to remove columns with null values. 

## PHASE 3: PROCESS
### Key objectives:
1. Check the data for errors
2. Choose your tools
3. Transform the data so you can work effectively
4. Document the cleaning process

### Adding a new columns to the dataset in PostgreSQL:

After looking at the data, I see that some columns need to be added for them to be used in analysis later.
The columns are:

1. A new column for trip length (hours,minutes,seconds) was created to calculate the length of each ride.

2. A new column for date_of_ride was extracted from started_at, results in date only.

3. A new column for time_of_ride was extracted from started_at, results in time only.

4. A new column for day_of_week was extracted from started_at, results in 0-6 as day of weeks where 0 = sun and 6 = sat.

Now we have a clean dataset with no null values, and 4 new columns ready for analysis.

Additional data I was unsure was marked for exclusion from the final dataset. 

A full description of the process: (insert: google_cyclistic_sql) 

## PHASE 4: ANALYSIS
### Key objectives:











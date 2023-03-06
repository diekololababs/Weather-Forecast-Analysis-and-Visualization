# Weather-Forecast-Analysis-and-Visualization
This repository contains details about the weather forecast project. SQL scripts for data cleaning and analysis for the above project. The project was initiated on LinkedIn by Aditya Sharma.


## :bookmark_tabs: Table of Contents
- 📝 About the Project
- 📂 Dataset
- 📙 Case Study Questions
- 🏆 Solution Script

## :memo: About the Project
Scientific weather forecasting relies on empirical and statistical techniques, such as measurements of temperature, humidity, atmospheric pressure, wind speed and direction, and precipitation, and computer-controlled mathematical models.


## :open_file_folder: Dataset
This data contains day wise weather attributes from 2022 to July 2033 (predicted data)

 <details><summary>View Dataset Columns</summary>
 <p> 
 
  Columns are as follows :
   - [ ] Date
   - [ ] Average temperature (°F)
   - [ ] Average humidity (%)
   - [ ] Average dewpoint (°F)
   - [ ] Average barometer (in)
   - [ ] Average windspeed (mph)
   - [ ] Average gust speed (mph)
   - [ ] Average direction (°degree)
   - [ ] Rainfall for month (in)
   - [ ] Rainfall for year (in)
   - [ ] Maximum rain per minute
   - [ ] Maximum temperature (°F)
   - [ ] Minimum temperature (°F)
   - [ ] Maximum humidity (%)
   - [ ] Minimum humidity (%)
   - [ ] Maximum pressure
   - [ ] Minimum pressure
   - [ ] Maximum wind speed (mph)
   - [ ] Maximum gust speed (mph)
   - [ ] Maximum heat index (°F)
</p>
</details>

*View the raw dataset:* [HERE](https://github.com/diekololababs/Weather-Forecast-Analysis-and-Visualization/blob/main/weather_dataset%20(raw_data)%20.xls)

## :closed_book: Data Cleaning Tasks
The Processes involved in the data cleaning are listed below; the data was cleaned using SQL:

 - Task 1: Correct years for given data set  
 - Task 2: removal of duplicate rows and duplicate columns
 - Task 3: fix a few labels in the given data set 
 - Task 4: encoding data into suitable format

## :closed_book: Case Study Analysis
Each of the following case study questions were derived from the data using SQL:

  1. Give the count of the minimum number of days for the time when temperature reduced.
  2. Find the temperature as Cold / hot by using the case and avg of values of the given data set.
  3. Can you check for all 4 consecutive days when the temperature was below 30 Fahrenheit.
  4. Can you find the maximum number of days for which temperature dropped.
  5. Can you find the average of average humidity from the dataset (NOTE: should contain the following clauses: group by, order by, date).
  6. Use the GROUP BY clause on the Date column and make a query to fetch details for average windspeed.
  7. If the maximum gust speed increases from 55mph, fetch the details for the next 4 days.
  8. Find the number of days when the temperature went below 0 degrees Celsius.
  9. Create another table with a “Foreign key” relation with the existing given data set.


 ## 	:trophy: Solutions
 *View the Data Cleaning scripts:*[HERE](https://github.com/diekololababs/Weather-Forecast-Analysis-and-Visualization/blob/main/Data%20Cleaning%20Script.sql)
 - [x] *View the clean dataset:* [HERE](https://github.com/diekololababs/Weather-Forecast-Analysis-and-Visualization/blob/main/Clean%20Date.csv)
  
  *View the Case Study Analysis scripts:* [HERE](https://github.com/diekololababs/Weather-Forecast-Analysis-and-Visualization/blob/main/Solution%20Script.sql)

## Flight DElay Analysis

### Objective:
The primary objective of this analysis is to explore, analyze, and identify key factors contributing to flight delays across the United States from 2019 to 2023.
By leveraging comprehensive data from the US Department of Transportation, the analysis aims to uncover patterns and correlations between various 
delay factors (such as weather, carrier issues, and late aircraft) and overall departure delays. The insights gained will help stakeholders, including airlines 
and policymakers, develop strategies to minimize delays, improve operational efficiency, and enhance passenger satisfaction.

### Data Source:
- Provider: US Department of Transportation, Bureau of Transportation Statistics
- URL: DOT On-Time Performance
- Content: Contains data on flight delays and cancellations for domestic flights in the 
US, covering flight routes, time ranges for events, and reasons for delays and 
cancellations.
- Time Period: January 2019 – August 2023
- Format: Monthly subsets, consolidated annually, processed using csvkit, Python, 
and Excel.

### Data Profile:
There are 3000000 rows and 32 columns in the dataset.
Variables with description:
-o FL_DATE: Flight date
-o AIRLINE: Airline code
-o AIRLINE_DOT: Airline DOT code
-o AIRLINE_CODE: Airline code (alternative)
-o DOT_CODE: Department of Transportation code
-o FL_NUMBER: Flight number
-o ORIGIN: Origin airport code
-o ORIGIN_CITY: Origin city name
-o DEST: Destination airport code
-o DEST_CITY: Destination city name
-o CRS_DEP_TIME: Scheduled departure time
-o DEP_TIME: Actual departure time
-o DEP_DELAY: Departure delay in minutes
-o TAXI_OUT: Taxi out time in minutes
-o WHEELS_OFF: Wheels off time
-o WHEELS_ON: Wheels on time
-o TAXI_IN: Taxi in time in minutes
-o CRS_ARR_TIME: Scheduled arrival time
-o ARR_TIME: Actual arrival time
-o ARR_DELAY: Arrival delay in minutes
-o CANCELLED: Cancellation indicator
-o CANCELLATION_CODE: Cancellation code
-o DIVERTED: Diversion indicator
-o CRS_ELAPSED_TIME: Scheduled elapsed time
-o ELAPSED_TIME: Actual elapsed time
-o AIR_TIME: Air time in minutes
-o DISTANCE: Distance between airports in miles
-o DELAY_DUE_CARRIER: Delay due to carrier in minutes
-o DELAY_DUE_WEATHER: Delay due to weather in minutes
-o DELAY_DUE_NAS: Delay due to National Airspace System in minutes
-o DELAY_DUE_SECURITY: Delay due to security in minutes
-o DELAY_DUE_LATE_AIRCRAFT: Delay due to late aircraft in minutes


### [Link to Tableau Storyboard](https://public.tableau.com/app/profile/femina.kallangadan/viz/flightdelayanalysis_17235940914290/nextstep?publish=yes)

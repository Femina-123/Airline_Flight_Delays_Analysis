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
- FL_DATE: Flight date
- AIRLINE: Airline code
- AIRLINE_DOT: Airline DOT code
- AIRLINE_CODE: Airline code (alternative)
- DOT_CODE: Department of Transportation code
- FL_NUMBER: Flight number
- ORIGIN: Origin airport code
- ORIGIN_CITY: Origin city name
- DEST: Destination airport code
- DEST_CITY: Destination city name
- CRS_DEP_TIME: Scheduled departure time
- DEP_TIME: Actual departure time
- DEP_DELAY: Departure delay in minutes
- TAXI_OUT: Taxi out time in minutes
- WHEELS_OFF: Wheels off time
- WHEELS_ON: Wheels on time
- TAXI_IN: Taxi in time in minutes
- CRS_ARR_TIME: Scheduled arrival time
- ARR_TIME: Actual arrival time
- ARR_DELAY: Arrival delay in minutes
- CANCELLED: Cancellation indicator
- CANCELLATION_CODE: Cancellation code
- DIVERTED: Diversion indicator
- CRS_ELAPSED_TIME: Scheduled elapsed time
- ELAPSED_TIME: Actual elapsed time
- AIR_TIME: Air time in minutes
- DISTANCE: Distance between airports in miles
- DELAY_DUE_CARRIER: Delay due to carrier in minutes
- DELAY_DUE_WEATHER: Delay due to weather in minutes
- DELAY_DUE_NAS: Delay due to National Airspace System in minutes
- DELAY_DUE_SECURITY: Delay due to security in minutes
- DELAY_DUE_LATE_AIRCRAFT: Delay due to late aircraft in minutes

### Project Structure:
Here’s a breakdown of scripts:
1.Data Sourcing and Preparation:
- Source and clean flight delay data from the US Department of Transportation.
- Define key questions for analysis.
- Document initial data cleaning and preparation steps.

2.Exploratory Analysis:
- Conduct exploratory visual analysis using Python.
- Define and test hypotheses based on initial data insights.

3.Geospatial Analysis:
- Source shapefiles for geographic data.
- Merge and clean location data with flight delay data.
- Create a choropleth map to analyze delays across different regions.

4.Supervised Machine Learning:
- Formulate a hypothesis for regression analysis.
- Select and prepare variables for linear regression.
- Split data into training and test sets, run the regression, and evaluate model performance.

5.Unsupervised Machine Learning:
- Prepare data for cluster analysis.
- Use the elbow method to determine the optimal number of clusters.
- Run k-means clustering, visualize clusters, and analyze descriptive statistics.

6.Time Series Analysis:
- Source relevant time-series data via an API.
- Visualize and decompose time series data, test for stationarity, and apply differencing as needed.


### [Link to Tableau Storyboard](https://public.tableau.com/app/profile/femina.kallangadan/viz/flightdelayanalysis_17235940914290/nextstep?publish=yes)

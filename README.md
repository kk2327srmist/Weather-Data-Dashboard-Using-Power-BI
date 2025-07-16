weather data is imported from weatherapi.com
data is imported to powerbi using WEB as source and collected data of 6 cities using API URL generated from weather.api.com for a period of 7days with air quality data
preprocessing:
appended 6 cities data into a single table called masterTable
Taking master table as reference to create
Current data: Removed data except current data
ForecastData_day: Removed current data and forecast data by hour columns
ForecastData_hour: removed current data and forecast data by day columns

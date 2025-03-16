# LocationCrossCheck
This code is for cross checking the country, location_name(city), latitude, longitude, and time zone.
(part of the weatherforecast data science assessment)

The data has 195 cities with 58000 rows, so Deepseek or ChatGPT was limited to use.
Therefore, I built this code to cross check all the information.

## About the code

1. Eliminate duplicate locations.
2. Read the Excel file using pandas.
3. Verify the city, latitude, longitude, and time zone using a reliable source (e.g., a geocoding API like Google Maps API).
4. Flag discrepancies and save the results to a new file.

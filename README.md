# solar_panel_predictor

Polynomial regression model to predict solar panel intensity using weather and geographic data. 

## Parameters:
- Weather data:
    - Average Temperature
    - Hours of daylight
    - Humidity
    - Precipitation
        - Cloud coverage
        - Inches of rain

- Theoretical solar intensity, depending on:
    - Latitude and Longitude
    - Day of year
    - Time of day

## Output:
- Predicted solar intensity (MW)
- Error score when compared to NREL recorded amounts

## Sources
Function for calculating the Solar Position and Intensity:
https://www.nrel.gov/grid/solar-resource/solpos.html
https://github.com/NREL/SolarPILOT/tree/21a1466398ec22db24a5a838e5133da58e347b83

Solar panel performance data:
https://www.nrel.gov/grid/solar-power-data.html

Weather data files:
https://www.ncdc.noaa.gov/cdo-web/

Plant-level Hourly Generation estimates:
https://catalog.data.gov/dataset/utility-scale-solar-2022-edition-analysis-of-empirical-plant-level-data-from-u-s-ground-mo/resource/d47f849f-ffc5-4356-8bae-5207fc9c8ba0

Actual PV power generation:
https://pvdata.nist.gov/


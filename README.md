# Python API Challenge

#### In this challenge I was asked to use Python and Jupyter notebook to:
- identify a set of more than 500 nearby cities from a randomly generated set of 1500 geocode location coordinates
- use the OpenWeatherMap API to collect temperature, humidity, cloudiness, and wind speed data for those cities
- identify any correlations between the collected data and the latitude of the cities
- find a nearby hotel in the cities that have great weather

#### What I found was this:
- In general, the maximum temperatures of cities increased as cities approached the equator. The apex temperatures appeared between latitude 20 and 40 where some maximum temperatures measured over 100F.
- In the Northern Hemisphere, there is a negative correlation between temperature and latitude.  The correlation between the factors is -0.62
- In the Southern Hemisphere, there is a positive correlation between temperature and latitude.  The correlation between the factors is 0.82
- In the Northern Hemisphere, there is no or negligible correlation between humidity and latitude.  The correlation between the factors is 0.04

![markermap](/VacationPy/output_data/markermap.png)
![reg_temperature_latitude_hemi_s](/WeatherPy/output_data/reg_temperature_latitude_hemi_s.png)



# City_bike_sharing_demand
 Bike Sharing Demand Analysis in Washington D.C.
Description:
Bike sharing systems redefine traditional bike rentals, automating the entire process from membership to rental and return. Users can effortlessly rent bikes from one location and return them to another, adding a new layer of convenience to urban transportation. These systems play a pivotal role in addressing urban challenges by contributing to traffic reduction, offering an alternative mode of transportation to alleviate congestion, especially in urban areas. Additionally, the widespread use of bikes as an eco-friendly mode of transport significantly reduces carbon emissions, fostering cleaner and greener urban environments. Moreover, by encouraging physical activity, bike sharing promotes a healthier lifestyle among users, positively impacting public health.

Objectives:
Conduct a comprehensive analysis of the Washington D.C. Bike Sharing dataset to uncover the correlation between the number of rented bikes and various factors, including temperature, season, and prevailing weather conditions.

Dataset:
While the dataset includes both daily and hourly data, our analysis specifically utilizes the daily count of rental bikes from 2011 to 2012 in Washington, D.C.'s Capital Bikeshare system along with corresponding weather and seasonal information.

Content:
The fields in both hour.csv and day.csv are identical, with the exception of the 'hr' field, which is not present in day.csv.

instant: Record index
dteday: Date
season: Season (1:springer, 2:summer, 3:fall, 4:winter)
yr: Year (0: 2011, 1:2012)
mnth: Month (1 to 12)
hr: Hour (0 to 23)
holiday: Weather day is holiday or not (extracted from Holiday Schedule)
weekday: Day of the week
workingday: If the day is neither a weekend nor a holiday, it is 1; otherwise, it is 0.
weathersit: (Extracted from Freemeteo)
1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
temp: Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
hum: Normalized humidity. The values are divided by 100 (max)
windspeed: Normalized wind speed. The values are divided by 67 (max)
casual: Count of casual users
registered: Count of registered users
cnt: Count of total rental bikes, including both casual and registered
Tools and Libraries:
Jupyter Notebook
Python
Libraries: Pandas, Matplotlib, Seaborn
Steps:
Data Loading and Preprocessing
Data Exploration
Data Visualization
Insights Documentation
Project Structure:
Link to Dataset

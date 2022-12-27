# surfs_up
A classwork example researching weather data using SQL with SQLite and SQLAlchemy

---

# Overview
This is a classwork example in which "I plan to open an ice cream and surf shop in Hawaii ". The investor has requested temperature information for the island that will eventually be home to the ice cream and surf shop. Using SQLAlchemy to connect to and query a SQLite database (hawaii.sqlite), I will present temperature information using graphs and a "bonus" Flask API script. 

## Purpose
I am providing a summary of temperature information to my investor to prove that my choice of location would allow customer demand to be consistent. By request, I will present results specifically from June and December. 

---

# Results
* June and December temperatures both show that, on average, the temperature rarely goes below 67 degrees F and rarely goes above 80 degrees F:</br>
![Jun_temp_screenshot](/jun_temp_graph.png)
![Dec_temp_screenshot](/dec_temp_graph.png)
* June temperatures are most frequently in the mid 70 degree range:</br>
![Jun_temp_freq_screenshot](/jun_temp_freq_graph.png)
* December temperatures are, on average, higher than June temperatures. Temperatures are most freqently in the mid to high 70 degree range:</br> 
![December_temp_screenshot](/dec_temp_freq_graph.png)

---

# Summary 
Temperature data from this island collected over the period of several years has shown that temperatures in this locality are consistent and stable. Temperatures rarely go beyond a range that is sufficient for customer comfort while surfing or while eating ice cream. 

However, it is important to note that Hawaii experiences a storm season that lasts from June to November each year. Heavy rains, winds, and sometimes even hurricanes are some of the natural risks that occur during this time of the year. I created additional queries to view total precipitation in June and in December. I also created an additional graphic to show correlation between temperature and precipitation for the months of June and December to see if precipitation happens more often at a particular temperature and if so if that temperature happens often. For additional query script: please see "SurfsUp_Challenge.ipynb".

* June precipitation levels have historically been low (with an exception for a storm in 2010), but in recent years precipitation has increased:</br>
![Jun_prcp_screenshot](/jun_prcp_graph.png)
* December precipitation levels are consistently high compared to June precipitation levels. Recent years also show an increase in precipitation:</br>
![Dec_prcp_screenshot](/dec_prcp_graph.png)
* Below is a correlation graph. Precipitation occurs most frequently when the temperature is close to 70 degrees F. Based on the frequency graphs (pictured above), this could pose as a problem, because both June and December frequently have days with temperatures around 70 degrees F:</br>
![correlation_screenshot](/correlation_graph.png)

At this time I would highly suggest further research into precipitation and temperature correlations for the whole year. I would also suggest that other months are examined - such as March and September - to see if temperatures fluctuate during other seasons of the year. 

---
## Additional Flask API
Just for fun: To view a list of temperatures based on date input, view and run "app2.py". 

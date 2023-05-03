# Team 4 QST IS 843
## Members:
### 1. Abhishek Malakar (Team Lead)
### 2. David Bartlett
### 3. Jifu Li
### 4. Zelin Zhao
### 5. Zhihao Zhang

## NYC Biking & Weather Analysis
### Motivation
##### Riding bikes (bicycles) have been a longstanding method of transportation for fitness enthusiasts, environmentalists, students, hikers etc. We were intrigued by the dataset and its in-depth record of trip analysis for bikers in NYC. Even though NYC is a city where the major mode of transportation for most people would be cars or public transport, the data presented for bikers is in itself really interesting. By analysing and understanding data related to cycling, we can gain insights into factors that impact cycling behavior, such as weather, infrastructure, and demographics. Additionally, bicycle data can be used to inform policy decisions and planning efforts aimed at promoting cycling and creating safer cycling environments. Working with a bicycle riding dataset can help us better understand this important mode of transportation and recreation.

### The following datasets have been used for the analysis and their EDA is provided through the notebook
####
1. NYC Citi Bikes dataset (https://console.cloud.google.com/marketplace/product/city-of-new-york/nyc-citi-bike)
2. Storms information (https://console.cloud.google.com/marketplace/product/noaa-public/severe-storm-events)
3. Extreme weather datasets (https://console.cloud.google.com/marketplace/product/noaa-public/preliminary-storm-reports)
4. NYC 311 Calls Dataset (https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=new_york_311&page=dataset&project=is-843-project-t4)
5. NYC weather dataset(https://github.com/zonination/weather-us)
### Through this analysis we will be answering the following questions 

#### 
1. Given the bike rides dataset and weather dataset let us analyse the co-relation between weather conditions of the day and the biking behvior 
2. Given the storm dataset and bike rides dataset perform an analysis on the effect of harsh stormy weather conditions on bikes being rented (Keep in mind outliers by performing box selection of only area of NYC)
3. Given the bikes dataset and 311 calls dataset perform an analysis on Relation between Safety/Traffic issue calls on the rental of bikes. Perform this analysis in the form of designing scatter plots to analyse weather there is a change in rentals in areas having higher concerns.
4. Given the bikes dataset and 311 calls dataset analyse if on months having more number of safety/traffic concerns were the number of bike rentals co-related to the same or not? (Please note that accuracy of this question comes into question as the analysis is solely being done on a monthly aggregate basis without bringing into question accurate location information and only as a collective. For future goals the analysis can be done on a simple location basis)
5. Perform an analysis on the bikes dataset to find out which station ids were most or least popular through different days.
6. Given the bikes dataset and the extreme weathers dataset form an analysis on the question "do drops in bike rentals correspond to reported bad weather events?"

### Special Thanks to:
1. City of New York and Google for providing the datasets used for this analysis
2. ChatGPT and Open AI team for providing us with helpful resources and quick resolutions to problems we are stuck with. ChatGPT was only used to know about how certain logics could be performed especially in sections of scatter plots and line charts to overlay images
3. Stackoverflows.com

##### The above are to be considered as the resources we used

## Conclusion

The analysis of the biking dataset has provided valuable insights into bike rental patterns in New York City. One of the key findings was the identification of the specific stations that are most frequently used as start and stop stations. This information can be used to improve the availability of bikes in those areas and ensure that the stations are well-maintained.

The analysis also revealed that extreme weather conditions have a significant impact on bike rentals. During storms, people were less likely to use bikes in most areas of the city, except for outliers where people may have left bikes at stations until the storm subsided. Additionally, people were more likely to rent bikes during months with pleasant weather conditions, rather than during months that were too hot or too cold.

The analysis of 311 calls provided further insights into bike rental patterns in the city. The data showed that people are less likely to rent bikes in areas with unexpected traffic conditions or safety concerns. This information can be used to improve bike rental systems and increase the convenience and safety of biking in New York City.

Finally, the use of ML models provided accurate predictions of future bike rentals based on previous data. These predictions can be used to plan for increased demand during certain times of the year or during events that may affect bike rental patterns. Overall, these findings can be used to improve bike rental systems, increase the convenience and safety of biking in New York City, and promote the use of sustainable transportation options.

## Challenges Faced

Ensuring the quality, accuracy, and completeness of the data was a significant challenge, especially as we were dealing with massive datasets.

Integrating and merging multiple datasets from different sources was a challenge, particularly as they were structured differently or contained different levels of granularity.

Normalizing the data to a consistent format was challenging, particularly dealing with different units of measurement or time zones.

Processing and handling a vast amount of data was resource-intensive and time-consuming.

Dealing with weather data posed additional challenges, such as handling various types of weather events, such as storms, heatwaves, and snow.

Developing and implementing appropriate analytical models and techniques was a significant challenge, particularly as we were dealing with complex datasets.
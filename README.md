# US-Accidents-EDA

## ***Goal of the Project:*** 📃
The goal of this project is to investigate various attributes and trends on temperature, weather condition, traffic signals that affect the accidents occuring.The data is  collected from 49 states of the United States of America over the period between February 2016 and December 2020. 

## Dataset:-
The dataset used for the project is [US Accident Dataset Link](https://www.kaggle.com/sobhanmoosavi/us-accidents). 

- Datasize: ~3M entries
- Time period: February 2016 to December 2019
- Scope: 49 US states

## ***Steps Followed*** :pen:

1. Selected a large dataset from Kaggle.

2. Performed data preparation and Cleaning using Numpy and Pandas.

3. Performed EDA and Visulization using Matplotlib and Seaborn.

4. Ask and answer question on the data

5. Summarize the inferences.

## Data Cleaning:
- Select important features and remove unnecessary columns.
- Remove the rows with null values.
- Do data profiling to validate correctness of data.

## Data Preprocessing:
- Convert columns with text field to numerical data.
- Categorized weather conditions
- Eliminated rows that greatly contributed to the imbalance of the data and were not significant in volume
- Replaced null values with fillers

### Data Overview:-
#### We will first discuss about each attribute and discuss what it stands for:
- ID:- A unique identifier for each accident.
- Source:- The source which reported the accident.
- TMC:- It is Traffic Messagen Channel which providea more detailed description of the event.
- Severity:- The level of impact of the accident. 1 being the lowest and 4 being the highest.
- Start_Time:- Shows start time of the accident in local time zone.
- End_Time:- Shows end time of the accident in local time zone.
- Start_Lat:- Shows latitude in GPS coordinate of the start point.
- Start_Lng:- Shows longitude in GPS coordinate of the start point.
- End_Lat:- Shows latitude in GPS coordinate of the end point.
- End_Lng:- Shows longitude in GPS coordinate of the end point.
- Distance(mi)-: The length of the road extent affected by the accident.
- Description:- The description of the accident.
- Number:- Street Number
- Street:- Street Name
- Side:- Relative side of the address field.
- City:- Name of the City.
- County:- Name of the county.
- State:- Name of the state.
- Zipcode:- Zipcode of the address
- Country:- Name of the country
- Timezone:- Timezone of the location where accident occurred
- Airport_Code:- Denotes an airport-based weather station which is the closest one to location of the accident.
- Weather_Timestamp:- Shows the time-stamp of weather observation record
- Temperature(F) :- Temperature in Fahrenheit
- Wind_Chill(F):- Wind chill in Fahrenheit
- Humidity(%):- Humidity in percentage
- Pressure(in):- Air pressure in inches
- Visibility(mi):- Visibilty in miles.
- Wind_Direction:- Wind direction
- Wind_Speed(mph):- Wind speed in miles per hour.
- Precipitation(in): -Precipitation in inches.
- Weather_Condition: Shows what was the weather that day, i.e., if it was rainy, sunny, etc.
- Amenity:- A Point-Of-Interest (POI) annotation which indicates presence of amenity in a nearby location.
- Bump: Tells whether there was any bump on the road.
- Crossing:- Tells whether there was any corssing on the road.
- Give_Way:- Tells whether there was any give-way sign on the road.
- Junction:- Tells whether ther was any junction present.
- No_Exit:- Tells whether there was any no-exit sign on the road.
- Railway:- Tells whether ther was any railway present nearby.
- Roundabout:- Tells whether ther was any roundabout present nearby.
- Station:- Tells whether there was any sytation present.
- Stop:- Tells whether there was any Stop sign on the road.
- Traffic_Calming:- Tells whether ther was any Traffic-calming means present nearby.
- Traffic_Signal:- Tells whether there was any taffic signal nearby.
- Turning_Loop:- Tells whether there was any turning loop nearby.
- Sunrise_Sunset::- Tells us the period of the day based on sunrise or suset.
- Civil_Twilight:- Tells us the period of the day based on civil twilight.
- Nautical_Twilight:- Tells us the period of the day based on nautical twilight.
- Astronomical_Twilight:- Tells us the period of the day based on astrnomical twilight.


# ***Tools Used*** :hammer_and_pick:

![](desktop/images.png)

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="70" height="70"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="70" height="70"/> </a> <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" width="70" height="70"/> </a> <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://miro.medium.com/max/805/1*aUSZsGFCMPNYCkQygs4aGQ.jpeg" width="100" height="70"/> </a>

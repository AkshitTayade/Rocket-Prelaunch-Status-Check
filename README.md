# Rocket-Prelaunching-Status
After giving various Technical and Weather condition before prelaunch, Model predict if its suitable for GO-NO GO launch for rockets.

<img align="right" alt="GIF" src="https://github.com/AkshitTayade/Rocket-Prelaunch-Status-Check/blob/master/media/main.gif" width="500" height="300" />

### What is this project about ?
* How Machine Learning can be used in Space?
* The challenges weather can pose on shuttle launches. 

### Space Centres collects data from a wide range of sources, including:
*	NOAA Weather
*	Satellite imagery
*	Remote sensors
*	Weather pattern experts

<br>

> #### Nasa has a documentation on  Weather Launch Commit Criteria which can be read [here](https://www.nasa.gov/centers/kennedy/news/releases/2003/release-20030128.html)


### Some key factors that dataset takes into account regarding launches are:
* Surface electric field
* Temperature during Launch time
* Weather Conditions
* Cloud temperature
* Precipitation intensity
* Rocket velocity

## This project will be performed in 4 steps :

### 1. Data Pre-processing 

*	Data Cleaning 
Firstly we do some data exploration of our dataset. After looking at dataset, we find missing values in lot of columns. 
So the question is how to fill this missing values? 
We check the information of each individual column.  Then fill the NULL values with appropriate values (i.e. mean or average ).

*	Data Transformation
Now that we have complete dataset ready. Some of the columns are in string format, which cannot be interpreted by Machine Learning algorithms. Some string has to be transformed into numerical values. And this will be done using LabelEncoder function which is inbuilt in sklearn.

*	Data Reduction
Finally we have clean float type dataset available with us. But we do not need some columns as they make no significant impact on data patterns. So we will eliminate them.


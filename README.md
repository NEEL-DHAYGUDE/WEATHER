# WEATHER
WEATHER DATA ANALYSIS AND PREDICTIONS (NEEL DHAYGUDE)
PROJECT DESCRIPTION

The project talks about weather reports dataset analysis and prediction using machine learning and data visualization to analyze global and local weather patterns, focus on temperature and air quality. The project aims to generate insights about temperature, air quality level, and how they relate to geographic variables like latitude, longitude, and country. The project encompasses various modules for data manipulation, trend analysis, prediction, and visualization with real-time data. Various machine learning algorithms are used for modeling the relationship between different features of the dataset and prediction of both global and country-specific temperature and air quality. 

METHODOLOGY 

The methodology includes several steps: 

Data Collection and Preparation: The dataset was downloaded and unzipped for local processing. The dataset contains temperature, air quality, geographical coordinates (latitude, longitude), and weather-related features across several countries.

Data Visualization:

Basic scatterplots and pair plots were created to understand the relationship among temperature, air quality, latitude, and longitude.
Boxplots were constructed to examine the distribution and frequency of temperature and air quality measurements.
Violin plots and bar plots were drawn to analyze the air quality distribution across different countries.

Country-wise Analysis: A sample consisting of the first five countries was used to generate the bar plots and multi-value box plots to compare the temperature and air quality within those regions.

Linear Regression for Global and Country-wise Trends:

Linear regression models were used to establish trends in temperature and air quality over time.
A time index representing the passage of time over the dataset using that time index was utilized for predicting temperature and air quality in future instances.
Regression models were trained on linear regression to analyze trends and were transformed using a StandardScaler to standardize the data for model training.

Prediction:

Models for prediction were constructed using both global (mean level) temperature and air quality variation together with country-based temperature and air quality variation.
The future prediction model was developed to forecast temperature and air quality over the next several days, based on historical data. 

RESULTS

Temperature vs Latitude and Longitude: The scatter plots and pair plots corroborated the geographical influence of temperatures.
Air Quality: The boxplots emphasized the differences in the quality of air (PM2.5 and PM10) found across countries with extremely different air qualities.
Country-wise Analysis: Visualizations for the top 5 countries demonstrated the regional differences in temperature and air quality with distribution patterns.
Global Temperature and Air Quality Trends: Linear regression models suggested a unidirectional development for both temperature and air quality.
Similar features seen in individual country data.
Assumed accurate predictions made on future trend of such values

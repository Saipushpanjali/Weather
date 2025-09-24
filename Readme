Used kaggle to get the dataset on wether.(https://www.kaggle.com/datasets/prasad22/weather-data)

It contains weather records from different cities.

Columns include:

Location → City name
Date_Time → Timestamp of observation
Temperature_C → Temperature in Celsius
Humidity_pct → Humidity in percentage
Precipitation_mm → Rainfall in millimeters
Wind_Speed_kmh → Wind speed in kilometers per hour


Task 1:Load and Inspect Data

Loaded the dataset using pd.read_csv()
Checked shape and displayed the first few rows and checked the datatypes


Task 2: Data Cleaning 

Converted Date_time to datetime format using pd.to_datetime()
Removed missing values
Confirmed all columns were clean


Task 3: Descriptive Statistics with NumPy

Used NumPy functions: np.mean(), np.median(), np.std(), to calculate mean, median and standard deviation of Temperature, Humidity and Precipitation
Descriptive Statistics:




Task 4:Monthly and Seasonal Analysis (Using Pandas Group By)

Extracted Month and Season from Date_time.
Grouped by Month→ calculated average temperature, humidity, precipitation.

Grouped by Season→ compared seasonal averages (e.g., higher temperatures in summer, higher rainfall in rainy months).



Task 5:Visualizations with Matplotlib

Line Plot → Monthly average temperature trend.
Bar Plot → Average precipitation by month.
Histogram → Distribution of daily temperatures.


Task 6:Identify Extreme Weather

Defined thresholds using percentiles:

Extreme Hot → above 90th percentile of temperature
Extreme Cold → below 10th percentile of temperature
Extreme Rainy → above 90th percentile of precipitation
Filtered rows meeting these conditions.

Counted extreme days using .shape[0]






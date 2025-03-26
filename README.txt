Research Question:
"How effectively can a combination of meteorological attributes, atmospheric conditions, and visibility factors predict weather type, and which features play the most significant role in distinguishing between different weather categories?"

Objective:
The objective of this study is to build a classification model that predicts the weather type using a combination of meteorological, atmospheric, and environmental attributes. By identifying the most influential features, this research aims to enhance the understanding of weather patterns, improve forecasting accuracy, and aid decision-making in weather-dependent domains such as agriculture, transportation, and disaster management.

Target Variable:
Weather Type - This variable categorizes weather conditions into specific types, serving as the classification target for our model.

Features:
The dataset includes 14 predictive attributes categorized into four main groups, which will be utilized to predict the weather type.

Meteorological Attributes:

Temperature: Represents the atmospheric temperature in degrees Celsius.
Humidity: Measures the amount of water vapor in the atmosphere, expressed as a percentage.
Wind Speed: Indicates the speed of the wind in kilometers per hour (km/h).
Precipitation (%): Reflects the likelihood of precipitation as a percentage.
Cloud Cover: Represents the fraction of the sky obscured by clouds.

Atmospheric Conditions:

Atmospheric Pressure: Measures the pressure exerted by the atmosphere, typically in millibars.
UV Index: Indicates the level of ultraviolet radiation on a given day, on a scale from 0 (low) to 11+ (extreme).

Environmental and Visibility Factors:

Season:A categorical variable representing the season during which the data was recorded.
Visibility (km): Measures the horizontal distance at which objects can be clearly seen.
Location: Denotes the geographical area where the data was collected.

Derived and Related Metrics:

Heat Index: A derived metric indicating how hot it feels when accounting for both temperature and humidity.
Precipitation Intensity: Represents the intensity of precipitation during the recorded period.

Excluded Variables:

Dew Point: A metric indicating the temperature at which air becomes saturated with moisture, excluded due to redundancy.
Wind Chill: The perceived decrease in air temperature due to wind, excluded for its lack of direct predictive value for weather type classification.

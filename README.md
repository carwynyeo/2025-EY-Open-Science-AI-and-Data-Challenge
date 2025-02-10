# 2025-EY-Open-Science-AI-and-Data-Challenge
Being an absolute unit, creating the best machine learning model.

The goal of the challenge is to develop a machine learning model to predict heat island hotspots in an urban location. 

Additionally, the model should be designed to discern and highlight the key factors that contribute significantly to the development of these hotspots within city environments.

Contributors:

Terms of Use and Licensing requirements for the datasets:

Training Data:

Description: Ground temperature data over New York City on July 24, 2021 (CSV format)
Contributors: Climate, Adaptation, Planning, Analytics (CAPA) Strategies
Data Host: Center for Open Science - https://www.cos.io
Terms of Use: https://github.com/CenterForOpenScience/cos.io/blob/master/TERMS_OF_USE.md
License: Apache 2.0 > https://github.com/CenterForOpenScience/cos.io/blob/master/LICENSE
Satellite Data (Sentinel-2 Sample Output)

Description: Copernicus Sentinel-2 sample data from 2021 obtained from the Microsoft Planetary Computer (TIFF format)
Contributors: European Space Agency (ESA), Microsoft
Data Host: Microsoft Planetary Computer - https://planetarycomputer.microsoft.com/dataset/sentinel-2-l2a
Terms of Use: https://sentinel.esa.int/documents/247904/690755/Sentinel_Data_Legal_Notice
License: https://creativecommons.org/licenses/by-sa/3.0/igo/
Building Footprint Data

Description: Building footprint polygons over the data challenge region of interest (KML format)
Contributors: Open Data Team at the NYC Office of Technology and Innovation (OTI) - New York City Open Data Project
Data Host: https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh
Terms of Use: https://www.nyc.gov/html/data/terms.html and https://www.nyc.gov/home/terms-of-use.page
License: https://github.com/CityOfNewYork/nyc-geo-metadata#Apache-2.0-1-ov-file
Weather Data

Description: Detailed weather data collected every 5 minutes at two locations (Bronx and Manhattan). Includes surface air temperature (2-meters), relative humidity, average wind speed, wind direction, and solar flux.
Contributors: Contributors: New York State Mesonet
Data Host: https://nysmesonet.org/
Terms of Use: https://nysmesonet.org/about/data
License: https://nysmesonet.org/documents/NYS_Mesonet_Data_Access_Policy.pdf




Note: Participants are strictly prohibited from using Longitude and Latitude values as features in building their machine learning models. Submissions that employ longitude and latitude values as model features will be disqualified. These values should only be utilized for understanding the attributes and characteristics of the locations.

Incorporating latitude and longitude data in their raw forms or through any form of manipulation—including multiplication, embedding, or conversion to polar coordinates—as predictive features in your model is strictly prohibited, as it can compromise the adaptability of your model across diverse scenarios. This prohibition extends to calculating the distance from a reference point and using it as a feature, which is essentially a transformation of the original geographical coordinates into a new feature form. Submissions that include these types of features will be considered non-compliant and will be disqualified.

# Table of Contents
1. [Introduction](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#introduction)
2. [Task](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#task)
3. [Data](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#data)
4. [Data Processing and Cleaning](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#data-processing-and-cleaning)
5. [Analysis](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#analysis)
7. [Findings](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#findings)
8. [Recommendations](https://github.com/valeria-jimenez/cyclistic-python?tab=readme-ov-file#recommendations)

# Introduction
* This case study is a part of the Google Data Analytics Course Capstone, originally based on [this case study](https://artscience.blog/home/divvy-dataviz-case-study).
* Cyclistic is a Chicago-based bike share company with about 4 million customers. In order to increase revenue, they sought to maximize annual memberships.

# Task
* The goal of this analysis was to find out how members differ from casual (non-annual members) riders in order to convert casual riders to members and increase revenue.

# Data
* The data is provided by Google as part of the Google Data Analytics Certification course. It has bike-share information from January 2021 to December 2021.

# Data Processing and Cleaning
* Times were converted from string objects to datetime objects.
* New features were created from existing features (duration of ride, day of week, month, and hour of trip initiation)

# Analysis
* The detailed analysis can be seen [here](https://github.com/valeria-jimenez/cyclistic-python/blob/main/cyclistic.ipynb).

# Findings
* Members
  * Trips made: 55.4% of 2021 trips
  * Favorite Station: Clark St & Elm St
  * Peak Time: 17:00
  * Rush Hour: Morning and Evening
  * Peak Season: Summer
  * Low Season: Winter
  * Ride Length: Stable throughout the year

* Casual Riders
  * Trips made: 44.6% of 2021 trips
  * Favorite Station: Streeter Dr & Grand Ave
  * Peak Time: 17:00
  * Rush Hour: Evening
  * Peak Season: Summer
  * Low Season: Winter (more drastic downturn than members)
  * Ride Length: Peaks during weekends
  * Casual riders out-ride members during the peak season

# Recommendations
1. Tap into different types of riders
  1. Commuter Membership
     * Targets existing members and potential members
     * Offer priority usage morning and evening rush hour

  2. Recreational Membership
     * Offer priority usage during weekends
     * Introduce special rates or promotions for weekend rides
     * Allow users to bring friends on rides at reduced rates (since use is mostly recreational, it could be likely that users typically ride with others)

2. Tap into seasonality in ridership
* Introduce incentives (ex. discounted membership) for users who sign up to be members during the low season

# HarriganKrejsa_ENV872_EDA_FinalProject
Environmental Data Analytics (ENV 872) final class project, Spring 2021, Duke University

Elise Harrigan and Katie Krejsa

This study focused on understanding the use of elephant trails and the frequency of travel on these trails. We analyzed the condition of trail as poor, medium or heavy trodden, the width of the trail, and the use denoted by the start, stop or change direction in the trail. We aimed to answer the following questions to gain information on the activity level of elephants and the use of the trails.

1. What is frequency and number of days traveled on each trail? 
2. What is the condition and use of the trail?


We received these two datasets from Dr. Amelia Meier (Duke University).

IV_tracklogs.csv:
This dataset includes the tracklogs of elephants, which is the GPS device recording where the field teams were walking. 
Dates of tracklogs: Feb 2018 - May 2018
Data contained in this dataset: site, date, time, latitude, and longitude (everything is in decimal degrees WGS84)

IV_wpts.csv:
This dataset includes the waypoints taken by field teams when they started walking on an elephant trail or if the elephant trail changed characteristics. 
Data contained in this dataset:
Date
Time
Latitude and longitude
name (includes start or stop if the team got on or off a trail, trstart or trstop if the trail itself started or disappeared, change if a characteristic of the trail change, jct if they came to a trail crossing)
sym (the symbol used in the GPS)
cmt (there are two sets of information here a letter (P = poor, M = medium, H = heavy) representing how heavily trodden the path is and a number representing the width of the trial in cm. If the cmt section is blank then the details previously recorded remained the same.)


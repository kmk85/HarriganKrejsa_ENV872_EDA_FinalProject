# HarriganKrejsa_ENV872_EDA_FinalProject
Environmental Data Analytics (ENV 872) final class project, Spring 2021, Duke University

Elise Harrigan and Katie Krejsa

For this project, we aim to explore how forest elephants are using trails in Gabon. We received these two datasets from Dr. Amelia Meier (Duke University).

IV_tracklogs.csv:
This dataset includes the tracklogs of elephants, which is the GPS device recording where the file teams were walking. 
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


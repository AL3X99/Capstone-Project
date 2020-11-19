# Capstone-Project

This project aims to identify the safest place to park your bike in Toronto, Canada. 
The report is targeting bikers of any kind, whether BMX, Electric, classic bicycles etc. to understand where they can drive and park safely. Moreover, this could also serve as a potential route planner for the bikers, to ensure they are driving at safe routes with limited risks of crime.
Data science is implemented to analyse the data and focus on safest neighbourhoods for biking. 

Based on the problem definition, the below factors will influence the final decision point:
-	finding safest area of Toronto based on Bicycle Thefts statsics as recorded by Toronto State Police
-	Choosing the safest area/neighbourhood 

Toronto’s geographical coordinates will be used to plot the neigbourhoods in a borough, to thus determine the safest place. Finally, we will cluster those neigbourhoods and then present the findings.

Data sources to be used:
-	Part 1 https://data.torontopolice.on.ca/datasets/bicycle-thefts - real world data set from Toronto Police Service, covering bicycle thefts from 2014 – 2019
-	Part 2 https://en.wikipedia.org/wiki/List_of_neighbourhoods_in_Toronto from Wikipedia, full list of categorized boroughs in Toronto. This will be utilized for mapping the dataset and assigning it to each neigbourhood and borough
-	Part 3 – using OpenCage Geocoder, will will find the safest borough. Thereafter, we will explore the neighborhood chosen and plot it on the maps. This will be done using Folium. Finally, a exploratory analysis will complete part 3
-	Part 4 – A new data set is created, consisting of neigborhoods and borougs and coo-ordinets clusetered and plotted in the maps

Data science tools will be utilized to analyse data, focusing on the safest borugh – exploring neigboorhoods and identifieny the 10 most safest in each of neighboords, to thus decide where the safest place to park your bike will be.


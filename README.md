# BTT-Orbital-Insihgt-Project
## Project Write-Up

1) Outline the problem that you were working to solve in your AI Studio project.
In our AI Studio project, we were trying to find out if typhoons have a strong effect on Shanghai’s shipping port, the busiest port in the world. We wanted to use the findings to show the potential disastrous results of more numerous and destructive typhoons on the world, which can come as a result of climate change.
 

2) Outline your approach to solving the problem.
To solve this problem, we broke down three main data points that we would need to add to the dataset or calculate: dwell time (how long a ship remains at port), draught (how far down a ship is in the water, which indicates whether it is loaded or unloaded) and whether or not a typhoon occurred. After this, we worked through which model selection would be best, and we landed on regression. Afterwards, all we had to do was test.
 

3) Describe your dataset and how it was obtained.
For our project, we used AIS data which described the geospatial location, characteristics, and destination of ships at Shanghai’s shipping port in the month surrounding Typhoon Lekima. Orbital Insight provided the datasets from us, which they obtained using AIS receivers that receive pings from ships with all the information included in the dataset. 

4) Showcase Impact with data.
While we didn’t have enough time to tweak our model to make accurate predictions concerning dwell times and the occurrence of a typhoon, we did notice a trend within our data. On the days surrounding the occurrence of the typhoon, there was a sharp dip before a sharp rise in the number of ships anchored at Shanghai’s shipping port.

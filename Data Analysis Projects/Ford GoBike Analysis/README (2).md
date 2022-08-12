# Ford Gobike Data Analysis
## by Chisom Ibezim


## Ford GoBike Trip Data

The Ford GoBike system is an integral part of the Bay Area’s transportation network. With more than 300 stations and 3,000 bikes on the ground across San Francisco, San Jose, Berkeley, Oakland and Emeryville, the system has generated over two million rides since launching in June 2017. [MTC (2022)](https://mtc.ca.gov/news/ford-gobike-ramps-ebikes#:~:text=About%20Ford%20GoBike,since%20launching%20in%20June%202017.)

This dataset contain information about trips taken using the Ford GoBike for the month of february in 2019 in the San Francisco Bay Area. Some useful features contained in this dataset include trip duration, start time, end time, start station_id, end station id, bike user id, etc.


## Summary of Findings

From the data exploration, I observed that a the quantitative variables in the dataset are positively skewed. Using a doughnut chart, I found out that 75% of bike users for that period were males. Using a barchart, I found out that over 85% of the bike users are `subscribers`. Exploring further, I found out, using a scatterplot, that a positve linear relationship exists among the 3 quantitative variable in the dataset. However, only `duration_min` and `distance_in_km` showed a strong positive relationship. 


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

For the presentation, I focus on just the influence of `distance_in_Km` on `duration_min`. I start by introducing the `duration_min` variable, followed by the distribution of `duration_min` variable, distribution of `distance_in_km` variable and finally plot scatterplot to display the positive relationship between them.   
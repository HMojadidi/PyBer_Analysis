# PyBer_Analysis
# PyBer_Challenge:

## Overview:
In preparing a data analysis presentation for the CEO of PyBer, a major ride-sharing company, I am required to use my Python skills and knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type (Urban, Suburban and Rural). Then using Pandas and Matplotlib, I will create a mutlitple-line graph that shows the total weekly fares for each city type. In this accompanying report, I will be discussing how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results:

### Deliverable 1: 

#### Getting a Summary DataFrame

The PyBer Challenge had started off by merging two .csv files to create a DataFrame. From that DataFrame, I went on to create a new one called the 'pyber-summary_df' which would calculate the total rides, total drivers, total fares, average fare per ride, and average fare per driver. I also formatted the calculations to make sure they looked presentation-worty.

![Screen Shot 2022-03-29 at 12 30 48 AM](https://user-images.githubusercontent.com/95712234/160533572-bb8ede78-696b-4ebc-973b-410a79969179.png)

As the Summary DataFrame results show, the Urban cities has the lead in total rides, total drivers, produced the highest fares total, but were charging less as average fare per ride and average fare per driver. The opposite was true for Rural areas which had the least numbers in total rides, total drivers, total fares, yet charged the most in average fare per ride and average far per driver. The Suburban areas fell in the middle consistently with these five categories. 

### Deliverable 2: 

#### Create a multiple line plot that shows the total weekly of the fares for each type of city

Using Pandas and the functions pivot() and resample(), I created a multi-line graph that shows the total fares for each week by city type. Using the loc method, a new DataFrame was formed on the date range 2019-01-01 through 2019-04-28. The resample() function helped resample the data into weekly bins and then applying the sum() method I got the total fares for each week. 


![Screen Shot 2022-03-29 at 12 43 37 AM](https://user-images.githubusercontent.com/95712234/160534902-076096a0-a59c-4ab9-ad08-f21f7bc8ed80.png)


![Screen Shot 2022-03-29 at 12 44 36 AM](https://user-images.githubusercontent.com/95712234/160534995-8be67855-17b9-4bde-bb83-dc01c250ef07.png)


As can be seen, in the above graph, The Urban cities produced the highest total in weekly fares, followed by the Suburban cities and lastly trailed by the Rural areas. 

## Summary:

Upon review of the above DataFrames and graph, one can conclude that the higher availability of drivers keeps the cost of fares per ride and per driver low in Urban areas. In contrast, the lower number of drivers in the Suburban cities and even more so in Rural areas, gave drivers the opportunity to charge more for their trips per ride and per driver. One can conclude that the a higher availability of drivers could produce more income in total fares while keeping the fares lower. A recommendation would be to suggest further investigate how increasing the number of drivers in rural and suburban areas could generate more profits for the company. One can also look into incentives for hiring more drivers in rural and suburban areas in order to increase profit and make ride-sharing more accessible. 

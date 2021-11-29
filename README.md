# surfs_up

## Overview
The purpose of this statistical analysis was to take a look at the weather data in order to determine if Oahu, Hawaii is a good island to set up a surf shop. We need to make sure that there are enough good weather days to justify opening up a shop. We explored advanced data storage and retrieval on temperature trends and specifically looked at the months of June and Dececember to determine whether the business could operate year-round as opposed to only seasonly.

## Features and Data Sources
- Data Source: hawaii.sqlite
- Software: Jupyter Notebook, Flask, SQLite, Python 3.8.8
- Data Tools: SQLAlchemy, Pandas, Numpy, Matplotlib

## Results
Let's take a look at the differences in weather between the months of June and December.

The image below shows the summary statistics for the month of June.

![June](https://github.com/RyleeJensen/surfs_up/blob/main/Images/June_Temps.png)

The image below shows the summary statistics for the month of December.

![Dec](https://github.com/RyleeJensen/surfs_up/blob/main/Images/December_Temps.png)

- Key differences between the two months:
  - The average recorded temperature for the month of June is about 75 degrees Fahrenheit. Which is 4 degrees higher than the average temperature for the month of December.
  - June's lowest recorded temperature was 64 degrees, while December's lowest temperature got all the way down to 56 degrees.
  - The highest temperature was actually quite similar between the two months, with June's being 85 degrees and December's being 83 degrees.

## Summary
Although it seems like the temperature varies a bit more in the month of December than the month of June, both months would provide very suitable weather for a surf and ice-cream shop. The shop would be able to be open to the public year-round, making it rather profitable. However with that said, it wouldn't hurt to have a couple additional queries to make sure the right decision is being made. Looking at June and December definitely give us a decent idea of the weather for the summer and winter months, but I would also look into the summary statistics of all twelve months and compare them against each other. This would provide a more clear picture of what months the surf and ice-cream shop would really excel, and what months might not be ideal. Finally, while temperature is certainly important in determing whether people are going to surf and eat ice-cream, there are a few other weather factors that would be important to consider. These would include figuring out the average wind speeds for the months, precipitation, and even wave data. All of these certainly play a big role in the decision for people to come out to a surf and ice-cream shop, or stay inside for the day. With all of these other queries looked into, it would help make the final decision on opening the shop in Oahu, Hawaii or not.



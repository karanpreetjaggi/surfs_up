# SURFS UP
## Overview
The project started with W.avy wanted to open different shops in Oahu based on precipiation, station and temperature data. He wanted to compare the data for the current year to the previous year to weigh out his chances of opening an ice cream and surfing shops primarily. We used SQLAlchemy,SQLITE and Matplotlib along with jupyter notebook and vscode as data tools to analyze and present the data to him.
Once the data was presented to him regarding the most active station -its precipitation levels and temperature comparisons, he decided to narrow the temperature data to just 2 months. 
The purpose of this next part of the project was to get more information before opening the surf shops especially in month of June and December to make sure that the surf and ice cream business is sustainable all year around in Oahu.

## Methodology
We used the above mentioned tools (SQLAlchemy,SQLITE and Matplotlib along with jupyter notebook and vscode) and filter the temperature information for the month of June and December for all year. This provided us a good idea of the average temperatures in June and December to do a comparison. Attached, are the screeshots of the temperatures for both months across all the year.

![JuneTemp](https://user-images.githubusercontent.com/76858662/109695886-74b19400-7b5a-11eb-92e6-5947dafdeff6.PNG)

![DecTemp](https://user-images.githubusercontent.com/76858662/109695535-01a81d80-7b5a-11eb-9296-e51fe3739e2e.PNG)

## Results
Looking at the data, month of June has average higher temperature of 74 vs 71 in month of December. Also, June has the highest temperature of 85 and lowest temperature of 64 vs Decemeber, which has the highest temperature of 83 and lowest is 56.

![June](https://user-images.githubusercontent.com/76858662/109693219-6b72f800-7b57-11eb-85c0-4ace68045eda.PNG)

![Dec](https://user-images.githubusercontent.com/76858662/109692736-dc65e000-7b56-11eb-8b10-4ca214c64ac0.PNG)

## Summary
The max temperatures are comparable but min temperatures have a difference of 8 degree which is quite significant and can turn into pretty cold weather in winter. I think we should add stations to see the temperature variance for various stations and pick the best site with highest min, max and average temp. I also think he should look into the time of the day (morning vs afternoon vs evenings) to make an informed decision of where to open the shops and what should be the operating hours to make the most profit from his new business. 





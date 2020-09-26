<h1 align = "Center"> PyBer in the City
</h1>

<p align = "center">
<img src = "https://img.yle.fi/uutiset/kotimaa/article9708622.ece/ALTERNATES/w960/uber%20kuljettaja" width = "700" height = "300">
 </p>

## Analysis Overview

I was tasked by the ride sharing app Pyber to leverage some 2019 data (during the months of January to April) to gain some insights looking at three disctinct city types: Rural, Suburban and Urban. With this dataset, I will use Pandas and Matplotlib packages with Python programming to create data frames and a multi-line graph that will illustrate each city types' data points. With this report, I'm hoping it can show some level of impact for the stakeholders moving forward with how each city type has distinct qualities with their user bases.
 
## Results

<p align = "center">
<img src = "https://github.com/JoseCalucag/PyBer/blob/master/analysis/Pyber%20Chart.png" width = "900" height = "200">
 </p>
 
 If we take a look of each city type independently:
 
 ### Rural </br>
Compared to the other 2 city types, Rural doesn't drum as much business with only 125 rides in a 4 month period; which also explains that there's only 78 drivers for the region and it only profiting just over $4000. However, we can see that the averages are higher than the rest ($34.62/ride and $55.49/driver).
 
 ### Suburban </br>
 As the middle point of the 3 city types, the Suburban City type shows 5 times as many rides (625) and approximately 6 times as many drivers (490). During the 4-month range, there was a profit of just under 20K ($19,356.33) where the averages are just under the Rural marks ($30.97/ride and $39.50/driver).
 
 ### Urban </br>
 With the Urban city type, we do see significant jump in the data. Due to the large number of rides (1,625), Pyber has more drivers trying to accomodate and cover the city with 2,405. Albeit there is definitely a lot of money to be made (39,854.38 made in profit), the averages are way less compared to the other city types; where the average ride is $24.53 and a driver is making $16.57 on average. </br>
 

<p align = "center">
<img src = "https://github.com/JoseCalucag/PyBer/blob/master/analysis/pyber_challenge.png" width = "800" height = "300">
 </p>

## Summary </br>
If there are some recommendations that we can garner from this analysis: </br>

- The Urban city type can take on less drivers. Sure, there's more business here, but it does saturate the streets where drivers aren't really making enough (on average) for each ride. As all city types add up to a complete region, the spill over of Urban drivers can taken on rides in the Suburban and Rural regions.
- If this cannot be taken into consideration, Pyber should consider other business alternatives for their Urban and Rural drivers as well as they aren't getting that many rides. With apps like Uber and Lyft taking the next steps with food delivery, this can help suppliment some money for the drivers and keep them engaged on the streets.

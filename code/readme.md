## Problem Statment

##### The problem is to identify  the likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia, that have the impact on roads that will cause  in injuries and casualties . which affects the quality of people  life and  city quality.

---
## Executive Summary
#### we did an analysis on the data to identify  the likely factors influencing the outcomes of traffic accidents in the various regions in Saudi Arabia, that have the impact on roads. and our key findings was:
1. improving the quality of roads in both makkah and riyadh
2. increasing the cost of Traffic Violations
3. stricts on giving driving licence 

---
##### &#x1F534; **Licence Dataset**.   
1. <span style="color:green">**Year**</span> :  the year of the Licen  count  
2. <span style="color:green">**Administritive Area**</span> :the area name 
3. <span style="color:green"> **Driving Liceses**</span>: number of Driving Licen 
4.  <span style="color:green"> **geo_point_2d**</span> : the longitude and latitude For the <span style="color:red">**Administritive Area**</span>


---
##### &#x1F534; **accidents Dataset**.   
1. <span style="color:green">**Year**</span> :  the year of the accident count 
2. <span style="color:green">**Region**</span> :the area , Region name   
3. <span style="color:green"> **Indicator**</span>: accident that are (Injured,Dead) and the total number of accident
4. <span style="color:green"> **Value**</span>: the Value accident that are (Injured,Dead) and the total number of accident
5.  <span style="color:green"> **geo_point_2d**</span> : the longitude and latitude For the <span style="color:red">**Region**</span>
---
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Driving_Licenses|the year of the licenses  count|
|region|object|Driving_Licenses|the region name in the KSA | 
|driving_licenses|int|Driving_Licenses|number of Driving licenses| 
|x|float|Driving_Licenses|the longitude of the ```region```| 
|y|float|Driving_Licenses|the latitude of the ```region``` |




---
|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Traffic_Accidents|the year of the accidents  count|
|region|object|Traffic_Accidents|the region name in the KSA | 
|indicator|object|Traffic_Accidents|accident that are (Injured,Dead) and the total number of accident it's have only names and the values are in the value column| 
|value|int|Traffic_Accidents|the number of accidents the associate with indicator column| 
|x|float|Traffic_Accidents|the longitude of the ```region```| 
|y|float|Traffic_Accidents|the latitude of the ```region``` |


---


## Conclusions and Recommendations
##### &#x1F534;** what are  key takeaways and recommendations?**.  

1. I will suggest improving the roads in both makkah and riyadh 
2. increasing the cost of Traffic Violations can reduce accidents and that because on that the year 2017 had seen increase int the cost of Traffic Violations
3. Makkah is crowded and need more Traffic management
4. Traffic management should be more strict on giving driving licence 

---
##### &#x1F534;**Are there additional data you desire that would better inform your investigations?**.   
1. having the roads name can improve our findings the  Causes of Road Accidents
2. The type of car we can identfies what type of cars are  dangerous on the roads
3. data on the cost of Traffic Violations 

<a href = 'https://medium.com/@s.w.f1437/traffic-in-saudi-arabia-3488a8ec638e'>blog post</a>
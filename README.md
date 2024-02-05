# Road accidents in the Czech Republic

## Introduction

The automobile is one of the most dangerous forms of transportation, but it is also the most popular.
I've always wondered what factors contribute to this and why people die. Now I live in Prague and so I decided to collect statistical data and analyze it

### Brief summary
1. Covid-19 has changed the trend of accidents.
2. From one year to the next, injuries are significantly decreasing.
3. Most accidents occur after sunset.
4. Drivers in 90% of cases are not affected by any factors.

## Results of the done work

Downloaded, cleaned, transformed raw data from 2016-2022.    
(Read more in README.md in the data folder)    

**Before** 

![image](https://github.com/apereprosov/car-accident-cr/assets/61319269/804f09a8-852f-494a-ab03-6087b1055e7d)    
**After**    

![image](https://github.com/apereprosov/car-accident-cr/assets/61319269/8520c61a-5d8f-4a0c-88f3-cc822cda52be)

---

Translated using Deepl API with subsequent upload to Kaggle for research by others

---
Performed a full analysis from different angles, identified patterns

---
Identified a location with an abnormally high number of crashes

---
Used catboost to identify the main causes of injury

## Insights

- We see an increasing trend, which has slowed down quite a bit after Covid-19, we can assume that people prefer more public transportation ![image](https://github.com/apereprosov/car-accident-cr/blob/main/src/visualization/accident_timeline.png)
- There is also a trend towards a lower risk of injury in collisions. ![image](https://github.com/apereprosov/car-accident-cr/blob/main/src/visualization/injuries_timeline.png)
- Accidents often occur after sunset and evenly distributed across seasons, but it's worth considering that there are 15% more accidents in winter due to weather conditions + it gets dark earlier.    
  <div style="display: flex; justify-content: space-between;">
      <img src="https://github.com/apereprosov/car-accident-cr/blob/main/src/visualization/time_of_day.png" style="flex: 1; object-fit: cover; width: 40%; height: 60%;" />
      <img src="https://github.com/apereprosov/car-accident-cr/blob/main/src/visualization/time_of_year.png" style="flex: 1; object-fit: cover; width: 40%; height: 60%;" />
  </div>
- 20% of all accidents occur in Prague, 30% occur outside of the city ![image](https://github.com/apereprosov/car-accident-cr/assets/61319269/c2e7b999-b68f-4fbe-bd9c-e5dfb0968ff0)
- The anomalous road is in Poruba town where 26% of collisions are due to lack of following distance when on average only 6% occur for this reason
- Injury Analysis
  - The chance increases by an average of 10% with at least some alcohol consumption ![image](https://github.com/apereprosov/car-accident-cr/assets/61319269/fcdb7302-d61a-472c-a65a-14d4f913f031)
  -  New generation car owners are 10% less likely to be injured. ![image](https://github.com/apereprosov/car-accident-cr/assets/61319269/e7aa6bec-9222-4511-b3d3-4dd74f8988bc)
  -  Cyclists and motorcyclists are 4 times more prone to injuries than car drivers
  






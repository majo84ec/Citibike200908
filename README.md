# Citibike 2009-08 Analysis

## Purpose.

Citibike is a bike-sharing program in Des Moines and it is looking to convince investors that it is a solid business program.. To solidify the proposal, one of the key stakeholders request us a bike trip analysis with information of August 2009 using Tableau.

Follow the link for story 

## Results.

After using Python and Pandas to convert the "tripduration" column to a datetime datatype,  we exported the DataFrame as a CSV file to use for the trip analysis.

### How long bikes are checked out for all riders and genders.

The visualization below shows the typical rental peaks around 10 minutes, and nearly all the rides are under one hour in duration.

![image](https://user-images.githubusercontent.com/120151872/229652460-431d1097-043f-47c1-8922-25003a5a06bb.png)


On the other hand, we can observe the relation between trip duration and number of trips by Gender. In this case the trip duration distribution for Men and Women are the same and primarly the customers are Male.

![image](https://user-images.githubusercontent.com/120151872/229652560-e2778a1b-1b43-4399-bc45-8d0eff5b0b90.png)



### How many trips are taken by the hour for each day of the week, for all riders and genders.


### What days of the week a user might be more likely to check out a bike, by type of user and gender.


 This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines. Specifically, you want to find out how the proportion of short-term customers to annual subscribers has changed.

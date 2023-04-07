# Citibike 2009-08 Analysis

## Purpose.

Citibike is a bike-sharing program in Des Moines and it is looking to convince investors that it is a solid business program.. To solidify the proposal, one of the key stakeholders request us a bike trip analysis with information of August 2009 using Tableau.

Follow the link for story 
https://public.tableau.com/views/NY_Citibike200908/Story5?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link



## Results.

After using Python and Pandas to convert the "tripduration" column to a datetime datatype,  we exported the DataFrame as a CSV file to use for the trip analysis.





The follow visualization shows the typical rental peaks 5 minutes, and nearly all the rides are under one hour in duration.

![image](https://user-images.githubusercontent.com/120151872/229652460-431d1097-043f-47c1-8922-25003a5a06bb.png)


On the other hand, we can observe the relation between trip duration and number of trips by Gender. In this case the trip duration distribution for Men and Women are the same and the main customers are Male.
![image](https://user-images.githubusercontent.com/120151872/229654367-f523490d-d355-4eee-8b44-d7bde86dd56d.png)


The Fig. 1 below shows us Thursday is the day of week with more trips and Male suscribers are who take this rides (Fig.2.

![image](https://user-images.githubusercontent.com/120151872/229654775-aaa2a940-7449-412c-9dea-b03fcb1093ae.png)
Fig.1

![image](https://user-images.githubusercontent.com/120151872/229654924-cbeaacb3-3a03-47d5-a449-e814f75fb193.png)
Fig.2

![image](https://user-images.githubusercontent.com/120151872/229655665-53738bd0-b46c-4c34-8dcd-21ee448732f8.png)



### What days of the week a user might be more likely to check out a bike, by type of user and gender.


 This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines. Specifically, you want to find out how the proportion of short-term customers to annual subscribers has changed.

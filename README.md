# Citibike 2009-08 Analysis

## Purpose.

Citibike is a bike-sharing program in Des Moines and it is looking to convince investors that it is a solid business program. To solidify the proposal, one of the key stakeholders request us a bike trip analysis with information of August 2009 using Tableau.

Follow the link for Tableau story: https://public.tableau.com/views/NY_Citibike200908/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link




## Results.

### Data Base

After using Python and Pandas to convert the "tripduration" column to a datetime datatype,  we exported the DataFrame as a CSV file to use for the trip analysis.

![image](https://user-images.githubusercontent.com/120151872/230682172-77f22516-a616-41ba-93a5-1641496cdc41.png)


### Tableau

The follow visualization shows the typical rental peaks 5 minutes, and nearly all the rides are under one hour in duration.Fig.1

![image](https://user-images.githubusercontent.com/120151872/229652460-431d1097-043f-47c1-8922-25003a5a06bb.png)
Fig. 1

On the other hand, we can observe the relation between trip duration and number of trips by Gender. In this case the trip duration distribution for Men and Women are the same and the main customers are Male. Fig.2


![image](https://user-images.githubusercontent.com/120151872/229654367-f523490d-d355-4eee-8b44-d7bde86dd56d.png)
Fig.2



The Fig. 3 below shows us Thursday is the day of week with more trips and Male suscribers are who take this rides (Fig.4-5)

![image](https://user-images.githubusercontent.com/120151872/229654775-aaa2a940-7449-412c-9dea-b03fcb1093ae.png)
Fig.3


![image](https://user-images.githubusercontent.com/120151872/229654924-cbeaacb3-3a03-47d5-a449-e814f75fb193.png)
Fig.4


![image](https://user-images.githubusercontent.com/120151872/229655665-53738bd0-b46c-4c34-8dcd-21ee448732f8.png)
Fig.5


Additional analysis can be made to identify the frequent customers and age . People who born year 1997-2010 known as Milennial represent high volume of user by subscription . This information helps the company to address future campaigns and fidelity programs.(Fig.6)

![image](https://user-images.githubusercontent.com/120151872/230696333-ad6ab5dd-8356-45d6-a5bc-ca083b6e8336.png)
Fig.6


Knowing the top locations will give company an idea where to allocate their inventory , and bikes with more number of rides will support the maintenace plan maintenance. 


![image](https://user-images.githubusercontent.com/120151872/230695775-89561341-51ac-4e4b-861b-32b406bcfc9b.png)
![image](https://user-images.githubusercontent.com/120151872/230696216-0b168760-0091-4dc8-812e-f3572c147990.png)


Fig.7




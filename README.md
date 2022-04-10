# BikeSharing
Used pandas to edit data source and export new csv file for data visualization in Tableau. 


Overview of the analysis: 

The purpose of this analysis is to provide a high level summary of the bike sharing data in the form of Tableau visualizations for easy consumption by investors. First, I used pandas to change the change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I create a set of visualizations. 

Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

Length of time that bikes are checked out for all riders and genders

![image](https://user-images.githubusercontent.com/96396696/162558083-cf14cfb9-eb29-4041-a883-8a7dfe2e7956.png)

This line graph shows that most bikes are rented between 0 and 60 minutes disagreggated by gender. The first thing you will notice is that more men rent bikes than women and the unknown gender. Additionally, over 10,000 men rent bikes for about 5 minutes and then after that, the rental time tapers down. 

Show the number of bike trips for all riders and genders for each hour of each day of the week

![image](https://user-images.githubusercontent.com/96396696/162558207-8811123c-8a80-45dc-ba1a-ad5d43e107f3.png)

A high concentration of rides for males are happening between 5-7pm. Very few rides are happening late at night between 12-4am. Weekdays seem to be the busiest days for rental, but there are still many riders who rent on Saturday and Sunday. 

Show the number of bike trips for each type of user and gender for each day of the week.

![image](https://user-images.githubusercontent.com/96396696/162558369-f182186e-4824-4121-b428-54ee6f1c86e9.png)

 This visual shows that a majority of male customers are subscribers to this business. This is also true of female riders but not those who did not identify their gender. 

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors: [link to dashboard](https://public.tableau.com/app/profile/liya.haile/viz/BikeSharingInformation/Story1?publish=yes)


Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

From this data analysis, we can conclude that a majority of riders are male, folllowed by females, and then those who did not identify their gender. Additionally, most users rent their bikes for less than one hour. Unsurprisingly, the heat map helps us to understand that most people are renting early in the morning before work and after work. 

The additional analysis I would suggest is looking at the time of day users who rent their bikes for 0-30 minutes. After narrowing down on this subset of riders, I would use the coordinates to triangulate which stations riders are renting from in the mornings between 6a,-9am and in the evenings 5-7pm. Furthermore, I would disaggregate this data not by gender but rather by usertype. 

This information will be usefull for the business because they will be able to identify hotspots and ensure that they are prioritizing and servicing those bikes in frequently visited stations. Furthermore, prioritization can be given to stations which service more subscribers vs customers. Additionally, narrowing down on these stations will help the company make future decisions related to cost/benefit of having bikes at certain stations and/or transferring bikes to key locations. 

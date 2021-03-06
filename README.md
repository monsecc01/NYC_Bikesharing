# NY Citibike

## Resources

[NY_Citybike_Challenge.ipynb](https://github.com/monsecc01/NYC_Bikesharing/blob/f943c55d69ff07f36792c8930eecb9f221188448/NYC_CitiBike_Challenge.ipynb)

## Purpose
The purpose of the bike trip analysis is to create visualizations of Citibike trip data in NYC. The visualizations will help back up a proposal for a bike-sharing program in Des Moines, Iowa. We used Pandas to transform and load data into the desired format, and Tableau Public to create and publish the visualiztions. The following visualizations were created for this analysis:
*  A line graph displaying the number of bikes checked out by duration for all users
*  A line graph displaying the number of bikes checked out by duration for each gender
*  A heatmap showing the number of bike trips for each hour of each day of the week
*  A heatmap showing the number of bike trips by gender for each hour of each day of the week
*  A heatmap showing the number of bike trips for each type of user and gender for each day of the week

## Results

<img width="500" alt="Top start and end locations" src="https://user-images.githubusercontent.com/81447450/123561757-e64bc880-d76f-11eb-98a5-8d2b36dae235.png">

The Top Start and End locations were found for Citibike users in NYC. We can see that the large majority of users are located in Manhattan, specifically Midtown and Lower Manhattan. This could be due to the high density of people that work in those areas.  

<img width="572" alt="checkout times for users" src="https://user-images.githubusercontent.com/81447450/123561760-ec41a980-d76f-11eb-9fc1-f7c422900bd6.png">

The results for Checkout Times for all users show that the majority ride for an average of less than an hour. The highest average riding duration is 5 minutes.

<img width="653" alt="checkout by gender" src="https://user-images.githubusercontent.com/81447450/123561764-f19ef400-d76f-11eb-8471-5df6b8424c8c.png">

The Checkout Times by gender visualization further dives into the checkout time data. We see that the majority of riders identify as male.

<img width="374" alt="weekday per hour" src="https://user-images.githubusercontent.com/81447450/123568596-4485a500-d78a-11eb-83d7-c891ff0e4315.png">

When observing the Bike Trips heatmap for each hour of the day , we see that more bike trips occur during the usual work start and end times (8 am and 5 pm). This further supports the conclusion that bikes are used for commuting to and from work. On Saturday afternoons we also see high activity, although not as high compared to during the week, but this could be due to recreational bike riding around the city. 

<img width="571" alt="trips by gender" src="https://user-images.githubusercontent.com/81447450/123562665-b69fbf00-d775-11eb-9b6c-daeab2847792.png">

The results for the Bike Trips heatmap broken up by gender shows similar results as the heatmap for all users and the Checkout Times by gender line graph. It showed that most of the bike riders that commute during end/start work hours identify as male. 

<img width="352" alt="by Gender by weekday" src="https://user-images.githubusercontent.com/81447450/123561775-fcf21f80-d76f-11eb-96e5-e89d5ad0e29e.png">

When we look at the Bike Trips heatmap by user type and gender, we see that most regular bike riders identify as male. Also, this visualization shows that one time customers use bikes as many times across all genders. 

## Summary
Overall we can see that most people using the bikesharing system in NYC use the bikes for commuting to and from work. It also seems that there are customers who bike recreationally (most likely tourists). One key observation is that the majority of the overall bikers using the bikes are male, however further investigations will have to be made to understand why this is. 
Two suggested visualizations to better understand the customer base are:
1.  Reasons why people don't use bikes for transportation (this might have to be preceded by a survey)
2.  Which stations are "sold out" during peak hours to understand if more stations are needed

See the dashboard here:
[NY Citibike Dashboard](https://public.tableau.com/views/NYC_CitiBike_16248281330990/NYCitibike?:language=en-US&:display_count=n&:origin=viz_share_link)

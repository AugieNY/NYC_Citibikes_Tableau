# NYC_Citibikes_Tableau

# Objective
We need to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis,we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we created a story in Tableau Public.

## Analysis
We based ourselves on the Citibike data from NYC, a successful and well-known bike sharing program.

At first, we wanted to look at a glance at the user age, gender, and the most used start stations to understand the data better.
![image](https://user-images.githubusercontent.com/75656368/213880461-92f3f3cc-60c5-44fc-abfd-e0752a002365.png)

We can see that most of the users were born after 1960, with the major part of them born between 1980 and 2000. Meaning that NYC is building a generation that is used to Citibike and using them. We can assume that it will help to give continuation to the bike sharing program for many years to come.

Then we wanted to look at Hhow long bikes are checked out for all riders and genders. We can observe that most of the rides are done within 20 minutes. Indicating a short commute time. 
![image](https://user-images.githubusercontent.com/75656368/213880592-2d4b6638-a7de-43c9-8065-4426018f2cd8.png)

When we look at the trip duration length by gender, we can see that most riders are males. But there is no differences in trip duration by gender.
![image](https://user-images.githubusercontent.com/75656368/213880620-60ddf1b1-aee4-4311-884d-4e2ddfc96955.png)

Looking at trips by Weekday for Each Hour, we can see that during the weekday, the morning and evening rush hour concentrate most of the rides. While the weekend rides are around the "Brunch" hours.
![image](https://user-images.githubusercontent.com/75656368/213880671-449b76ca-6b9e-4fde-8db8-fa60468d23d6.png)

There is more of a difference when we split the previous data by gender. We observe that males riders are using citibikes throughout the day more than female rides that use it mostly during rush hour. (We filtered the data to focus on rush hours during weekdays then).
![image](https://user-images.githubusercontent.com/75656368/213880979-cbba8e87-68a4-4e6b-a9bf-8c46c5671219.png)

Now looking at the data by customer type. That's an interesting part for the investors. The subscribers are mostly male, and as we saw before, it's also the gender that use the bikes the most, guaranteeing stable revenue from subscriptions. 
![image](https://user-images.githubusercontent.com/75656368/213881008-07d97d04-b182-4add-a9e8-087a64d3d83a.png)

We chose to observe the concentration of starting station and ending station accross NYC for the following visualizations.
 As we can see, it's heavenly distributed in the boroughs that are seeing congesting areas. Manhattan and Brooklyn stationsare both heavily used.
 ![image](https://user-images.githubusercontent.com/75656368/213881047-71225b67-c3ce-4e3c-a80a-e4e73d720760.png)

Most of the stations are being used close to central areas but it's also use widely. Midtown is heavily impacted, which is where a lot of the rush hour traffic is usually congested for the ending stations (receiving the bikes at the end of a trip).
![image](https://user-images.githubusercontent.com/75656368/213881087-efa0e5b8-de19-4191-822a-0ba7bcbd8c90.png)


## Summary
We can concludes that Citibike is a success in NYC with a stable demand, mostly male and mostly during work days rush hour. This allows investors to see a stable return on investment as we do not see a gap in usage (or stop).


## Link to Tableau public:
https://public.tableau.com/app/profile/augustin.augie.bourgois/viz/CitibikeNYC-TableauStory/Citibike?publish=yes

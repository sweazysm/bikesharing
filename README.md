# Ridesharing? It is now time for Bikesharing!

[View the Tableau Story by clicking this link](https://public.tableau.com/app/profile/scott.sweazy.jr/viz/NYCCitiBikeChallenge_16338367263680/CitiBikeSharing)

We have all become familiar with the concept of Ride Share services such as Uber and Lyft. Without needing a car or a taxi we can pay for a stranger to pick us up and take us virtually anywhere within reason. With that being said, can this extend to other means of transportation? What about bicycles? Seemingly an increasing form of transportation yet again with younger generations (and the growing difficulty of getting a car), it would make sense to extend a ride service to bikes. However, will such a service actually succeed? This is what has been set out to be proven. More specifically: Can a bike-share service run through Citi Bank become profitable in Des Moines? Let's find out!

# Results and Processes

Data was extracted and transformed from bike share data taken in August 2019 from the Citi Bike website. This data was slightly modified and then imported into the data visualization software known as "Tableau." In this software data was comprised into dimensions and measures, both of which were compiled and edited to create the visualizations you will see below and in the Tableau Story linked at the top.


### Customers vs Subscribers

<img width="424" alt="Screen Shot 2021-10-10 at 12 31 26 AM" src="https://user-images.githubusercontent.com/86274124/136683768-f4994a16-a297-4cd8-9b6b-6511709faf48.png">
<img width="461" alt="Screen Shot 2021-10-10 at 12 31 31 AM" src="https://user-images.githubusercontent.com/86274124/136683769-1b9774f4-0b74-4444-b182-4f97a9426101.png">

The bikeshare data provided contained just over 2,300,000 individuals' data in relation to their demographics and usage of citibike. Of these participants, the overwhelming majority were subscribers to the citbike service as opposed to customers. This shows retention of clients and gives credence to the concept of bikesharing by itself being potentially profitable.


### Peak Ride Times in August, 2019

<img width="1002" alt="Screen Shot 2021-10-10 at 12 32 02 AM" src="https://user-images.githubusercontent.com/86274124/136683846-f0fdb06a-4d99-4125-b02a-9967582961bd.png">
<img width="741" alt="Screen Shot 2021-10-10 at 12 32 24 AM" src="https://user-images.githubusercontent.com/86274124/136683848-7ae1df3e-0b83-4604-b472-4fc4693c13cb.png">
<img width="1031" alt="Screen Shot 2021-10-10 at 12 32 36 AM" src="https://user-images.githubusercontent.com/86274124/136683849-31d7cb9c-d674-49c5-a27f-c767bc2f45ec.png">

The Citibike got plenty of uses ini August of 2019. Specifiically, the times where the bikes were used the most were hours 7 to 10 and hours 16 to 19. These hours correspond most closely with the times people head into work or class and the times people leave work or class. This makes sense as people need transportation to and from these occupations. 


### Checkout Times for Users

<img width="1019" alt="Screen Shot 2021-10-10 at 12 33 05 AM" src="https://user-images.githubusercontent.com/86274124/136684352-0aaff509-4be0-4060-9696-f3a99cadb9da.png">

Checkout times for users shows the relation between the number of citibikes being used and the amount of time they were ridden. For example, we can see from this chart that an overwhelming amount of bikes were ridden for around 5 minutes. As times goes on, the amount of bikes ridden for longer times decreases, showing that the majority of bike rides with citibike were around 5 minutes. A sharp decline occurs and stagnates at around an hour, staying steady across further timespans. This shows that the majority of people who use citibike only need it for short rides and are most likely staying within a close proximity to their destinations/not much travel is being conducted.


### Checkout Times by Gender
<img width="1051" alt="Screen Shot 2021-10-10 at 12 33 14 AM" src="https://user-images.githubusercontent.com/86274124/136685414-cedbac75-9589-44a6-a17e-f012dae141ba.png">

Similar to the data showing Checkout Times for Users in general, when Gender is added to the variable we see similar yet differing results. The results are similar to those shown above in that the majority of rides appear to last within the range of 5 minutes. What becomes more clear is that an overwhelming amount of these rides conducted in the first hour are conducted by males as opposed to females. A small minority are unknown/their gender is not reported in the dichotomy. What can be garnered from this is that it appears that the majority of citibike users, for the population observed in August, are male. Citibike would most likely have greater Citibike usage by targeting the male demographic as a result.


### Trips by Weekday (per hour)

<img width="1051" alt="Screen Shot 2021-10-10 at 12 33 26 AM" src="https://user-images.githubusercontent.com/86274124/136686014-7d7a5bd9-e5d6-4eff-ad2b-26a6bba94987.png">


We have seen so far that the majority of Citibike users are subscribers who are overwhelmingly males that ride the citibikes during the beginning of the morning and the end of the work/school day. How does this hold up across the 7 days of the week? A heatmap was created to illustrate the times of this data. As was found in the last 2 visualizations, peak riding times across the work/school week (Monday - Friday) are 6am - 9am. Likewise, we also seek peak riding times at 4pm - 8pm, the times when we can expect people to be leaving work or class. Not surprisingly, during the workweek we do not see many people riding bikes between the hours of 10am - 3pm and likewise for very late times such as 10pm - 4am. We see slight differences during the weekend with a less populated, but more consistent, riding population between the hours of 9am - 7pm.


### Trips by Weekday (per hours(by gender))
<img width="1050" alt="Screen Shot 2021-10-10 at 12 33 36 AM" src="https://user-images.githubusercontent.com/86274124/136686196-805abdc5-4f6e-44fd-b547-b2de333706bc.png">


As with the visualizations that looked at the relation between ride duration and gender, we also have a variation of the visualization for Trips by Weekday per hour by gender. These heatmaps are almost identical in pattern to the one above, the only difference in the populations of citibike users. As it was determined that our main population of citibike riders is male, the majority of data points can be seen in the Male Heatmap as opposed to the lighter Female Heatmap and the almost non-existant Unknown Heatmap. Across time Males dominate the citibike usage during the peak hours and the off hours.


### User Trips by Gender: Customers vs Subscribers across the Weekday and Weekend 


<img width="1052" alt="Screen Shot 2021-10-10 at 12 33 45 AM" src="https://user-images.githubusercontent.com/86274124/136686296-391c00e5-b61e-4fab-8d45-83c9d4103ce4.png">

Finally we come to a final breakdown of data points from our visualizations. What is shown here are the amount of times a citibike was used on what day, by what gender, divided into subscribers and customers. The data is simple and clear: the overwhelming usage is not only male but it is from subscribers. Monday, Tuesday, Thursday, and Friday appear to be great days for citibike usage amongst males making these the peak earning times for Citibike. 


# Summary

From the data posed here it can be suggested that Citibike could be successful in Des Moines if it targets mostly males during the weekday. Males overwhelming domiinate the number of bike rides found and would be the best to target subscriptions to. It is best to target people during the weekday, coming to and from school or work. Citibike would, I suggest, be best suited to target males with a cheap, healthy, and environmentally friendly way of getting to and from their daily destinations. While this is a simple answer it also implies other things that need be graphed. One of these is that citibikes most likely will need to be repaired. While we can look at peak and hours and suggest times from those visualizations, it would be best to create a visualization showing the times and days with the least amount of citibike riders across demographics and use these times to repair the bikes. Another visualization that could be explored from this is how to bring in more of the female demographic. Where are their citibikes stopping off at? What are they taking as opposed to citibike? What attracts them to citibike? It seems that the male population is in the bag with that citibike is doing, but bringing in more of the female demographic could lead to increased porfits for citbike. 

# Introduction  

You are Bob, a globe trotter who is travelling across the world. You find yourself stranded in Chicago with nothing to eat or to drink. Because somehow nobody wants to help you, you look at the Chicago Food Inspection's guide with restaurant recommendations. By reading it, you realize that some of these recommendations are linked to multiple factors and some restaurants are deemed as dangerous or sage. You ignore the hunger and decide to go deeper in the book to learn about them.

# Bird's eye view of Chicago restaurants.

To get the ideas of safe restaurants in Chicago, we first need to see how Chicago food inspection works for restaurants in general. How often are restaurants inspections conducted and how many of them pass? What are the main causes of failure? Are there other sociological or geological features that are correlated with certain tendancies?

## Are franchise restaurants safer than individual restaurants?
Roughly, there are two ways of choosing a place to eat. One is eating at a franchise restaurant that is already familiar to you, the other is challenging a restaurant you have never seen before. Which will be the safest action? 
 

Here is a quick look at the average number of inspections and inspection pass rate of Chicago restaurants. We classified the restaurants in three groups: massive and worldwide franchises, smaller franchises, and non-franchises. As we can see in the next figure, the average inspections is the highest in big franchise restaurants while smaller franchises were inspectly least frequently.  
<br>
![Inspections per group](general/inspections_avg_franchise_individuals.png)  
<br>

Franchise are also more resistant to socioeconomics factors than individual restaurants. For example the poverty of a district doesn't influence if a franchised restaurant will fail an inspection whereas a small restaurant will suffer higher failing rate.  We displayed from left to right big franchises, small franchises and individuals. Each point represents the average fail rate (x axis) of a district depending on its wealth (y axis).  
<br>
![Inspections per group](general/median_income_passrate.png) 
<br> 


## The fries or the salad?  
There are different types of food served in franchise restaurants: burgers, sandwiches, pizza.. Can we tell which type of franchise is safer to eat in Chicago? First, let's take a look at the average number of inspection for each type of franchise to see how they behave.  
<br>
![Inspections per group](general/inspection_per_license_franchisetype.png)  
<br>
Sandwich franchises are the ones being the most inspected with on average 8.1 inspections per restaurant! They are closely followed by burritos/bowls and burgers. This is interesting as those are often mentionned when diseases outbreak and thus may have been targeted more thoroughly by inspectors. Opposed to this are pizza places that are inspected half as much. But more importantly, what about the results of those inspections?  
<br>
![Inspections per group](general/fail_rate_franchisetype.png)  
<br>
Looking at the overall failure rate between different types of franchises, we can say sandwich franchises are the safest and the pizza franchises are the least safe. Furthermore, the inspection pass rate is heavily correlated with the inspection frequency. We can infer that a restaurant that is inspected more often is more likely to take care of safety issues and eventually, to pass the inspection more easily than its counterparts.  

## Which violations are the main causes of inspection failure?
Before digging the different franchises and the violations they've got, let's take a look at the main cause of inspection failure for major franchise restaurants.  
<br>  
![Inspections per group](general/violations_repartition.jpeg)  
<br>
Among the violations related to the inspection failure, hygiene issue caused more than half of the total violations, followed by equipment. Looking at those two violations thoroughly, different types of franchises will give us the detailed idea of which place is safer to visit.

## The violations podium
Few franchises are similar to each other and it gives some interesting results. We have found a few intriguing stats:  
<br>
![Inspections per group](general/severe_equipment_violations_by_franchise.png)  
<br>
Funnily, McDonald's has the highest number of violations related to equipment maintenance/sanitization. A nice find when you know that they were heavily mocked a few months ago on the internet for their always-broken ice machines.  
![McDonalds](meme.png)  
<br>
![Inspections per group](general/complaint_inspections_by_franchise.png)  
<br>
No luck for McDonalds, they are still the best in another category! With BurgerKing, they must have angered a lot of customers to be controlled close to four out of five times for a complaint.  



# I prefer big food chains, where should I go?  
Suppose that someone wants to eat in a big franchise for some reason. One can say that it maybe is important to go to a safe place with little risk to contract a disease. If we check the rate of failing inspections, we can have an idea of which franchise is the safest.  
### Want to eat a beef burger?  
![Fail rate of burger restaurant](franch_img/mc_bk_wd.png)  
<br>
If we look at McDonald's, Burger King and Wendy's, we want to choose one of them to have a good american burger. The question is which one? One can say that it depends on the person's preference. Let's answer this question by looking at the safety of each restaurant without taking into account the taste of each burger. Depending on the year, the safest restaurant varies a lot but nowadays, Burger King is the best performing. In addition, one can note that since 2015, only Burger King tries to improve compared to Wendy's and McDonald whose fail rates still increase.  

### Want to eat some fried chicken?  
![Fail rate of chicken restaurant](franch_img/kfc_hc_pp.png)  
<br>
Let's say that our Chicago guy want to choose one of KFC, Harold's Chicken or Popeyes for his dinner. He doesn't prefer any of them, but he wants to be sure that the restaurant is safe because he read an article about [bird flu](http://dbfchicago.com/bird-flu-chicago/) that makes him scared of this disease. Like the burger franchises since 2015, KFC and Popeyes try to decrease their fail rate. In contrast, Harold's Chicken tends to fail more inspections than the two others. Based on that, the Chicago guy will have to choose between KFC and Popeyes.  
### Want to eat some Pizza?  
![Fail rate of Pizza restaurant](franch_img/ph_dm_pjp.png)  
<br>
Finally, what's better than a good pizza while watching TV? We have to select one of the following restaurant: Pizza Hut, Dominos or Papa John's pizza. By taking into account the plot above, we know that Papa John's pizza decreased his fail rate ratio through 2015 but unfortunately, nowadays it is better to goes to Dominos or Pizza Hut to have more safety. In the end, the best restaurants is Pizza Hut who only has 9% of fail rate at the moment.
 
## Where do I need to go?  

Sometimes, we just don't want to go far away to enjoy a meal. We want to get out of bed, go outside and take a burger at the closest street block without worrying about transportation. We will see in this part that not all districts are equal regarding inspections and their results. Later on, we will focus on some franchises that have different results depending on where they are located in Chicago.  

### The socio-economic factor  

Chicago suffers a clear wealth divide with some districts being largely poorer than their neighbors. This can be observed with the North and North-East districts that are richer than the West and South side of Chicago. We used the median household income as a wealth indicator to see if there is a correlation between the wealth and the overall restaurant inspections’ results.
To visualize this, we put side by side the districts’ median income, their average inspections per restaurant (from 2011 to 2017) and the average inspection fail rate of these same restaurants.  
<br>  
![Correlation between wealth, inspections and fail rate](part_location/socioeconomics/merged.png)  
<br>  
We clearly see a domino effect between these different metrics. Especially, lower income districts' restaurants may face fewer inspections. This lower amount of inspections leads surely to more failures as restaurants are left alone longer without control. So if you want to eat lunch in a random restaurant within your district with as few sanitization issues as possible, you better live in the wealthiest one!  

### But what if I  prefer <insert_food\> ? 

We got you covered! They are many franchises established in Chicago and all the biggest ones (such as McDonald's, Starbucks, KFC...) are present. But as we may expect, they all behave differently depending on where they are located. We will cover in this subsection which franchises are to be preferred depending on what type of food do you want and where do you want to eat it.  
We split up the franchises in four different categories depending on what type of food they are selling: burgers, pizzas, fried chicken and snacks/drinks. Each category only contains the three most established franchises as smaller ones tend to have not enough data to study. 
#### I want: a Burger  
For the burger category, we have McDonald's, Burger King and Wendy's facing themselves. McDonald's has a failure rate around 15% in most Chicago distrincts but has no outliers (the biggest fail rate is only 35%). This differs from Burger King which is much less prone to failing inspections in the North and South of Chicago but has two districts in the Middle-North that are close to 50% failing rate. Wendy's follows the same trend except for the worst places in the south.  
<br>
![Burgers](part_location/burgers/merged.png)  

#### I want: a Pizza  
Pizzas are a little bit different than other franchise types as they are also heavily involved in delivery. Papa Johns Pizza is the black sheep here with more than 25% failed inspections on about 60% of the districts it covers. Dominos and Pizza Hut are the inverse of each other with Dominos being exemplary everywhere except in the middle of Chicago. Pizza Hut is a little bit better on average in the Middle-North but worse than Dominos elsewhere.  
<br>
![Pizzas](part_location/pizzas/merged.png)  

#### I want: Fried Chicken  
There is also a black sheep in fried chicken fast foods: Harold's Chicken. While it covers the vast majority of South Chicago (the poorest region), most of the franchises are failing at least one quarter of the inspections. KFC and Popeyes are doing well in the South but KFC has the advantage in the North.  
<br>
![Fried Chicken](part_location/friedchicken/merged.png)  


#### I want: a Snack  
One information that isn't shown in this part is the number of licenses Starbucks and Jamba Juice have in each district. They are both heavily invested in the touristic area of Chicago (the port in the Middle-West) with as many as thirty stores in the tiniest district! They both are very careful in this location with fail rates lower than 15% on average. Starbucks is much better than Dunkin Donuts in the North and finally the later is the only one covering the South with unfortunately a pretty high fail rate.  
<br>
![Snacks](part_location/snacks/merged.png)  

#### Recommendation table
To summarize, we made a table to recommend which franchises to go to depending on your location and food habits. It is obviously simplified and thus may miss some details such as smaller districts:  
<br>
![Recommendation](part_location/recommendation.png)  

# Conclusion  
To sum up, by reading the Chicago's guide recommandation, Bob gained some insights on which franchises are safer and make the most effort on sanitization. Bob can read this little guide to help him remember which franchise to choose or flee. The inspections are necessary to enforce a good level of sanitization of the restaurants and we can clearly see it in the guide. The restaurants that do not follow the stream surely will not be visited anymore in the near future by Bob. Food safety should at the center of concern when choosing a place to eat for most people in the world.

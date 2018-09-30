CEE 224X | Released: 180925 | Due: 181002
Name: Irene Alisjahbana

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

The combined fields shows those values are obtained by combining consumption data with a neighboring ZIP code to fulfill the aggregation criteria based on the California Public Utilities Commission. The purpose of this is to retain anonymity of the customers; so that we can’t pinpoint each customer’s electricity consumption. This information might affect the analysis because the combination of data from other ZIP  codes might not accurately reflect the energy consumption of that specific ZIP code. 


#### Q2: Why are the “Average” fields likely not useful for our analyses?

The "Average" field might not be useful because it will not show the distribution of consumption between the customers in the specific zip code. Some customers might consume larger number of KwH per quarter, whereas others might only be consuming a little.  Using the average might not accurately represent the electricity and gas usage of the area. 


#### Q3: What type of calculations should "X" and "Y" be in the step above? Why?

Q3 Response Here (<100 words)



#### Q4: What is the total KBTU combined electricity and gas consumption in PG&E territory in 2017? What is the average annual electricity consumption per customer, and average annual gas consumption per customer?

The total KBTU combined electricity and gas consumption in PG&E territory in 2017 is 2.73e11 kBTU. The average annual electricity consumption per customer is 21951.5 kBTU and the average annual gas consumption per customer is 43258 kBTU. Note that the values obtained here are the results of the modified dataset in which the duplicate for month 9 in the Q4 was deleted before the analysis. 



#### Q5: How would you explain the results of this chart to an average property owner in Northern California? What would be the value of conducting further "seasonal" analyses of energy use, compared to "year-long" analyses, and how would you define seasonal boundaries?

From the chart, it can be seen that gas usage is extremely high in the first quarter compared to the electricity usage. This can be attributed to the fact that it’s winter and that customers would turn on heaters a lot of the time. As the year progresses however, it can be seen that the gas usage significantly drops, and electricity usage becomes higher than gas usage. Again, this makes sense because as the weather becomes hotter, customers would start using ACs and fans compared to heaters. Towards the end of the year, when the temperature starts dropping again, it can be seen from the chart that customers would start significantly using gas a lot more once again. Compared to the gas usage, it can be seen that the electricity usage remains relatively constant throughout the year. 

By conducting seasonal analyses of energy use versus year-long analyses, we can see the distribution of energy uses clearly. Such as the one seen in the chart, by doing seasonal analyses, we can understand the trends of gas usage vs electricity usage that is different for different periods of time. I would define the seasonal boundaries as winter and summer, in which winter is the time where gas usage is higher than electricity usage and summer is the time where electricity usage is higher than gas usage. 


#### Q6: Explain your choice of formula for "avgkbtu".

First, I grabbed the total number of customers for electricity and gas for a specific ZIP code. Then I took the maximum number between the two. The reason why I did this is because some customers would only have electricity and others only gas, and to be more conservative I took the maximum. I then divided the total kBTU of the zipcode with the number of customers. Because the number of customers is a cumulative value throughout the year, the division will result in the average annual energy consumption per month. Therefore, I had to multiply it by 12 to obtain the annual value. 



#### Q7 Paste a publicly viewable link to your Slides.

https://docs.google.com/presentation/d/14duGwbwPZvuCNpZdu4EKMpnpZB_NZ8Z8cvqYGl_q2Tg/edit?usp=sharing



#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

I used Stanford’s ZIP code. Based on the images, it can be seen that Stanford has a very high average but has a very low total usage, which is similar to what I would expect. This is because Stanford is a campus and not a packed residential area where there would be lots of customers that use energy. Because there are not as many residents, the total energy usage is also low. But on the other hand, the fact that Stanford doesn’t have as many residents also cause the average energy usage to be really high. 


#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

It took longer to complete Pass One than I thought. It was partly because of all the manual labor that goes into analyzing data on excel. It also took quite a while to make sure that I had imported all the data correctly. It was challenging to find errors in my calculation and even in the data itself as I had to go through most of the data one by one. This was especially true because at first the results weren’t making sense, and so I had to go through the data again to find the error. 

If I had more time, I would probably spend more time analyzing the results and think about why the results are the way they are by going through some of the details, instead of just looking at the total values for example. I might also look at the energy usage separately (gas and electricity) as opposed to the total usage immediately. 



#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

Using Excel (Pass One) was definitely more time consuming and involved a lot more manual labor work because the datasets were large. Pass Two was much faster once you got the code running. Using R/Python also reduced the chances of making mistakes in modifying data. The outcome of the analysis however, was very useful. I am able to see the trend of energy usage throughout the year through the chart. Showing the results of the data on the map also enabled me to quickly see which areas uses the most energy or the least energy. I think that these kinds of outputs are essential to understanding urban systems and figuring out solutions to urban problems. 

In my opinion, the assignment wasn't too difficult. However, it took quite a long time to get all the software installed in my computer. A lot of time was also spent in trying to understand the data, and why the results were not as I expected (turns out there was an error in the dataset itself). In addition, because I don't have any experience in R before, I took some time to figure out what the code was doing. 


#### Q11 In total, how long did Assignment 1 take?

Part 1: Tech Setup: 120 minutes

Part 2: Pre-Assessment: 30 minutes

Part 3: Practice Data Dive: Pass 1: 240 minutes

Part 3: Practice Data Dive: Pass 2: 60 minutes

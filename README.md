# Zorang-Campus-Drive
## Explanation

1.Here, we need to divide these 100 orders into 10 non-empty groups. Each delivery agent gets one of the groups to be delivered. 

2.Consider each agent, the agent starts from the store location to collect the orders of his group. Then goes to the location of each order of his group, one by one. Then, finally returns to the store location.

3.The distance to be travelled from one delivery location to another needs to be included. And, we can optimize the distance the delivery agents travel from store location to first delivery location and the distance from his last delivery location to the store location. So, the maximum of time taken by all agents has to be as minimum as possible. Since all of them travel at the same speed, optimizing distance is equivalent to optimizing time. 
4.First, we calculate the total distance that needs to be covered. 
5.Since we need to minimize the maximum of all distance’s agents travel, we try to divide the groups such that distances travelled in each group are as close as possible. 
5.After forming the groups, we have to decide the order in which they travel. So, the starting location will be that location which is closest to the store location. 
6.Then, the order of the next location will be the closest one to the previous location. We thus sort each group in such a manner.
7.Thus, we obtained 10 groups of delivery locations for each delivery agent, and locations in each group are sequenced to inform the order of travel.



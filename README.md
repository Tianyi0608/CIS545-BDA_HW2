# CIS545-BDA_HW2
Recommend restaurants for users based on BFS on yelp data with Spark
1. Load data as yelp_business_sdf, yelp_review_sdf, yelp_users_sdf, yelp_business_attributes_sdf
2. Create SQL table for each sdf and clean data (for none)
3. Do some basic analysis: most popular restaurants in PA,  highest avg stars, difference from avg in a place, most common check-in days and times
4. Generate user-business graph (from node, to node)
5. Create BFS algorithm
6. Recommend restaurants use BFS with depth=1 and score>4
7. Find the smallest number of restaurants between two users based on BFS
8. Obtain friend list of yelp users and graph it

First: clean data; second: create from node, to node graph; third: implement BFS on graph; forth: get the needed info (e.g. recommend restaurant, find shortest path…)

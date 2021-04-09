---
layout: post
title: Supermarket Sales
subtitle: Demo of sales data with Tableau
---

### The Plan

The plan for this project was to create a dashboard in Tableau that could give some insights to the client with the data provided by said client for their store chain consisting of 3 branches that sells various products.



### The Data

The data in this project came from a kaggle dataset that can be found [here](https://www.kaggle.com/aungpyaeap/supermarket-sales). It consists of a single csv file with 1,000 rows each being a transaction at store owned by the chain and containing information such as total amount, tax, department of products sold, and which location they were sold at.


### The Dashboard

A quick overview of the dashboard can be seen with this screenshot here,

<img src="/img/SupermarketDashboard.png">

and the link to the project's home on Tableau Public can be found here: [Tableau project](https://public.tableau.com/profile/thomas.mcdaniel91#!/vizhome/SupermarketSalesViz/SupermarketSalesData?publish=yes)

During the creation of the dashboard in Tableau, I wanted to focus on the sales and the products with filters consisting of branch and product line to allow deeper investigation into individual stores and departments. Since customer ratings were provided, I also chose to shed some light on the amount of money the average person spends in the store based on those ratings and lo and behold, the few customers that did give a 10/10 rating were also the ones that had the highest average total per transaction. 

This is what led me to create the heat map of average sales per rating which forced me to create my own calculated field. Luckily this is very similar to the syntax in Python so it was fairly straightforward just to put this in:

<img src="/img/Calculatedfield.png">

After taking a look at the customer ratings themselves, I noticed that the graph looked pretty ugly and difficult to read as they were continuous numbers so after making bins of 0.5 for the ratings and separating them by gender, I was able to turn it into a much easier to read bar chart as shown in the before and after here:

<img src="/img/UnbinnedRatings.png"> <img src="/img/BinnedRatings.png">

With all of these things done, I believe that the client would have a much easier time determining where to put their focus in each store by way of customer service as well as sales and if this client were to return to me for another analysis, I would attempt to pursued them into using a database to store this data so that an automated pipeline could be set up to allow them to constantly update and view more real time data rather than historical to make needed changes quicker than seeing past months' sales.

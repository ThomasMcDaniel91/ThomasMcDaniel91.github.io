---
layout: post
title: Supermarket Sales
subtitle: Demo of sales data with Tableau
---

### The Plan

The plan for this project was to get some familiarity with Tableau in specific. Because of this, a simple dataset was chosen and the main focus is to make a dashboard in Tableau that could give some insights to a company manager of said chain.



### The Data

The data in this project came from a kaggle dataset that can be found [here](https://www.kaggle.com/aungpyaeap/supermarket-sales). After a brief check on the data in SQL Server to check out values and get a quick view of the data, I deemed there was no need to do any further cleaning to complete the project I had in mind.
Since this particular chain only consists of a single store per city with a total of 3 stores, a map was out of the question. Instead I decided to go filters of product line, month and branch for the dashboard's filters and decided to focus it on the customer ratings that I was supplied with.


### The Dashboard

A quick overview of the dashboard can be seen with this screenshot here,

<img src="/img/SalesOV.png">

and the link to the project's home on Tableau Public can be found here: [Tableau project](https://public.tableau.com/profile/thomas.mcdaniel3679#!/vizhome/SupermarketSales_1/SupermarketSalesData)

While designing the dashboard, I wanted to make sure that the customer ratings were the focus because I feel like that is the best insight that could be gained from these particular parameters. The original rating data was comprised of continuous ratings between 4 and 10 so I used the bin method in Tableau to turn them into bins of 0.5 for easier viewing.  

With the filters of product line and branches, you can see which departments of each store are in need of improvement in their customer service skills and which departments are going above and beyond to get more of the preferred scores.  

Another quick overview this gives is which product lines are doing the best in each store because there are different product lines as the top seller for each location and this could give the owner an idea of which locations to run certain sales in or possibly even move product to different stores where they have a higher chance of being sold for a reasonable quantity. All in all, I believe that this dashboard in the hands of someone in the company could most certainly improve their sales overall by way of customer satisfaction and have a better idea on ordering quantity for their stores in the future.

# Supply_Chain_Analysis
In this project. My goal was to take a deep dive into this kaggle dataset to find some insight about its supply chain operations.

I began by reading in the csv data and observing its layout. I noticed that it would need some data cleaning before I could do any analysis. I chose to drop all NaN rows and looked for and data that wouldn't belong in a particular column. I also changed some data types and assigned values to late delivery risk column. After cleaning the data I saved of the first dataset to a csv. The sencond dataset didnt provide much insight after viewing its attributes.

Next I read in the newly cleaned dataset and started my analysis. I manage to retrive in sight on the top 10 products this company sells and other attributes that I compilled into a dataframe. I then went to visualize this using a bar and pie chart. The next insight I dove into was looking at delivery risk & benefit per order by customer state. These findings were visualized through dataframes.

What I ultimatley derived from my analysis was that our top product by quantity was "Perfect Fitness Perfect Rip Deck"	with (quantity =24515	Avg_Order_Profit_Per_Order = 20.14	Avg_Order_Item_Total = 162.07). However the piechart illustrates the "Field & Stream Sportsman 16 Gun Fire Safe" brought in the majority of profit per order with 20.9%. For the delivery risk analysis i found that the top thre for benefit per order are also the riskiest places to do business. 

I believe that "Perfect Fitness Perfect Rip Deck" & "Field & Stream Sportsman 16 Gun Fire Safe" should be sold at every store and operations should be located just outside these states that bring the most profit. This gives us the opportunity to be close to our money states while minimizing our risk by not being centered in those locations

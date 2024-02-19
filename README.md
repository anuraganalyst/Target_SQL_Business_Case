
![logo](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/e4998160-5b92-4e17-8cd8-759c71dc15ff)
# About Target
Target is a globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation, and an exceptional guest experience that no other retailer can deliver.
# Problem Statement
This project aims to find patterns and gain insights into Target Business Operations in the Brazil Market, by shedding some light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.
# About the Dataset
This particular business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.
The data is available in 8 CSV files:  

1.	customers.csv
   
2.	sellers.csv
	
3.	order_items.csv
	
4.	geolocation.csv
	
5.	payments.csv

6.	reviews.csv
   
7.	orders.csv

8.	products.csv
___________________________________________________________________________________________________________
# The Schema
![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/9d08b8ba-c31f-4553-b8bc-3bd0fbcb6ed3)

# Tools Use
SQL, BigQuery

# Business Insights
![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/5bb5de27-9958-4ea1-a53d-2995323ff29c)
There is an inclined trend in customer orders placed over time. 
From 2016 to 2017, no. of orders went too high in the trend however, after 2017, it slowed down a little.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/b7d434a8-d0dc-419e-b930-d9c2f8359bbc)
The  bar plot shows that there is some seasonality in the no. of orders placed over the given period. From January to August, the orders were in an inclined trend with a slight variation in between. However, the orders drastically fell in September and again went up in the trend.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/e419ca39-57b7-48d7-ab14-b65e2a73f752)
From the plot, we can state that Brazillian customers mostly place their orders during the Afternoon.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/a444613d-94f7-4484-a286-b5dc9bbadaf3)
From the above bar plot, we can state that Sao Paulo(SP) has the highest no. of customers while Roraima(RR) has the lowest no. of customers.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/44ac9b3c-b17c-4c32-b66c-24f5e0e1e2cd)
From 2017 to 2018, the % increase in the cost of orders was highest in January and lowest in August.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/6d8f5574-806a-4207-b193-83d9afb18974)
The total value of the order price is highest in Sao Paulo(SP) and least in Roraima(RR) and Amapa(AP).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/67aa180b-e993-48c1-b58c-1e738e2e63a0)
The average value of customer order prices is highest in Paraiba(PB) and least in Sao Paulo(SP).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/f5797c29-1045-4c24-860e-b22b63429a50)
The total value of order freight is highest for Sao Paulo(SP) and lowest for Roraima(RR).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/a2b5c743-cbaa-426e-a927-e9ca9c225e2e)
The average value of order freight is highest for Roraima(RR) and lowest for Sao Paulo(SP).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/5b1ae2ee-4ed4-425e-9da3-5a29099c3bec)
From the above bar plot based on the 1O order IDs, we can state that delivery time is highest for order id 635c894d068ac37e6e03dc54eccb6189. 

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/eb2f2efb-aa23-477c-9d1b-d4652e93bfbd)
The difference between the estimated delivery time and actual delivery date of the order is highest for order id c830f223aae08493ebecb52f29aa48ca and lowest for order ID b60b53ad0bb7dacacf2989fe27ad567a because the order was delivered 5 days before the estimated delivery date.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/5b186221-4ee8-48e7-a154-9625f3278873)
Out of 27 states of Brazil based on the highest average order freight, the top 5 states are Roraima(RR), Paraiba(PB), Rondonia (RO), Acre(AC), and Piaui(PI).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/b5caab29-893f-4386-b9a7-8e49c802f1d5)
The top 5 states in Brazil's Market, based on the lowest average order freight are Sao Paulo(SP),
Minas Gerais(MG), Parana(PR), Distrito Federal(DF) and Rio De Janerio(RJ).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/cec07165-2bde-4176-95ed-7d0982f837fd)
The top 5 states in Brazil's Market based on the highest average delivery time are Roraima(RR), Amapa(AP), Amazonas(AM), Alagoas(AL), and Para(PA).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/5a7f850a-6f38-4d1b-960a-5ab0dedda0d4)
The top 5 states based on the lowest average delivery time are Sao Paulo(SP), PR(Parana), Minas Gerais(MG), Distrito Federal (DF), and Santa Catarina(SC).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/0fd99cc4-7369-420d-9755-4b107bc7e929)
The top 5 states in Brazil Market where order delivery is as fast as compared to the estimated date of delivery are Alagoas(AL), Maranhao(MA), Sergipe(SE), Espirito Santo(ES), and Bahia(BA).

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/8e58c0ba-93e6-4d85-883b-bc76b649de1a)
From the plot, we can state that the maximum number of orders placed by Brazilian customers is through credit cards.

![image](https://github.com/AnuragAnalyst/Target_SQL_Business_Case/assets/92114108/d659de77-c13d-4020-988b-93ed93f1c64e)
From the above line plot, we can state that the number of orders placed by customers is highest when the installment is 1, and gradually with the increase in no. of installments, the no. of orders declined drastically.

# Recommendations:

Target’s operation in Brazil lasted for 2 years, spanning across 27 states which were driven by customer numbers, shipping efficiency, payment efficiency, and customer satisfaction levels to name a few.

Based on the above analysis, Target should have focused on the below recommendations to make a turnaround in its operations.

•	Out of 27 states, Sao Paulo had the highest number of customers and Roraima was the lowest. Surprisingly, the average time of delivery to customers was highest in Roraima and lowest in Sao Paulo. This could have been the cause of a lack of resources or geographical positioning of customers in the state of Roraima.

•	States like Roraima, Paraiba, and Rondonia had the highest average order freight which is another factor for the declined customer satisfaction level.

•	Credit card was the most popular payment type for customers so analysts at Target should have focused on other payment types like UPI, and debit cards and should have provided some incentives or perks for using other payment types.

•	It was observed that the number of customer orders was maximum when the No. of payment, installments were limited to 1,2 or 3. So, Target should have focused on customer orders of products with lesser no. of installments and should have added some benefits from the customer perspective for products with more no. of installments.
























